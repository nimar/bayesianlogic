---
title: NET-VISA improvements for regional and aftershock event identification at the IDC
author: Nimar Arora, Stuart Russell, Ronan Le Bras, and Radek Hofman.
layout: post
categories: publications
---

Presented in AGU-2018 (S43B-06).

NET-VISA is a Bayesian approach to solve the network processing problem for nuclear explosion monitoring. At its core is a probabilistic generative model of global-scale seismology which is supplemented with a model of under-water as well as atmospheric events. The model describes
- the generation of events,
- the propagation of energy in multiple phases and mediums,
- the cross-over of energy between mediums,
- the detection of the energy at seismic, hydro-acoustic, and infrasound stations as so-called arrivals,
- the detection of spurious arrivals at the stations due to local noise, clutter sources, as well as coda noise from large events,
- and finally all of the parameters of the arrivals depending on the source.

The model is trained on many months of historical data to fine-tune the priors and the likelihoods. Some of the priors such as the seismic event generation prior, which is trained on ten years of ISC data are static and not trained. Finally, a heuristic search algorithm uses the model to extract the true events and the associations of these events to the arrivals in overlapping thirty minute intervals.

This paper describes a couple of important improvements to the model and the inference algorithm. A new QC (or Quality Control) module now provides additional information about the real time noise levels measured in one-minute intervals. This provides important information such as if the station is saturated due to high noise levels following a powerful earthquake. The model now takes this real time noise information into account when computing the detection probability as well as the SNR (signal-to-noise ratio) levels. On experiments conducted in the aftershock sequence of the 2011 Tohoku earthquake, these new model changes result in a 5% improvement in the overlap with the LEB bulletin.

Another improvement in the model is focused on regional events. The heuristic search algorithm has been extended to propose candidate events at much lower body-wave magnitudes, and also a uniform proposer has been added to the search for events not found by the current inversion-based proposer. Other model improvements help to distinguish noise arrivals from real regional arrivals. As a result of these improvements, the identification of regional events has improved by 10% in terms of overlap with the LEB bulletin on all of 2013 data.

[Presentation](Arora_AGU_Dec_2018.pdf).
