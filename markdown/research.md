---
layout: page
title: Research
sidebar_link: true
page_class: research-page
---
My research typically involves applications of ML, HPC, and Systems. I've enjoyed being able to work on a variety of different projects in diverse domains.

<a class="scholar-profile-link" href="https://scholar.google.com/citations?user=7gZFL2IAAAAJ&amp;hl=en" target="_blank" rel="noopener">
  <img src="https://cdn.simpleicons.org/googlescholar/4285F4" alt="" aria-hidden="true">
  <span>View my Google Scholar profile</span>
  <span class="link-arrow" aria-hidden="true">↗</span>
</a>

<div class="timeline">

<section class="project current" markdown="1">
### Supernova: Realistic Billion-Scale Vector Search Benchmarks
<p class="project-meta"><span class="org">University of Wisconsin Madison, Argonne National Laboratory, Qdrant &amp; ETH Zurich</span><span class="date">2026 – Present</span></p>

In collaboration with [Argonne National Laboratory](https://www.anl.gov/){:target="_blank"}, [Qdrant](https://qdrant.tech/){:target="_blank"}, and [ETH Zurich](https://ethz.ch/){:target="_blank"}, I helped develop [Supernova](https://github.com/qdrant-labs/supernova){:target="_blank"}, an open-source toolkit for billion-scale vector search benchmarking, including embedding generation, exact ground-truth computation, and evaluation. Using Supernova, we released three public datasets: [FineWeb-10B](https://huggingface.co/datasets/Qdrant/FineWeb-10B){:target="_blank"}, a 10-billion-document dataset supporting dense, sparse, and filtered search; [PubMed-MV](https://huggingface.co/datasets/Qdrant/PubMed-MV){:target="_blank"}, a multi-vector dataset of PubMed abstracts; and [Coyo-VE](https://huggingface.co/datasets/Qdrant/Coyo-VE){:target="_blank"}, a multimodal image–text embedding dataset.

<div class="pub-links">
  <a href="https://github.com/qdrant-labs/supernova" target="_blank" rel="noopener"><b>Code</b> Supernova</a>
  <a href="https://huggingface.co/datasets/Qdrant/FineWeb-10B" target="_blank" rel="noopener"><b>Data</b> FineWeb-10B</a>
  <a href="https://huggingface.co/datasets/Qdrant/PubMed-MV" target="_blank" rel="noopener"><b>Data</b> PubMed-MV</a>
  <a href="https://huggingface.co/datasets/Qdrant/Coyo-VE" target="_blank" rel="noopener"><b>Data</b> Coyo-VE</a>
  <a href="https://qdrant.tech/blog/qdrant-fineweb-10b-release/" target="_blank" rel="noopener"><b>Blog</b> Qdrant release</a>
</div>
</section>

<section class="project current" markdown="1">
### Characterizing and Scaling Vector Databases on HPC Systems
<p class="project-meta"><span class="org">University of Wisconsin Madison &amp; Argonne National Laboratory</span><span class="date">2024 – Present</span></p>

Working with [Professor Shivaram Venkataraman](https://shivaram.org/){:target="_blank"}, [Amal Gueroudji](https://www.anl.gov/profile/amal-gueroudji){:target="_blank"}, and [Rob Ross](https://www.anl.gov/profile/robert-b-ross){:target="_blank"}, I study the performance and scalability of vector databases (Qdrant, Milvus, and Weaviate) on HPC systems. We published our initial findings in an [SC 2025 workshop paper](https://arxiv.org/abs/2509.12384){:target="_blank"}, followed by a more in-depth examination in [*When More Cores Hurts*](https://arxiv.org/abs/2606.08950){:target="_blank"}.

<div class="pub-links">
  <a href="https://arxiv.org/abs/2606.08950" target="_blank" rel="noopener"><b>Preprint</b> When More Cores Hurts</a>
  <a href="https://arxiv.org/abs/2509.12384" target="_blank" rel="noopener"><b>Paper</b> SC '25 Workshop</a>
  <a href="/assets/posters/vector-db-scaling-2026.pdf" target="_blank" rel="noopener"><b>Poster</b> SC '26</a>
</div>
</section>

<section class="project" markdown="1">
### Memory-Efficient Distributed Training for Spatiotemporal GNNs
<p class="project-meta"><span class="org">University of Wisconsin Madison &amp; Argonne National Laboratory</span><span class="date">May 2024 – 2025</span></p>

Under [Professor Shivaram Venkataraman](https://shivaram.org/){:target="_blank"} and [Amal Gueroudji](https://www.anl.gov/profile/amal-gueroudji){:target="_blank"}, I designed and implemented a novel batching technique that reduced memory overhead and improved scalability in spatiotemporal GNNs (ST-GNNs). My work was published as an [SC-2025 conference paper](https://arxiv.org/abs/2507.11683){:target="_blank"}, and the techniques are fully integrated into the open-source package [PyTorch-Geometric Temporal](https://github.com/benedekrozemberczki/pytorch_geometric_temporal){:target="_blank"}.

<div class="pub-links">
  <a href="https://arxiv.org/abs/2507.11683" target="_blank" rel="noopener"><b>Paper</b> SC '25</a>
  <a href="https://github.com/benedekrozemberczki/pytorch_geometric_temporal" target="_blank" rel="noopener"><b>Code</b> PyG Temporal</a>
  <a href="/assets/posters/dask-gnn-2024.pdf" target="_blank" rel="noopener"><b>Poster</b> Argonne '24</a>
</div>
</section>

<section class="project" markdown="1">
### HPC-Tailored Workflow Profiling with Flowcept and Mofka
<p class="project-meta"><span class="org">Argonne National Laboratory</span><span class="date">2024 – 2025</span></p>

With [Amal Gueroudji](https://www.anl.gov/profile/amal-gueroudji){:target="_blank"} and [Rob Ross](https://www.anl.gov/profile/robert-b-ross){:target="_blank"}, I aided in integrating [Mofka](https://mofka.readthedocs.io/en/latest/){:target="_blank"}, an HPC-tailored streaming service, into [Flowcept](https://github.com/ORNL/flowcept/tree/main){:target="_blank"}, enabling more efficient profiling of HPC workloads. Our findings are described in a [Frontiers in High Performance Computing journal paper](https://www.frontiersin.org/journals/high-performance-computing/articles/10.3389/fhpcp.2025.1638203/full){:target="_blank"}.

<div class="pub-links">
  <a href="https://www.frontiersin.org/journals/high-performance-computing/articles/10.3389/fhpcp.2025.1638203/full" target="_blank" rel="noopener"><b>Paper</b> Frontiers in HPC '25</a>
  <a href="/assets/posters/flowcept-mofka-2025.pdf" target="_blank" rel="noopener"><b>Poster</b> GCASR '25</a>
</div>
</section>

<section class="project" markdown="1">
### FastPII: Enabling Multi-GPU, Memory-Efficient SWA
<p class="project-meta"><span class="org">Freelance</span><span class="date">May 2024 – Sep. 2024</span></p>

In collaboration with [Professor Erin Carrier](https://eecarrier.github.io/){:target="_blank"}, I expanded my past work with [BioPII](https://github.com/OckermanSethGVSU/Bio-PII){:target="_blank"} into [FastPII](https://github.com/OckermanSethGVSU/Fast-PII){:target="_blank"}. FastPII supports multi-GPU, multi-node, and NVIDIA multi-instance GPU sliding window analysis. Testing demonstrates that FastPII consistently outperforms both PyTorch and OpenCV. Our work was accepted for [publication in GPGPU-2025](https://dl.acm.org/doi/10.1145/3725798.3725804){:target="_blank"}.

<div class="pub-links">
  <a href="https://dl.acm.org/doi/10.1145/3725798.3725804" target="_blank" rel="noopener"><b>Paper</b> GPGPU '25</a>
  <a href="https://github.com/OckermanSethGVSU/Fast-PII" target="_blank" rel="noopener"><b>Code</b> FastPII</a>
</div>
</section>

<section class="project" markdown="1">
### Optimizing Computation vs Communication in Distributed Deep Learning Training
<p class="project-meta"><span class="org">University of Wisconsin Madison</span><span class="date">Feb. 2024 – May 2024</span></p>

Under [Professor Shivaram Venkataraman](https://shivaram.org/){:target="_blank"}, I explored the trade-offs between computation and communication in Distributed Deep Learning Training, designing an approach that maximized overlap of communication and computation kernels.
</section>

<section class="project" markdown="1">
### Exploring Machine Learning for State-of-Charge and State-of-Health Prediction in a Real World Fast-Charging Scenario
<p class="project-meta"><span class="org">University of Wisconsin Madison</span><span class="date">Aug. 2023 – Feb. 2024</span></p>

Under [Professor Shivaram Venkataraman](https://shivaram.org/){:target="_blank"}, I performed research which addresses the need for accurate battery state-of-charge (SoC) and state-of-health (SoH) predictions in energy storage systems. We explored SoC prediction in batteries with diverse fast charging policies, resembling real-world scenarios. Key findings include the identification of crucial training features, successful adaptation to unforeseen charging policies using continuous learning, and efficient transition from SoC to SoH prediction without additional development. This work was published in the [Journal of Power Sources](https://www.sciencedirect.com/science/article/pii/S0378775325012546){:target="_blank"}.

<div class="pub-links">
  <a href="https://www.sciencedirect.com/science/article/pii/S0378775325012546" target="_blank" rel="noopener"><b>Paper</b> J. Power Sources '25</a>
</div>
</section>

<section class="project" markdown="1">
### Harnessing Parallelization for Bayesian Optimization HPC Tuning Searches
<p class="project-meta"><span class="org">Lawrence Berkeley Lab</span><span class="date">June 2023 – Feb. 2024</span></p>

Bayesian optimization (BO) is an inherently sequential workflow that cannot fully utilize modern supercomputers' parallel architecture. Overseen by [Professor Adrián Pérez Diéguez](https://www.linkedin.com/in/aperezdieguez/?originalSubdomain=es){:target="_blank"}, I designed two [GPTune-RCI](https://github.com/gptune/GPTune){:target="_blank"} implementations which enable parallel function evaluation during BO. My parallel BO implementations reduced search time by up to 84% for prominent HPC applications. Further testing also demonstrated up to 77% reduced search time relative to the state-the-art HPC tuner (DeepHyper) which also employs parallelism. Additionally, I implemented a novel parallel multitask learning algorithm which improves both time-to-optimal-solution and final solution quality. This work formed the basis for a [2025 publication in IJ-HPCA](https://journals.sagepub.com/doi/abs/10.1177/10943420251362001){:target="_blank"}.

<div class="pub-links">
  <a href="https://journals.sagepub.com/doi/abs/10.1177/10943420251362001" target="_blank" rel="noopener"><b>Paper</b> IJHPCA '25</a>
  <a href="https://github.com/gptune/GPTune" target="_blank" rel="noopener"><b>Code</b> GPTune</a>
</div>
</section>

<section class="project" markdown="1">
### Multi-Model and Multi-Seed Parallel Multi-Task BO
<p class="project-meta"><span class="org">University of California Berkeley</span><span class="date">Aug. 2023 – Sep. 2023</span></p>

I implemented Multi-Model and Multi-Seed Parallel Multi-Task BO into the UC-Berkeley [GPTune](https://github.com/gptune/GPTune){:target="_blank"} codebase. Results show improved-time-to-solution and final parameter selection.
</section>

<section class="project" markdown="1">
### Improving the Scalability of Large Scale Image Processing through HPC
<p class="project-meta"><span class="org">Van Andel Institute</span><span class="date">May 2023 – July 2023</span></p>

Overseen by [Professor Brian Haab](https://scholar.google.com/citations?user=mC3JPI8AAAAJ&hl=en){:target="_blank"}, I built a large scale image processing toolkit for biological sliding window analysis. By combining the integral image method with GPU programming, I achieved a speedup of 131,806x on small-scale images and a speedup of 10,901x on large-scale microscopy images compared to the previously used method. Our toolkit is publicly available through the [BioPII](https://github.com/OckermanSethGVSU/Bio-PII){:target="_blank"} PIP package. Our work was recently accepted as a short paper in [IEEE CIBCB 2023](https://cmte.ieee.org/cis-bbtc/wp-content/uploads/sites/172/IEEE_CIBCB_2023_paper_2015.pdf){:target="_blank"}.

<div class="pub-links">
  <a href="https://cmte.ieee.org/cis-bbtc/wp-content/uploads/sites/172/IEEE_CIBCB_2023_paper_2015.pdf" target="_blank" rel="noopener"><b>Paper</b> IEEE CIBCB '23</a>
  <a href="https://github.com/OckermanSethGVSU/Bio-PII" target="_blank" rel="noopener"><b>Code</b> BioPII</a>
</div>
</section>

<section class="project" markdown="1">
### Predicting COVID-19 Cases Using Twitter Image Data
<p class="project-meta"><span class="org">Grand Valley State University</span><span class="date">July 2020 – Sep. 2022</span></p>

Mentored by [Professor Erin Carrier](https://eecarrier.github.io/){:target="_blank"}, I created a project that helped to improve our COVID response through more accurate COVID-19 case count prediction. My work was published in [IEEE ICMLA 2022](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10068950){:target="_blank"}.

<div class="pub-links">
  <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10068950" target="_blank" rel="noopener"><b>Paper</b> IEEE ICMLA '22</a>
</div>
</section>

<section class="project" markdown="1">
### Improving AI Model Selection in the Domain of Digital Agriculture
<p class="project-meta"><span class="org">The Ohio State University</span><span class="date">May 2022 – Dec. 2022</span></p>

Mentored by [Professor Christopher Stewart](https://cse.osu.edu/people/stewart.962){:target="_blank"}, I worked to examine the current neural network benchmarking practices in digital agriculture. I empirically demonstrated the dangers of using classical datasets for digital agriculture neural network benchmarking. Additionally, I designed a GBM which could predict final neural network test set performance with 87% accuracy using only 3% of the training time required for convergence. I led a team of three in the writing of an [arXiv paper](https://arxiv.org/abs/2208.03315){:target="_blank"}, and later I built my work into a full paper which was accepted for publication at [AAAI 2023](https://openreview.net/forum?id=vBSUoUuAYOA){:target="_blank"}.

<div class="pub-links">
  <a href="https://openreview.net/forum?id=vBSUoUuAYOA" target="_blank" rel="noopener"><b>Paper</b> AAAI '23</a>
  <a href="https://arxiv.org/abs/2208.03315" target="_blank" rel="noopener"><b>Preprint</b> arXiv</a>
</div>
</section>

<section class="project" markdown="1">
### Improving the Accessibility of Video Games
<p class="project-meta"><span class="org">Grand Valley State University</span><span class="date">Sep. 2019 – June 2020</span></p>

My freshman year, I worked as a research assistant for [Professor Ira Woodring](https://www.linkedin.com/in/ira-woodring-3720a47a){:target="_blank"}. I helped perform literature review, summarized and aggregated useful sources, and contributed towards a GameBoy Emulator in C.
</section>

</div>
