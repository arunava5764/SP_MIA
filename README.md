# SP_MIA Artifact — GhostViT (S&P Submission)

This repository contains the artifact for the paper:

**_GhostViT: Revealing and Exploiting Attention Kernel Leakage on GPUs for Side-channel-based Membership Inference in Vision Transformers_**  
*Submitted to the IEEE Symposium on Security and Privacy (S&P).*

This artifact provides a proof-of-concept implementation of our proposed GPU side-channel attack model. The included Jupyter Notebook demonstrates how GPU attention-kernel performance counters can be used to perform Membership Inference (MI) attacks against Vision Transformer (ViT) models.

The notebook reproduces the experimental results reported in **Table 4** of the paper, showing that our attack identifies Google ViT-Base model training samples with **100% accuracy** on NVIDIA Ampere architecture GPUs when fine-tuned on **GTSRB**.

---


