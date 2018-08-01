# Bayesian Logic, Inc.

This is a repository for the website of Bayesian Logic, Inc. To add new publications simply add them to the `_posts/` directory (see an existing example for frontmatter). The corresponding files can be uploaded to the `publications/` subdirectory.

## Local Testing

### Install Jekyll on Ubuntu

    sudo apt-get install ruby ruby-dev build-essential
    echo '# Install Ruby Gems to ~/.gems' >> ~/.bashrc
    echo 'export GEM_HOME=$HOME/.gems' >> ~/.bashrc
    echo 'export PATH=$HOME/.gems/bin:$PATH' >> ~/.bashrc
    source ~/.bashrc
    gem install jekyll bundler

### Run Jekyll in current directory

    jekyll serve

The website can then be viewed at http://localhost:4000

## Disqus comments

Add the following to the front matter of any post that should have
comments disabled:

    comments: False

Also, add the following to config.yml to enable disqus:

    disqus:
      shortname: www-bayesianlogic-com
