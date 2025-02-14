---
permalink: /projects/
title: "projects"
author_profile: true
redirect_from: 
  - /projects/
  - /projects.html
---
# Projects and Contributions to Science

## Improving Signal by Advanced Acquisition and Image Reconstruction: Spiral and Multi-Echo MRI

I have combined optimal sampling strategies for MR with robust model-based image reconstruction methods. This resulted in performing two first-of-its-kind studies utilizing spiral MRI at challenging ultra-high field conditions (7 Tesla) for rapid high-resolution anatomical (1) and functional imaging (2) with variable echo time and multi-echo sampling. I led the deployment of this work to spiral diffusion imaging via calibration measurements, significantly reducing the hardware requirements for clinical scanners, available as a published open-source image reconstruction workflow, and a software package in the Julia programming language (3).

1.	**Kasper L**, Engel M, Barmet C, Haeberlin M, Wilm BJ, Dietrich BE, Schmid T, Gross S, Brunner DO, Stephan KE, Pruessmann KP. Rapid anatomical brain imaging using spiral acquisition and an expanded signal model. NeuroImage. 2018 Mar 1;168:88–100. 
2.	**Kasper L**, Engel M, Heinzle J, Mueller-Schrader M, Graedel NN, Reber J, Schmid T, Barmet C, Wilm BJ, Stephan KE, Pruessmann KP. Advances in spiral fMRI: A high-resolution study with single-shot acquisition. NeuroImage. 2022 Feb;246:118738
3.	Jaffray, A., Wu, Z., Vannesjo, S.J., Uludağ, K., **Kasper, L.**, 2024. GIRFReco.jl: An Open-Source Pipeline for Spiral Magnetic Resonance Image (MRI) Reconstruction in Julia. Journal of Open Source Software 9, 5877.
n
## Reducing Noise by Mechanistic Measurement, Computational Modeling and Signal Processing
My work aims to reduce noise in MRI by accurately measuring and modeling both MR hardware imperfections (heating/drift) as well as subject-related physiological noise sources (heart rate, breathing, motion). This resulted in the first studies characterizing magnetic field-mediated noise in fMRI utilizing NMR probes (1), and a widely used software package for removing physiological noise sources from fMRI data, the PhysIO Toolbox ((2), >375 citations). This toolbox has been designed for robust processing of peripheral recordings (ECG, pulse oximetry, respiratory bellows) and is continuously extended by innovations in signal processing (3), making it amenable for use in different patient populations.

1. Bollmann S*, **Kasper L***, Vannesjo SJ, Diaconescu AO, Dietrich BE, Gross S, Stephan KE, Pruessmann KP. Analysis and correction of field fluctuations in fMRI data using field monitoring. NeuroImage. 2017 Jul 1;154:92–105.
2. **Kasper L**, Bollmann S, Diaconescu AO, Hutton C, Heinzle J, Iglesias S, Hauser TU, Sebold M, Manjaly Z-M, Pruessmann KP, Stephan KE. The PhysIO Toolbox for Modeling Physiological Noise in fMRI Data. Journal of Neuroscience Methods. 2017 Jan 30;276:56–72.
3. Harrison SJ, Bianchi S, Heinzle J, Stephan KE, Iglesias S, **Kasper L**. A Hilbert-based method for processing respiratory timeseries. NeuroImage. 2021 Apr 15;230:117787.

## Translational Innovations via Open Science and Collaborations
I strongly support open, transparent and reproducible science. Beyond publishing data and analysis code with all my recent publications (see spiral imaging papers in first section), I actively participate in scientific coding challenges for reproducibility of MR methods. Because of my specialization at the interface between technological innovation and application-driven research in my dual postdoctoral position at an MR Engineering group (K. Pruessmann) and the Translational Neuromodeling Unit (K. Stephan), I collaborated on high-impact projects, contributing robust, tailored MR protocol improvements and denoising pipelines for challenging imaging targets, such as the brainstem (1). Furthermore, this interdisciplinary, collaborative work led to me becoming one of the main developers of the Translational Algorithms for Psychiatry-Advancing Science (TAPAS) software collection ((2), > 5000 downloads since 2017), actively supporting the user community on GitHub for the aforementioned PhysIO Toolbox, as well as another software, the UniQC Toolbox for unified quality control in MR sequence development. I also contributed the PhysIO integration into “Neurodesk”, a highly recognized open-source, cloud-ready, and container-based data analysis environment designed for reproducible neuroimaging research (3).
 
1.	Iglesias S, Mathys C, Brodersen KH, Kasper L, Piccirelli M, den Ouden HEM, Stephan KE. Hierarchical Prediction Errors in Midbrain and Basal Forebrain during Sensory Learning. Neuron. 2019 Mar 20; 101(6):1196–1201. 
2.	Frässle S, Aponte EA, Bollmann S, Brodersen KH, Do CT, Harrison OK, Harrison SJ, Heinzle J, Iglesias S, Kasper L, Lomakina EI, Mathys C, Müller-Schrader M, Pereira I, Petzschner FH, Raman S, Schöbi D, Toussaint B, Weber LA, Yao Y, Stephan KE. TAPAS: An Open-Source Software Package for Translational Neuromodeling and Computational Psychiatry. Front Psychiatry. 2021;12:1–25. 
3.	Renton AI, [...], Kasper L, [...], and Bollmann S. Neurodesk: an accessible, flexible and portable data analysis environment for reproducible neuroimaging. Nat Methods. 2024; 21, 804–808.

For a full list of my peer-reviewed publications (43/7/2 total/first/senior author), please see [google scholar]() or [NCBI My Bibliography](https://www.ncbi.nlm.nih.gov/myncbi/lars.kasper.1/bibliography/public/)
