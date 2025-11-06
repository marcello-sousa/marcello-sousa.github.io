---
layout: page
title: Curriculum Vitae
permalink: /cv/
---

# Marcelo de Sousa

**Email:** marcelo.sousa@usp.br • marcelosousa@tecgraf.puc-rio.br  
**Phone:** +55 (11) 2566-6883 • +55 (11) 98326-7781  
**Location:** Brazil

--- 
<br>

## Professional Summary

Machine Learning specialist with combined experience in **Computer Vision** (SAS sonar, segmentation, detection, diffusion models) and **LLM/Generative AI** (fine-tuning, RAG, LangChain/LangGraph, code generation). Strong track record taking research to production: dataset quality and guardrails, reproducible training, rigorous evaluation (**pass@1**, latency/TTFT, tokens/s), and containerized deployments on NVIDIA GPUs. Client-facing delivery for **Shell** (CV) and **Petrobras** (LLM).

--- 
<br>

## Skills

- **Programming:** Python, Java, C++, C, Lua, SQL, Bash, Git  
- **ML/AI**: JAX, PyTorch, TensorFlow, scikit-learn, OpenCV, Diffusers, Transformers, Physics-Informed Neural Networks (PINNs), automatic differentiation (autodiff), scientific ML for PDEs
- **LLM/GenAI:** Fine-tuning (LoRA/QLoRA, Unsloth), LangChain, LangGraph, Nemo, NIM, prompt design, RAG, tool-calling, evaluation (pass@1, perplexity)  
- **Data & Analysis:** Pandas, NumPy, Matplotlib, Seaborn  
- **Dev & MLOps:** Docker, NVIDIA GPUs (A100/RTX), Triton, Tensor RT, YAML config pipelines, artifact/version management  
- **CV/Diffusion:** Stable Diffusion, ControlNet; semantic/instance segmentation; object detection  
- **Cloud & APIs:** OpenAI / Azure OpenAI, Hugging Face

--- 
<br>

## Work Experience

#### Instituto Tecgraf – PUC-Rio · **LLM / Generative AI Specialist**  
**Feb 2024 – Present** · **Client:** Petrobras (domain code generation & RAG)

- Led fine-tuning of open-source LLMs (e.g., **Mistral 3.2-24B**, **Qwen-Coder-7B**) with **LoRA/QLoRA** and **Unsloth**; curated/canonicalized datasets with guardrails.  
- Built domain **code-generation** pipeline for **Lua** using **LangChain** and **LangGraph** (structured prompts, helper assertions), with automated **Python↔Lua (Lupa)** execution and scoring (**pass@1**, runtime success).  
- Designed **RAG** and tool-calling workflows with deterministic controllers (retries, failure handling) and domain safety constraints for petroleum engineering.  
- Operated across **OpenAI/Azure OpenAI**; enabled local inference via **NIM** and **Nemo**; implemented token accounting, model selection, and throughput/latency benchmarking (incl. **TTFT** warm-ups).  
- Containerized training/inference, reproducible YAML configs, artifact versioning; strict train/dev vs. final GT separation to improve reliability and reduce false safety blocks.

--- 
<br>

**Apr 2023 – Feb 2024 · Client: Shell (Jellyfish project, with Kraken)**

- Collaborated directly with **Shell** on the **Jellyfish** project (with **Kraken**), integrating CV/ML into subsea inspection workflows using an **autonomous underwater vehicle (AUV)** equipped with **Synthetic Aperture Sonar (SAS)**.
- Built **synthetic seafloor SAS datasets** with **Stable Diffusion** and **Latent Diffusion Models** (incl. **ControlNet**), employing domain randomization and sensor-aware noise/backscatter to match real mission conditions.
- Trained and validated **semantic segmentation** and **object detection** models (U-Net variants and modern encoder–decoder backbones) robust to clutter, low SNR, and multipath artifacts—reducing false positives and improving target consistency across missions.
- Designed an end-to-end **data pipeline**: curation/annotation, class balancing, SAS-specific augmentations, real-plus-synthetic mixing, scenario-based evaluation, and reproducible documentation.
- **Productionized CV pipelines** for batch processing of AUV missions (experiment tracking, dataset/model versioning, containerized deployment) and collaborated with Shell/Kraken to integrate outputs with existing analysis tools—bridging advanced research and practical delivery.


--- 
<br>

#### Tribunal de Justiça do Estado de São Paulo · **Escrevente Judiciário**  
**Aug 2012 – Apr 2023**

--- 
<br>

#### E.E. Júlia de Castro Carneiro · **Teacher of Physics and Mathematics**  
**Feb 2007 – Jan 2012**

--- 
<br>

#### Enterusp Pre-University Course · **Teacher of Physics and Mathematics**  
**Mar 2007 – Dec 2007**

--- 
<br>

#### NEA – Youth and Adult Education Center • FEUSP · **Trainee Professor**  
**Sep 2003 – Jun 2006**  
Prepared and reviewed didactic material; participated in research/extension at FEUSP, HU, and Museu Paulista (Museu do Ipiranga); presented at the **12th SIICUSP** (USP international undergraduate research symposium).

--- 
<br>

## Education

**University of São Paulo (USP), Institute of Physics (IFUSP)**  
**Undergraduate degree in Physics (2003–2009)**

--- 
<br>

## Graduate-Level Coursework

**IMPA – Instituto de Matemática Pura e Aplicada**  
- 3D Computer Vision with Neural Networks (Gaussian Splatting and NeRF) — *Luiz Velho, Tiago Novello* (2024)  
- Image Processing and Trends (Multimodal Models and Neural Implicit Representation) — *Luiz Velho* (2022, 2023)  
- Markov Chains — *Milton Jara* (Summer 2023)  
- Introduction to the Theory of Oscillations and Waves — *Alexei A. Mailybaev* (Summer 2023)

**IME-USP – Instituto de Matemática e Estatística (USP)**  
- Introduction to Scientific Machine Learning — Prof. Diego Ribeiro Marcondes (2024)
Focus: Physics-Informed Neural Networks (PINNs) and scientific ML for PDE
- Machine Learning — *Renato Vicente* (2019/2)  
- Introduction to Digital Signal Processing — *Marcelo Queiroz* (2020/1)  
- Applied Probability I — *Claudia Peixoto* (2020/2)  
- Algorithms for Graphs — *Marcel Kenji* (2021/2)  
- Data Structures and Manipulation — *Guilherme Mota* (2022/1)

--- 
<br>

## Mini-Courses

- Tiling on the Plane — *Luiz Henrique de Figueiredo, J. Ezequiel Soto S.* (Summer 2021, Visgraf)

--- 
<br>

## Other Courses

- Bayesian Methods for Machine Learning — *HSE University (Russia)* (2022/2)

--- 
<br>

## Languages

- **Portuguese:** Native  
- **English:** Upper-intermediate (Cultura Inglesa – Level I3, current)

