# VMRE
Official Implementation of ''Video-Level Multimodal Relation Extraction with Event-Entity Semantic Consistency'' accepted by ACM MM2025. This repository provides code, data, and feature extraction resources for Video-Level Multimodal Relation Extraction.  
Our implementation is inspired by **[TMR: Translation-based Multimodal Relation Extraction](https://github.com/thecharm/TMR)**.

---

## 📘 1. Code

The core implementation and experimental framework are based on the open-source project **[TMR](https://github.com/thecharm/TMR)**.  
Please refer to that repository for detailed implementation, training, and evaluation.


## 📂 2. Data

You can download the dataset required for experiments from the following link:  
👉 **[Download Data](xxx)**  


---

## 🔍 3. Feature Extraction

We provide feature extraction guidance for both **visual** and **audio** modalities.

### 3.1 Visual Features

Visual embeddings are extracted using **ViT (Vision Transformer)**.  
Pretrained models can be downloaded from the official repository:  
👉 [ViT Model Download](https://huggingface.co/google/vit-base-patch16-224)

### 3.2 Audio Features

For speech-based features, we employ **HuBERT** for high-level representation extraction.  
👉 [HuBERT Model Download](https://huggingface.co/facebook/hubert-large-ll60k)

---

## 📚 Reference

If you use this repository or its components in your research, please cite the following paper:


**BibTeX:**
```bibtex
@inproceedings{10.1145/3746027.3755557,
author = {Zhang, Zefan and Zhang, Weiqi and Suo, Kailong and Li, Yanhui and Bai, Tian},
title = {Video-Level Multimodal Relation Extraction with Event-Entity Semantic Consistency},
year = {2025},
isbn = {9798400720352},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3746027.3755557},
doi = {10.1145/3746027.3755557},
booktitle = {Proceedings of the 33rd ACM International Conference on Multimedia},
pages = {8537–8546},
numpages = {10},
keywords = {multimodal alignment, multimodal relation extraction, video understanding},
location = {Dublin, Ireland},
series = {MM '25}
}

@inproceedings{zheng2023rethinking,
  title={Rethinking multimodal entity and relation extraction from a translation point of view},
  author={Zheng, Changmeng and Feng, Junhao and Cai, Yi and Wei, Xiaoyong and Li, Qing},
  booktitle={Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)},
  pages={6810--6824},
  year={2023}
}
