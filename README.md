# AFML Course Project Notebooks

Class-Aware Meta Learning explores parameter-efficient fine-tuning of CLIP ViT-B/16 on long-tailed CIFAR-100 while monitoring SVHN OOD robustness. The project combines class-aware sampling with MetaLoRA adapters and bi-level optimization to boost tail accuracy without sacrificing calibrated confidence.

- The class-aware OOD workflow lives in `ipython/class_aware_cifar100_ood.ipynb`. Open it locally to follow the SVHN evaluation pipeline.
- The class-aware classification notebook in `ipython` is not currently rendering in VS Code. You can run the latest version directly in Colab: [Open Colab Notebook](https://colab.research.google.com/drive/1vRav1AMWRHQw0TOp4MDV6f6-ySuDY41m#scrollTo=8qmwaR4LcMNQ)
