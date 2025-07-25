---
layout: page
title: Research
sidebar_link: true
---
My research typically involves applications of ML, HPC, and Systems. I've enjoyed being able to work on a variety of different projects in diverse domains.

[My Google Scholar](https://scholar.google.com/citations?user=7gZFL2IAAAAJ&hl=en){:target="_blank"}


### Exploring Reproducibility and Efficiency in ML and HPC
#### Argonne Lab & University of Wisconsin Madison | May 2024 - Present
Through a collaboration between Argonne National Labrartory and University of Wisconsin Madison, I am working under [Professor Shivaram Venkataraman](https://shivaram.org/){:target="_blank"}, [Amal Gueroudji](https://www.anl.gov/profile/amal-gueroudji){:target="_blank"}, and [Rob Ross](https://www.anl.gov/profile/robert-b-ross){:target="_blank"}. We are exploring reproducibility and efficiency in HPC and Deep Learning. This has taken the form of designing a new memory efficent approach for training spatiotemporal GNNs on large datasets, studying large-scale LLM preprocessing workflows to implement layered-profiling, and reducing data collection overhead by optimizing Mofka. This work is ongoing. 




### FastPII: Enabling Multi-GPU, Memory-Efficient SWA
#### Freelance | May 2024 - Sep. 2024
In collaboration with [Professor Erin Carrier](https://eecarrier.github.io/){:target="_blank"}, I expanded my past work with [BioPII](https://github.com/OckermanSethGVSU/Bio-PII){:target="_blank"} into [FastPII](https://github.com/OckermanSethGVSU/Fast-PII){:target="_blank"}. FastPII supports multi-GPU, multi-node, and NVIDIA multi-instance GPU sliding window analysis. Testing demonsrate that FastPII consistently outperforms both PyTorch and OpenCV. Our work was accepted for [publication in GPGPU-2025](https://dl.acm.org/doi/10.1145/3725798.3725804){:target="_blank"}.

### Optimizing Computation vs Communication in Distributed Deep Learning Training
#### University of Wisconsin Madison | Feb. 2024 - May 2024
Under [Professor Shivaram Venkataraman](https://shivaram.org/){:target="_blank"}, I explored the trade-offs between computation and communication in Distributed Deep Learning Training, designing an approach that maximized overlap of communication and computation kernels. 



### Exploring Machine Learning for State-of-Charge and State-of-Health Prediction in a Real World Fast-Charging Scenario
#### University of Wisconsin Madison | Aug. 2023 - Feb. 2024
Under [Professor Shivaram Venkataraman](https://shivaram.org/){:target="_blank"}, I performed research which addresses the need for accurate battery state-of-charge (SoC) and state-of-health (SoH) predictions in energy storage systems. We explored SoC prediction in batteries with diverse fast charging policies, resembling real-world scenarios. Key findings include the identification of crucial training features, successful adaptation to unforeseen charging policies using continuous learning, and efficient transition from SoC to SoH prediction without additional development. This work was published in the [Journal of Power Sources](https://www.sciencedirect.com/science/article/pii/S0378775325012546){:target="_blank"}.


--- 

### Harnessing Parallelization for Bayesian Optimization HPC Tuning Searches 
#### Lawrence Berkeley Lab | June 2023 - Feb. 2024
Bayesian optimization (BO) is an inherently sequential workflow that cannot fully utilize modern supercomputers' parallel architecture. Overseen by [Professor Adrián Pérez Diéguez](https://www.linkedin.com/in/aperezdieguez/?originalSubdomain=es){:target="_blank"}, I designed two [GPTune-RCI](https://github.com/gptune/GPTune){:target="_blank"} implementations which enable parallel function evaluation during BO. My parallel BO implementations reduced search time by up to 84% for prominent HPC applications. Further testing also demonstrated up to 77% reduced search time relative to the state-the-art HPC tuner (DeepHyper) which also employs parallelism. Additionally, I implemented a novel parallel multitask learning algorithm which improves both time-to-optimal-solution and final solution quality. This work helped form the basis for a 2025 publication in IJ-HPCA (link to be added when available).


---

### Multi-Model and Multi-Seed Parallel Multi-Task BO 
#### University of California Berkeley | Aug. 2023 - Sep. 2023
I implemented Multi-Model and Multi-Seed Parallel Multi-Task BO into the UC-Berkeley [GPTune](https://github.com/gptune/GPTune){:target="_blank"} codebase. Results show improved-time-to-solution and final parameter selection.

--- 

### Improving the Scalability of Large Scale Image Processing through HPC 
#### Van Andel Institute | May 2023 - July 2023
Overseen by [Professor Brian Haab](https://scholar.google.com/citations?user=mC3JPI8AAAAJ&hl=en){:target="_blank"}, I built a large scale image processing toolkit for biological sliding window analysis. By combining the integral image method with GPU programming, I achieved a speedup of 131,806x on small-scale images and a speedup of 10,901x on large-scale microscopy images compared to the previously used method. Our toolkit is publicly available through the [BioPII](https://github.com/OckermanSethGVSU/Bio-PII){:target="_blank"} PIP package. Our work was recently accepted as a short paper in [IEEE CIBCB 2023](https://cmte.ieee.org/cis-bbtc/wp-content/uploads/sites/172/IEEE_CIBCB_2023_paper_2015.pdf){:target="_blank"}.

--- 

### Predicting COVID-19 Cases Using Twitter Image Data
#### Grand Valley State University | July 2020 - Sep. 2022
Mentored by [Professor Erin Carrier](https://eecarrier.github.io/){:target="_blank"}, I created a project that helped to improve our COVID response through more accurate COVID-19 case count prediction. My work was published in [IEEE ICMLA 2022](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10068950){:target="_blank"}.

--- 

### Improving AI Model Selection in the Domain of Digital Agriculture
#### The Ohio State University | May 2022 - December 2022
Mentored by [Professor Christopher Stewart](https://cse.osu.edu/people/stewart.962){:target="_blank"}, I worked to examine the current neural network benchmarking practices in digital agriculture. I empirically demonstrated the dangers of using classical datasets for digital agriculture neural network benchmarking. Additionally, I designed a GBM which could predict final neural network test set performance  with 87% accuracy using only 3% of the training time required for convergence. I led a team of three in the writing of an [arXiv paper](https://arxiv.org/abs/2208.03315){:target="_blank"}, and later I built my work into a full paper which was accepted for publication at [AAAI 2023](https://openreview.net/forum?id=vBSUoUuAYOA){:target="_blank"}. 


--- 

### Improving the Accessibility of Video Games
#### Grand Valley State University | Sep. 2019 - June 2020 
My freshmen year, I worked as a research assistant for [Professor Ira Woodring](https://www.linkedin.com/in/ira-woodring-3720a47a){:target="_blank"}. I helped perform literature review, summarized and aggregated useful sources, and contributed towards a GameBoy Emulator in C. 

