---
layout: default
title: Projects
description:
---

# Gaussian Processes for Uncertainty Quantification and Estimation in Nonlinear Dynamical Systems

![Hybrid ML-Physics Climate Model](assets/images/hybrid-model-uq.png =250x)

**Authors:** Nishant Yadav and Auroop R. Ganguly
**Abstract:** Hybrid intelligent systems coupling knowledge-based reasoning with data-driven learning are becoming crucial to prediction and discovery in diverse scientific domains - medical diagnosis, decoding protein structures, fluid dynamics, and climate risk assessment, to name a few. Many of these applications are safety-critical, demanding risk-informed decision making. Thus, incorporating uncertainty within these hybrid knowledge-data (KD) systems is critical. Typical Machine Learning methods, however, are uninformative of uncertainty or do so at tremendous cost. In applications such as quantifying risk from climate where knowledge systems are imperfect high dimensional nonlinear models, this is a critical issue. Here using a nontrivial and nonlinear dynamical (NLD) model preferred by climate scientists for inverse problems in climate modeling, we show how Bayesian nonparametric methods, in particular Gaussian Processes (GPs), allow uncertainty quantification and interval estimation in a principled and tractable manner. Further, in many cases, GPs outperform a suite of benchmark point estimation methods as well. Results suggest that this approach to probabilistic learning in hybrid KD models is promising. While the illustrative example is from climate science, the results and insights are generalizable to other NLDs ubiquitous in robotics, biology and economics, among others







<!--
# Optical Flow for Intermediate Frame Interpolation of Multispectral Geostationary Satellite Data


<center><iframe width="560" height="315" src="https://www.youtube.com/embed/NeMXPQw3CJU?controls=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope;" allowfullscreen></iframe></center>

**Authors:** Thomas Vandal & Rama Nemani <br>
**Abstract:** Applications of satellite data in areas such as weather tracking and modeling, ecosystem monitoring, wildfire detection, and landcover change are heavily dependent on the trade-offs related to the spatial, spectral and temporal resolutions of the observations. For instance, geostationary weather tracking satellites are designed to take hemispherical snapshots many times throughout the day but sensor hardware limits data collection. In this work we tackle this limitation by developing a method for temporal upsampling of multi-spectral satellite imagery using optical flow video interpolation deep convolutional neural networks. The presented model, extends Super SloMo (SSM) from single optical flow estimates to multichannel where flows are computed per wavelength band. We apply this technique on up to 8 multispectral bands of GOES-R/Advanced Baseline Imager mesoscale dataset to temporally enhance full disk hemispheric snapshots from 15 minutes to 1 minute. Through extensive experimentation with a multi-terabyte dataset, we show SSM greatly outperforms the linear interpolation baseline and that multichannel optical flows improves performance on GOES/ABI. Furthermore, we discuss challenges and open questions related to temporal interpolation of multispectral geostationary satellite imagery. <br>
**Preprint:** [https://arxiv.org/pdf/1907.12013.pdf](https://arxiv.org/pdf/1907.12013.pdf)

<hr>

# Quantifying Uncertainty in Discrete-Continuous and Skewed Data with Bayesian Deep Learning

![alt text](assets/images/kdd2018-uq-intervals.png "Logo Title Text 1")

**KDD 2018 - Research Track** <br>
**Authors:** Thomas Vandal, Evan Kodra, Sangram Ganguly, Jennifer Dy, Rama Nemani, & Auroop Ganguly <br>
**Abstract:** Deep Learning (DL) methods have been transforming computer vision with innovative adaptations to other domains including climate change. For DL to pervade Science and Engineering (S&EE) applications where risk management is a core component, well-characterized uncertainty estimates must accompany predictions. However, S&E observations and model-simulations often follow heavily skewed distributions and are not well modeled with DL approaches, since they usually optimize a Gaussian, or Euclidean, likelihood loss. Recent developments in Bayesian Deep Learning (BDL), which attempts to capture uncertainties from noisy observations, aleatoric, and from unknown model parameters, epistemic, provide us a foundation. Here we present a discrete-continuous BDL model with Gaussian and lognormal likelihoods for uncertainty quantification (UQ). We demonstrate the approach by developing UQ estimates on “DeepSD’‘, a super-resolution based DL model for Statistical Downscaling (SD) in climate applied to precipitation, which follows an extremely skewed distribution. We find that the discrete-continuous models outperform a basic Gaussian distribution in terms of predictive accuracy and uncertainty calibration. Furthermore, we find that the lognormal distribution, which can handle skewed distributions, produces quality uncertainty estimates at the extremes. Such results may be important across S&E, as well as other domains such as finance and economics, where extremes are often of significant interest. Furthermore, to our knowledge, this is the first UQ model in SD where both aleatoric and epistemic uncertainties are characterized. <br>
**Paper:** [https://www.kdd.org/kdd2018/accepted-papers/view/quantifying-uncertainty-in-discrete-continuous-and-skewed-data-with-bayesia](https://www.kdd.org/kdd2018/accepted-papers/view/quantifying-uncertainty-in-discrete-continuous-and-skewed-data-with-bayesia) <br>
**Code:** [https://github.com/tjvandal/discrete-continuous-bdl](https://github.com/tjvandal/discrete-continuous-bdl)

<hr>

# DeepSD: Generating high resolution climate change projections through single image super-Resolution <br>

![test image size](assets/images/deepsd-network.png){:width="72%"}
![test image size](assets/images/deepsd-lr-hr.png){:width="26%"}

**KDD 2017 - Applied Data Science Track - Runner-up BEST PAPER** <br>
**Authors:** Thomas Vandal, Evan Kodra, Sangram Ganguly, Andy Michaelis, Rama Nemani, and Auroop Ganguly <br>
**Abstract:** The impacts of climate change are felt by most critical systems, such as infrastructure, ecological systems, and power-plants. However, contemporary Earth System Models (ESM) are run at spatial resolutions too coarse for assessing effects this localized. Local scale projections can be obtained using statistical downscaling, a technique which uses historical climate observations to learn a low-resolution to high-resolution mapping. Depending on statistical modeling choices, downscaled projections have been shown to vary significantly terms of accuracy and reliability. The spatio-temporal nature of the climate system motivates the adaptation of super-resolution image processing techniques to statistical downscaling. In our work, we present DeepSD, a generalized stacked super resolution convolutional neural network (SRCNN) framework for statistical downscaling of climate variables. DeepSD augments SRCNN with multi-scale input channels to maximize predictability in statistical downscaling. We provide a comparison with Bias Correction Spatial Disaggregation as well as three Automated-Statistical Downscaling approaches in downscaling daily precipitation from 1 degree (~100km) to 1/8 degrees (~12.5km) over the Continental United States. Furthermore, a framework using the NASA Earth Exchange (NEX) platform is discussed for downscaling more than 20 ESM models with multiple emission scenarios.<br>
**Paper:** [https://www.kdd.org/kdd2017/papers/view/deepsd-generating-high-resolution-climate-change-projections-through-single](https://www.kdd.org/kdd2017/papers/view/deepsd-generating-high-resolution-climate-change-projections-through-single)<br>
**Code:** [https://github.com/tjvandal/deepsd](https://github.com/tjvandal/deepsd)
-->
