# ViT Architecture Benchmark for Chili Leaf Disease Classification

## Overview

Chili plant disease detection is a critical component for enhancing agricultural productivity. While CNNs have shown promising results, they are limited in capturing global contextual relationships within images. This study benchmarks five architecturally diverse Vision Transformer models under an identical training and evaluation protocol to identify the most optimal model for chili leaf disease classification.


## Repository Structure

```
├── src/
│   ├── ViT_Standart.ipynb       # ViT      (vit_small_patch16_224)
│   ├── Swin_transformer.ipynb   # Swin     (swin_tiny_patch4_window7_224)
│   ├── MaxViT.ipynb             # MaxViT   (maxvit_tiny_tf_224)
│   ├── DINOv2.ipynb             # DINOv2   (vit_small_patch14_dinov2)
│   └── EVA_02.ipynb             # EVA-02   (eva02_small_patch14_336.mim_in22k_ft_in1k)
└── README.md◊
```

## Dataset

- **Source:** [Chili Plant Disease](https://www.kaggle.com/datasets/dhenyd/chili-plant-disease)


## Citation

The paper is currently under review. Citation details will be added upon publication.
