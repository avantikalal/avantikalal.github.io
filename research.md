layout: page
---
title: Research
subtitle: Decoding the human genome through AI.
---

### Overview
My research mission is to model large-scale, multimodal genomic data to understand how the human genome functions in both health and disease. By building models that can interpret the complex regulatory grammar of DNA, we can discover the underlying causes of complex diseases and accelerate the discovery of novel, life-saving treatments.

---

## 1. Foundation Models for Genomics
I develop "DNA Foundation Models" that learn the evolutionary and functional language of the genome from massive datasets. For example, [Decima](https://www.biorxiv.org/content/10.1101/2024.10.09.617507v1) is a state-of-the-art foundation model designed to predict gene expression directly from DNA sequences with unprecedented cell-type specificity. By leveraging large-scale single-cell genomic data, Decima learns to predict the functional impact of genetic mutations at a high resolution, revealing how genetic variants drive disease pathology across different cells in the human body.

---

## 2. Generative AI for DNA
Beyond prediction, I am interested in synthesis - engineering DNA sequences to achieve better therapeutic outcomes. For example:

* **[regLM](https://genome.cshlp.org/content/early/2024/09/24/gr.279142.124.abstract):** As the first autoregressive language model trained specifically to design human regulatory DNA, regLM treats genomic sequences as a structured language. It can generate synthetic promoters and enhancers that follow the "syntax" of the human genome. This work demonstrated that a language model can design realistic functional genomic elements with tailored regulatory properties, opening new doors for synthetic biology.
* **[Polygraph](https://link.springer.com/article/10.1186/s13059-025-03584-9):** As generative models become more powerful, validating their output is essential. Polygraph is a benchmarking framework that uses a suite of biological "filters" and deep learning evaluators to test whether AI-designed regulatory sequences are biologically realistic.

---

## 3. Scalable Infrastructure for Genomic AI
To bridge the gap between AI research and widespread biological application, I build high-performance software frameworks that enable biologists to easily adopt AI.

* **[gReLU](https://www.nature.com/articles/s41592-025-02868-z):** Developed at Genentech, gReLU is a comprehensive software ecosystem designed to standardize and accelerate the training of genomic deep learning models. It provides modular components for data handling, model architecture, and interpretability, allowing researchers to move seamlessly from raw DNA sequences to biologically meaningful insights.
* **[RAPIDS for Single-Cell Genomics](https://www.biorxiv.org/content/10.1101/2022.05.26.493607v1.abstract):** At NVIDIA, I led the development of GPU-accelerated workflows for single-cell analysis. We reduced data processing times from hours to seconds, enabling the real-time analysis of datasets containing millions of cells.

---

## 4. Improving Genomic Data Quality with Deep Learning
Meaningful discovery requires high-fidelity data. At NVIDIA, I worked on deep learning methods to clean and enhance genomic data, ensuring that biological signals are not lost in technical noise. These include [AtacWorks](https://www.nature.com/articles/s41467-021-21765-5), a deep learning tool to denoise epigenomic data, as well as deep learning models for [reference-free error correction](https://www.biorxiv.org/content/10.1101/2021.06.28.450238v3.abstract) in long-read sequencing data.

---

## 5. Translation: AI in the Clinic & Drug Discovery
Ultimately, my work aims to translate insights derived from AI models into therapeutic impact. At **insitro** and **Genentech**, I have worked on applying AI models to identify novel drug targets and design therapeutic molecules. During my postdoctoral work at Stanford University, I developed AI models to [predict patient outcomes](https://www.nature.com/articles/s41467-018-06921-8) and discover [mutational signatures](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009119) using personalized genomic data from cancer patients.

 By [clustering patients](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009119) based on these signatures rather than just tumor location, we can identify subgroups that may respond similarly to specific therapies, advancing the goal of precision oncology.
