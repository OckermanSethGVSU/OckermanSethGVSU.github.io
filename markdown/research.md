---
layout: page
title: Research
sidebar_link: true
---
My research typically involves applications of ML, HPC, and Systems. I've enjoyed being able to work on a variety of different projects in diverse domains.

[My Google Scholar](https://scholar.google.com/citations?user=7gZFL2IAAAAJ&hl=en){:target="_blank"}


## Harnessing Supercomputers for Bayesian Optimization Tuning Searches in HPC
Bayesian optimization (BO) is an inherently sequential workflow that cannot fully utilize modern supercomputers' parallel architecture. Overseen by [Professor Adrián Pérez Diéguez](https://www.linkedin.com/in/aperezdieguez/?originalSubdomain=es){:target="_blank"}, I designed two implementations on top of open-soure [GPTune](https://github.com/gptune/GPTune){:target="_blank"} of the speculation strategy (aka constant liar strategy) which enable parallel function evaluation during BO. My parallel BO implementations reduced search time for [ScaLAPACK PDGEQRF](https://netlib.org/scalapack/explore-html/da/d85/pdgeqrf_8f.html){:target="_blank"} by 73% and [SuperLU_Dist](https://github.com/xiaoyeli/superlu_dist){:target="_blank"} by 84% compared to sequential BO. Further testing also demonstrated reduced search time relative to the state-the-art HPC tuner (DeepHyper) which also employs parallelism - 77% with [SuperLU_Dist](https://github.com/xiaoyeli/superlu_dist){:target="_blank"} and 12% with [ScaLAPACK PDGEQRF](https://netlib.org/scalapack/explore-html/da/d85/pdgeqrf_8f.html){:target="_blank"}. Additionally, I implemented a novel parallel multitask learning algorithm which improves both time-to-optimal-solution and final solution quality. Our work is currently in submission for [IEEE PMBS 2023](https://www.dcs.warwick.ac.uk/pmbs/pmbs/PMBS/Welcome.html){:target="_blank"}. 

## Improving the Scalability of Large Scale Image Processing through HPC
Overseen by [Professor Brian Haab](https://scholar.google.com/citations?user=mC3JPI8AAAAJ&hl=en){:target="_blank"}, I built a large scale image processing toolkit for biological sliding window analysis. By combining the integral image method with GPU programming, I achieved a speedup of 131,806x on small-scale images and a speedup of 10,901x on large-scale microscopy images compared to the previously used method. Our toolkit is publicly available through the [BioPII](https://github.com/OckermanSethGVSU/Bio-PII){:target="_blank"} PIP package. Our work was recently accepted as a short paper in IEEE CIBCB 2023.

 
## Predicting COVID-19 Cases Using Twitter Image Data
Mentored by [Professor Erin Carrier](https://eecarrier.github.io/){:target="_blank"}, I created a project that helped to improve our COVID response through more accurate COVID-19 case count prediction. My work was published in [IEEE ICMLA 2022](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10068950){:target="_blank"}.


## Improving AI Model Selection in the Domain of Digital Agriculture
Mentored by [Professor Christopher Stewart](https://cse.osu.edu/people/stewart.962){:target="_blank"}, I worked to examine the current neural network benchmarking practices in digital agriculture. I empirically demonstrated the dangers of using classical datasets for digital agriculture neural network benchmarking. Additionally, I designed a GBM which could predict final neural network test set performance  with 87% accuracy using only 3% of the training time required for convergence. I led a team of three in the writing of an [arXiv paper](https://arxiv.org/abs/2208.03315){:target="_blank"}, and later I built my work into a full paper which was accepted for publication at [AAAI 2023](https://openreview.net/forum?id=vBSUoUuAYOA){:target="_blank"}. 

## Improving the Accessibility of Video Games
My freshmen year, I worked as a research assistant for [Professor Ira Woodring](https://www.linkedin.com/in/ira-woodring-3720a47a){:target="_blank"}. I helped perform literature review, summarized and aggregated useful sources, and contributed towards a GameBoy Emulator in C. 

