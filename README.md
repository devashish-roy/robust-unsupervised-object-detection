# Towards robust unsupervised object detection
A Multi-Layer Framework Using Open-Vocabulary Zero-Shot Detector, Vision-Language Models and Segmentation for Data Annotation

## Overview
This repository contains the code, data, and documentation for my Master’s thesis:
**"Towards robust unsupervised object detection - A Multi-Layer Framework Using Open-Vocabulary Zero-Shot Detector, Vision-Language Models and Segmentation for Data Annotation"**
at *Luleå University of Technology, Department of Computer Science, Electrical and Space Engineering*, supervised by *Prof. Homam Mokayed*.

The aim of this thesis was to design, implement, and evaluate an unsupervised multi-layer framework for robust aerial object detection, which reduces reliance on manual annotation by leveraging open-vocabulary zero-shot detectors, vision-language models, and segmentation techniques to generate high-quality pseudo-labels. It explores how to combine detection, filtering, and segmentation techniques to produce accurate, unsupervised annotations.

---

## Abstract
> Object detection has witnessed significant progress in recent years; however, its application in the Nordic region has remained limited. This is largely due to region’s unique geographical and environmental characteristics which creates a significant domain gap between available aerial datasets and the conditions existing in Nordic regions. Additionally, there is notable scarcity of annotated data in this region, which further limits the industrial adoption of current object detection methods. This master’s thesis addresses these challenges by proposing a multi-layered framework that leverages state-of-the-art pre-trained models such as Grounding DINO, SAM2, and Vision-Language Models such as Gemma3 and PaliGemma2, to generate high-quality pseudo-labels from unannotated data in an unsupervised manner. These pseudo-labels can then be used for training, evaluation, and fine-tuning of object detection models, ultimately supporting the development of robust and scalable object detection solutions.

---

## 🗂️ Contents
- `src/` — source code
- `data/` — https://nvd.ltu-ai.dev/
- `notebooks/` — Jupyter notebooks (if any)
- `results/` — output files, figures, or reports
- `thesis.pdf` — the final thesis document
