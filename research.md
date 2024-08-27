---
layout: research
title: 
date: 2020-11-20 
pgp: true 
---

<div class="jumbotron" style="background-color:#E8E5DA;">
  <h1 class="display-5">Optimising Laser Powder Bed Fusion to identify stable manufacturing regimes</h1>
  <p class="lead">Advisors: Dr. Sameh Tawfick and Dr. Elif Ertekin</p>
  <p>January 2022 - <i>present</i></p>
  <img src="/assets/img/research/am.png" alt="..." class="center">
  <hr class="my-4">
  <ul>
    <li> Built unsupervised image analysis techniques to help segmentation of cross-section images of single-track melt pools. </li>
    <li> Trained a neural network to perform the segmentation automatically with an accuracy greater than 99% and extract the melt pool features. </li>
    <li> Using Bayesian optimisation to exploit the experimental results and find the region of the parameter space in conduction mode, while employing the normalised enthalpy to transition across different materials systems. </li>
    <li> Published software (Python package) for image analysis of melt pool cross-sections. </li>
    <li> Working in collaboration with MIT and NIST to develop standards for the industry. </li>
  </ul>
  <p> <b>Links to the software:</b> </p>
  <a class="btn btn-primary btn-md" href="https://github.com/nanoMFG/lpbf-cs-image-analysis/" target="_blank" role="button" style="background-color:#648DE5;color:#FFFFFF">LPBF Cross Sectional Image Analysis Software</a>
</div>
<div class="jumbotron" style="background-color:#E8E5DA;">
  <h1 class="display-5">Graphene Recipes for Synthesis of High-Quality Materials (Gr-ResQ)</h1>
  <p class="lead">Advisors: Dr. Sameh Tawfick and Dr. Elif Ertekin</p>
  <p>September 2019 - <i>present</i></p>
  <img src="/assets/img/research/gresq.png" alt="..." class="center">
  <hr class="my-4">
  <ul>
    <li> Built a chemical vapour deposition system and synthesised graphene. Varied specific reaction parameters - such as total gas flow rate and growth duration - using design of experiments and achieved high repeatability in the quality of graphene. </li>
    <li> Performed active learning using Bayesian optimisation to exploit the experimental results and facilitate more efficient discovery of complex synthesis recipes. </li>
    <li> Designed a custom kernel for a Gaussian process model to simulate the CVD process and explain the balance between the governing physical processes. </li>
    <li> Published software on nanoHUB to enable crowd-sourcing of synthesis recipes and analysis of microscopy images and Raman spectra, with more than 1000 total users worldwide. </li>
    <li> Automated segmentation of scanning electron microscopy images of graphene with a deep neural network with 94.5% pixel-wise accuracy using only 93 training images. Published the trained model, compatible with <a href="https://deepimagej.github.io/">deepImageJ</a>, at <a href="https://doi.org/10.5281/zenodo.7063245">doi.org/10.5281/zenodo.7063245</a>. </li>
  </ul>
  <p> <b>Links to the software:</b> </p>
  <a class="btn btn-primary btn-md" href="https://nanohub.org/tools/gresq" target="_blank" role="button" style="background-color:#648DE5;color:#FFFFFF">Gr-ResQ Tool</a>
  <a class="btn btn-primary btn-md" href="https://nanohub.org/tools/graft" target="_blank" role="button" style="background-color:#648DE5;color:#FFFFFF">Graphene Raman Fitting Tool</a>
  <a class="btn btn-primary btn-md" href="https://nanohub.org/tools/imagesegment" target="_blank" role="button" style="background-color:#648DE5;color:#FFFFFF">SEM Image Segmentation Tool</a>
</div>
<div class="jumbotron" style="background-color:#E8E5DA;">
  <h1 class="display-5">Statistical modelling for design optimisation & performance validation of the Fuse series printers</h1>
  <p class="lead">Manager: Ryan Buck, Optics and Thermal Systems team, Formlabs Inc.</p>
  <p>September 2023 - December 2023</p>
  <img src="/assets/img/research/formlabs.png" alt="..." class="center">
  <hr class="my-4">
  <ul>
    <li> Developed a Standard Operating Procedure (SOP) for collecting seed data using design of experiments to support a data-driven model. </li>
    <li> Built an active-learning model to predict the EAB, UTS, and modulus, along with experimental uncertainty as a function of optical and thermal inputs for the SLS printers for PA12. Developed tailored acquisition functions to guide the print setting optimisation based on special requirements. </li>
    <li> This model explained the variability across printers, and is guiding optimisation efforts for the next generation of printers. </li>
    <li> The method, agnostic of the material system provided to it, is also being used to build similar models for other materials with little-to-no tuning by the engineers. </li>
    <li> Characterised thermal non-uniformity within the print volume and built a predictive model for the same as a function of the optical and thermal inputs. </li>
  </ul>
</div>