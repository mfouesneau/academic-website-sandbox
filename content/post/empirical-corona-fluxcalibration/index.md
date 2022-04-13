---
title: Empirical flux calibration of Coronagraph observations (part 1)
subtitle: Understanding the problem
date: 2022-04-12T22:05:24.765Z
summary: >
  A problem that requires flux calibration of low spectral resolution time series data.
draft: false
featured: false
authors:
  - admin
tags:
  - modeling
  - python
  - code
categories:
  - empirical
  - modeling
projects:
image:
  filename: featured
  focal_point: Smart
  preview_only: true
---

Matthias Samland (MPIA) came to discuss his calibration of coronagraphic observations with [SPHERE](https://www.eso.org/sci/facilities/paranal/instruments/sphere/overview.html). These are typically spectroscopic data (low-resolution) at a relatively high cadence with and without the occulation of the star for the characterization of planetary systems.

However in constrast with the direct observations, the spectra with the occulation have well established relative calibration but unknown absolute flux scaling. To solve the issue, the traditional way is to observe the star without the occulation before and after the scientific sequence to have an absolute flux reference. He is trying to use the three timeseries to implement a robust flux scaling factors (estimate and uncertainties). One of his first examples showed a an observation affected by clouds during the sequence. This problem is not a simple scaling constant number.

As many discussions, this discussion spent a significant time defining a common vocabulary and phrasing the question.

We discussed directions to explore. I offered to try toy models on my side.