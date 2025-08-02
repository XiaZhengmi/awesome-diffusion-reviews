# 🌀 Awesome Review Papers on Diffusion Models
A curated list of **review papers and resources** on diffusion models in **machine learning**, **computer vision**, and **generative AI**.

---

## 📚 Review Papers by Year

### 🗓️ 2025

- [Diffusion models in low-level vision: A survey](https://ieeexplore.ieee.org/iel8/34/4359286/10902142.pdf) – **C. He et al.**
- [Efficient diffusion models: A comprehensive survey from principles to practices](https://arxiv.org/pdf/2410.11795) – **Z. Ma et al.**
- [Exploring Diffusion Models for Oral Health Applications: A Conceptual Review](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11104086) – **M. Tabejamaat et al.** 🩺 **Medical**
- [Diffusion model-based image editing: A survey](https://arxiv.org/pdf/2402.17525)
- [Diffusion Models in Recommendation Systems: A Survey](https://arxiv.org/pdf/2501.10548) – **T.R. Wei et al.**
- [Efficient diffusion models: A survey](https://arxiv.org/pdf/2502.06805) – **H. Shen et al.**
- [Comprehensive exploration of diffusion models in image generation: a survey](https://link.springer.com/content/pdf/10.1007/s10462-025-11110-3.pdf) – **H. Chen et al.**

---

### 🗓️ 2024

- [A survey on video diffusion models](https://arxiv.org/pdf/2310.10647) – **Z. Xing et al.**
- [State of the art on diffusion models for visual computing](https://arxiv.org/pdf/2310.07204) – **R. Po et al.**
- [Diffusion models for time-series applications: a survey](https://arxiv.org/pdf/2305.00624) – **L. Lin et al.**
- [Diffusion models for medical image computing: A survey](https://ieeexplore.ieee.org/iel8/5971803/10676339/10676408.pdf) – **Y. Shi et al.** 🩺 **Medical**

---

### 🗓️ 2023

- [Diffusion Models in Vision: A Survey](https://arxiv.org/pdf/2209.04747) – **F.A. Croitoru et al.**
- [Diffusion models: A comprehensive survey of methods and applications](https://arxiv.org/pdf/2209.00796) – **L. Yang et al.**

---

### 🗓️ 2022

- [Diffusion models for medical image analysis: A comprehensive survey](https://arxiv.org/pdf/2211.07804) – **A. Kazerouni et al.** 🩺 **Medical**

---


### 🗓️ 2025 – Medical Diffusion Models

- **Computationally Efficient Diffusion Models in Medical Imaging: A Comprehensive Review** – Abdullah et al. (May 2025)  
  Examines **DDPM**, **LDM**, **WDM** for medical imaging; emphasizes inference speed and high-resolution use cases.

- **A diffusion model for universal medical image enhancement (UniMIE)** – Nature Communications, 2025  
  Unsupervised enhancement method across 13 medical modalities using a **training‑free diffusion model**.

- **Self‑Attention Diffusion Models for Zero‑Shot Biomedical Image Segmentation (ADZUS)** – Hamrani & Godavarty, 2025  
  Self‑attention diffusion enables **zero‑shot segmentation** across multiple anatomical domains.

- **Diffusion‑driven SpatioTemporal Graph KANsformer (DST‑GKAN)** – Li et al., 2025  
  Denoises heterogeneous medical record data via diffusion in support of recommendation systems.

- **Diffusion Models for Computational Neuroimaging: A Survey** – Zhao et al., 2025  
  Overview of **score/SDE‑based diffusion models** applied to neuroimaging tasks (reconstruction, diagnosis, generation).

### 🗓️ 2024 – Medical Diffusion Models

- **MedSegDiff: Medical Image Segmentation with Diffusion Probabilistic Model** – Junde Wu et al., MIDL 2024  
  A **DDPM‑based framework** with dynamic conditional encoding and frequency-based filtering; robust across ultrasound, MRI, and fundus segmentation tasks.

- **Analysing Diffusion Segmentation for Medical Images** – Öttl et al., arXiv (Mar 2024)  
  Provides critical insights into diffusion-based segmentation vs. generation, exploring algorithmic behavior and task-specific design.

- **Latent Diffusion for Medical Image Segmentation (LDSeg)** – Zaman et al., arXiv (Jul 2024)  
  Utilizes **latent diffusion** for efficient and accurate segmentation of multiple organs, offering faster inference and lower memory usage.

- **HiDiff: Hybrid Diffusion for Medical Image Segmentation** – Chen et al., arXiv (Jul 2024)  
  Combines a traditional segmentor and a **Bernoulli diffusion model** (BBDM) for refinement, improving accuracy on brain, polyps, retina datasets.

- **Polyp‑DDPM: Semantic Polyp Synthesis for Enhanced Segmentation** – Dorjsembe et al., arXiv (Feb 2024)  
  Generates synthetic gastrointestinal images conditioned on masks, improves segmentation by adding high-quality annotated data.

- **Seg‑Diff: Anatomically‑Controllable Medical Image Generation** – Konz et al., MICCAI 2024  
  A **mask-guided diffusion model** designed for anatomically plausible image generation (e.g. breast MRI), including training with partial segmentation masks.

- **SDSeg: Stable Diffusion Segmentation for Biomedical Images** – MICCAI 2024  
  A **single-step reverse latent diffusion** model optimized for segmenting medical images—efficient, fast, and competitive with DDIM-based methods.

### 🗓️ 2023 – Medical Diffusion Models

- **BerDiff: Conditional Bernoulli Diffusion Model for Medical Image Segmentation** – Chen et al., arXiv (Apr 2023)  
  A novel **Bernoulli diffusion** approach for generating diverse and accurate segmentation masks in medical imaging.

- **MedSegDiff‑V2: Diffusion-based Medical Image Segmentation with Transformer** – Wu et al., arXiv (Jan 2023)  
  Hybrid **DDPM + Vision Transformer** framework delivering state-of-the-art segmentation results across 20 datasets.

- **Diff‑UNet: A Diffusion Embedded Network for Volumetric Segmentation** – Xing et al., arXiv (Mar 2023)  
  Embeds diffusion into UNet architecture for robust 3D organ segmentation in MRI/CT.

- **DDMM‑Synth: Denoising Diffusion Model for Cross‑modal Medical Image Synthesis** – Li et al., arXiv (Mar 2023)  
  Uses a **DDIM variant** to perform cross-modal synthesis (e.g., MRI→CT) with embedded measurement priors.

- **DiffBoost: Enhancing Medical Image Segmentation via Text‑Guided Diffusion Model** – Zhang et al., arXiv (Oct 2023)  
  Introduces **text-conditioned diffusion** to generate synthetic data that significantly boosts segmentation performance.

### 🗓️ 2022 – Medical Diffusion Models

- **MedSegDiff: Medical Image Segmentation with Diffusion Probabilistic Model** – Wu et al., arXiv (Nov 2022)  
  A **DDPM‑based segmentation** framework with step‑aware encoding and frequency filtering, achieving SOTA results on fundus, MRI, and ultrasound datasets.

- **Diffusion Models for Implicit Image Segmentation Ensembles** – Wolleb et al., MIDL 2022  
  Generates multiple segmentation masks via diffusion sampling and computes **uncertainty maps** for brain tumor segmentation (BRATS2020).

- **Medical Diffusion: Denoising Diffusion Probabilistic Models for 3D Medical Image Generation** – Khader et al., arXiv (Nov 2022)  
  Uses **DDPM** to generate realistic 3D CT/MRI volumes; improves segmentation via synthetic‑data pre‑training.

- **Fast Unsupervised Brain Anomaly Detection and Segmentation with Diffusion Models** – Pinaya et al., MICCAI 2022  
  Employs **latent diffusion** for unsupervised anomaly detection and segmentation on brain MRI without any labeled data.

- **Diffusion Adversarial Representation Learning for Self‑supervised Vessel Segmentation** – Kim & Ye, arXiv (Sept 2022)  
  A **self‑supervised DDIM-based** approach for vessel segmentation using adversarially trained feature representations.

## 🛠 Useful Libraries & Tools

- [Hugging Face Diffusers](https://github.com/huggingface/diffusers)
- [OpenDenoise](https://github.com/OpenDenoise/OpenDenoise)
- [Guided Diffusion (OpenAI)](https://github.com/openai/guided-diffusion)

---

## 🎓 Tutorials & Lecture Series

- [Stanford CS236: Deep Generative Models (2023)](https://cs236.stanford.edu/)
- [Diffusion Models from Scratch – Lilian Weng](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/)
- [YouTube: Intro to Diffusion Models (AssemblyAI)](https://www.youtube.com/watch?v=HoKDTa5jHvg)

---
## 🚀 Quick Start on Google Colab

If you're looking for a simple way to try out diffusion models without setting up a local environment, you can use Google Colab:

- [🧨 Stable Diffusion](https://colab.research.google.com/github/huggingface/notebooks/blob/main/diffusers/stable_diffusion.ipynb)
- [🧨 DDPM](https://colab.research.google.com/github/keras-team/keras-io/blob/master/examples/generative/ipynb/ddpm.ipynb)
- [🧨 DDIM](https://colab.research.google.com/github/huggingface/diffusion-models-class/blob/main/unit4/01_ddim_inversion.ipynb)

Just click the link above and follow the instructions to get started in your browser with free GPU support.

---
## 🤝 Contributing

Feel free to open issues or pull requests to add new review papers or tutorials on diffusion models!
