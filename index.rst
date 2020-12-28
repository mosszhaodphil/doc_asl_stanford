===================================================
Arterial spin labeling (ASL) Data Analysis Tutorial
===================================================

This tutorial aims to demonstrate how to obtain perfusion or cerebral blood flow (CBF) using ASL MRI data collected by GE 3T MRI (or PET/MRI) scanners at Stanford University.

Pre-requisite
-------------

1 Download and install `FSL <https://fsl.fmrib.ox.ac.uk/fsl/fslwiki>`_

2 Download and install `dcm2niix <https://github.com/rordenlab/dcm2niix>`_

3 Understand the basics of `ASL <http://mriquestions.com/what-is-asl.html>`_

4 Able to visualize MRI data in NIfTI format


Sample Data
-----------

We will use a sample dataset of a healthy volunteer collected by a GE 3T MRI system. The dataset includes a T1 weighted structural image and an ASL image acquired using GE's product sequence. This dataset can be downloaded here.


.. toctree::
   :maxdepth: 2
   
   data_preparation

   structural_image_processing

   asl_pre_processing

   cbf_quantification




References
==========

If you employ BASIL in your research please reference the article below, plus any others 
that specifically relate to the analysis you have performed:

 [1] *Chappell MA, Groves AR, Whitcher B, Woolrich MW. Variational Bayesian inference for a non-linear forward model. IEEE Transactions on Signal Processing 57(1):223-236, 2009.*

If you employ spatial regularisation (priors) you should ideally reference this article too:

 [2] *A.R. Groves, M.A. Chappell, M.W. Woolrich, Combined Spatial and Non-Spatial Prior for Inference on MRI Time-Series , NeuroImage 45(3) 795-809, 2009.*


  
