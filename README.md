# cdkgc
**cdkgc** is an open-source software development framework for defining google cloud infrastructure in code using familiar programming languages and rich object-oriented APIs.
cdkgc apps synthesize into standard Cloud Deployment Manager templated which can be applied to google cloud account.\


## Overview

**cdkgc** apps are programs written in one of the supported programming
languages. They are structured as a tree of
[constructs](https://github.com/aws/constructs).

The root of the tree is an `App` construct. Within an app, users define any
number of configurations (classes that extend the `Configuration` class). Each configurations is
synthesized into a separate google cloud configuration file sutable for creating deployment with Cloud Deployment Manager. 
