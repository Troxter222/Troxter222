# Ali

Contact: troxtergrif@gmail.com

I'm working towards becoming a research engineer, diving deep into machine learning, physics, and systems programming. My aim? Build models that don't just crunch numbers—they actually get the laws of physics. I'm convinced AI's future hinges on solid math, interpretability, and leaving those mysterious "black box" models behind.

---

## Research & Engineering Interests

* Physics-aware AI and PINNs: I train neural nets that have to follow the rules set by PDEs and ODEs, weaving math directly into machine learning.
* Scientific computing and optimization: I work on speeding up simulations and crafting optimizers with strong mathematical foundations.
* Data pipelines & ML Ops: I love streamlining preprocessing—making tools that cut boilerplate and turbocharge training.
* Low-level & systems engineering: Writing tight, efficient code, tweaking kernels, and really understanding how algorithms run right on the hardware.

---

## Projects

### PsiLogic Optimizer
* Designed and tested PsiLogic, a deep learning optimizer I built to be a stable alternative to AdamW.
* Checked how fast it converges and benchmarked it against big names like BERT, ViT, and GPT-2.
* Zeroed in on keeping gradients stable and cutting training time—without sacrificing generation quality.

### FastNum
* Built a minimalist Python library that auto-detects input types (images, text, categories, batches) and turns them into NumPy arrays, no setup needed.
* Added a safe tokenization pipeline, nailed down deterministic text decoding with isolated padding.
* Streamlined preprocessing—tokenization, padding, one-hot encoding, image normalization—all collapsed into one API call.

### DeepFlow (PINNs)
* Modeled fluid dynamics solving inverse problems, keeping PDE constraints front and center.
* Looked at the tradeoffs between pure data-driven nets, physics-informed setups, and old-school analytical/CFD benchmarks.
* Tested periodic activation functions (SIREN) for handling complex physical fields.

### MUG Drug Design
* Used transformer-based latent models for molecular generation and structural design.
* Built custom scoring functions locked to chemical validity, docking scores, and ADMET properties.
* Pushed for scientific reproducibility and a flexible, modular architecture.

---

## Tech Stack & Workflow

* **Core Languages:** ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
* **Deep Learning & Math:** ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
* **Development Environment:** Arch Linux (running on a custom-optimized kernel).
* **Core Philosophy:** I stick to fundamentals. I often derive gradients by hand and write system simulators from scratch to ensure a deep, uncompromising grasp of the underlying mathematics.

---

If the projects or ideas resonate, just drop me a line.
