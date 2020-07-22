---
layout: post
title:  "Creation of a separate repository for the Basic Model Interface"
date:   2020-07-22 13:50:00 -0600
categories: website
excerpt: >-
  The pyDeltaRCM gets a separate repo for BMI support.
---


We have separated out the [Basic Model Interface (BMI)](https://bmi.readthedocs.io/en/latest/?badge=latest) implementation of the [pyDeltaRCM model](https://deltarcm.org/pyDeltaRCM/) into a new repository, named [BMI_pyDeltaRCM](https://github.com/DeltaRCM/BMI_pyDeltaRCM).
Our hope is that separating the BMI from our core model will allow us to keep the login inside the pyDeltaRCM model clearer and more flexible to extension, while still supporting the BMI.
With this change, we have brought the BMI up to the version 2.0 specifications outlined by the Community Surface Dynamics Modeling System; we hope the model will be useful for some folks there!
