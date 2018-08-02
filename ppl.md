---
layout: page
# see the following for help https://github.com/jekyll/minima
title: PPL
---

A **Probabilistic Programming Language** in simple terms is any programming language which produces probabilistic output. Or in other words, a programming language whose output follows a probability distribution. Typical uses of such a language are to *query* samples from the distribution, or to *infer* the posterior distribution, or mode, of latent variable(s) given some observations.

## Reading list

### [BLOG](https://bayesianlogic.github.io/)

[BLOG: Probabilistic models with unknown objects]({{site.url}}/ppl/blog-probabilistic-models-with-unknown-objects.pdf) by Brian Milch , Bhaskara Marthi , Stuart Russell , David Sontag , Daniel L. Ong , Andrey Kolobov (2005)

    @INPROCEEDINGS{Milch05blog:probabilistic, author = {Brian Milch and Bhaskara Marthi and Stuart Russell and David Sontag and Daniel L. Ong and Andrey Kolobov}, title = {Blog: Probabilistic models with unknown objects}, booktitle = {In IJCAI}, year = {2005}, pages = {1352--1359}}

### IBAL

[IBAL: A Probabilistic Rational Programming Language]({{site.url}}/ppl/ibal-a-probabilistic-rational-programming-language.pdf)  by Avi Pfeffer (2001)

    @INPROCEEDINGS{Pfeffer01ibal:a, author = {Avi Pfeffer}, title = {IBAL: A Probabilistic Rational Programming Language}, booktitle = {In Proc. 17th IJCAI}, year = {2001}, pages = {733--740}, publisher = {Morgan Kaufmann Publishers}}

### Church

[Church: A language for generative models]({{site.url}}/ppl/church-a-language-for-generative-models.pdf) by Noah D. Goodman , Vikash K. Mansinghka , Daniel M. Roy , Keith Bonawitz , Joshua B. Tenenbaum (2008)

    @INPROCEEDINGS{Goodman08church:a, author = {Noah D. Goodman and Vikash K. Mansinghka and Daniel M. Roy and Keith Bonawitz and Joshua B. Tenenbaum}, title = {Church: A language for generative models}, booktitle = {In UAI}, year = {2008}, pages = {220--229}}

### BUGS

[WinBUGS - a Bayesian modelling framework: concepts, structure, and extensibility]({{site.url}}/ppl/winbugs-a-bayesian-modelling-framework-concepts-structure-and-extensibility.pdf) by  David J. Lunn , Andrew Thomas , Nicky Best , David Spiegelhaltery (2000)

    @ARTICLE{Lunn00winbugs-, author = {David J. Lunn and Andrew Thomas and Nicky Best and David Spiegelhaltery}, title = {WinBUGS - a Bayesian modelling framework: concepts, structure, and extensibility}, journal = {Statistics and Computing}, year = {2000}, pages = {325--337}}

### [Stan](http://mc-stan.org)

[Stan: A probabilistic programming language for Bayesian inference and optimization]({{site.url}}/ppl/stan-a-probabilistic-programming-language-for-bayesian-inference-and-optimization.pdf) by Andrew Gelman, Daniel Lee, Jiqiang Guo (2015).

### [Infer.net](https://www.microsoft.com/en-us/research/project/infernet/)

[Expectation Propagation for Approximate Bayesian Inference]({{site.url}}/ppl/expectation-propagation-for-approximate-bayesian-inference.pdf) by Thomas P Minka

## Challenge problems

### Seismic 2D

The goal of this problem is to detect and localize seismic events on a simulated two-dimensional world (the surface of a perfect sphere) given signals collected over a fixed time interval at a number of seismic stations. This is a simplification of the real problem (Arora et al., 2013), and is designed as a challenge problem for research in probabilistic programming languages.

  - [Description](https://bitbucket.org/nimar/seismic-2d/downloads/description.pdf)
  - [Source Code](https://bitbucket.org/nimar/seismic-2d/src/master/)
  - [Data](https://bitbucket.org/nimar/seismic-2d/downloads/data.tar.gz).
