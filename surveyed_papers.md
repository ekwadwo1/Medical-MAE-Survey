# Curated List of Surveyed Papers & Official Code

A structured catalog of 110+ studies reviewed in our survey **"Transformer-Masked Autoencoder (MAE) for Robust Medical Image Classification"** (Expert Systems with Applications, 2026). This library categorizes frameworks by architectural innovation and clinical modality, providing direct links to official open-source implementations.

> **Note:** Performance metrics (AUC, Dice, Acc) refer to the best results reported in the original papers on their primary evaluation datasets.

## 1. Emerging Architectures (2024–2026)
*State-of-the-art frameworks introducing Hybrid, State-Space (Mamba), and Diffusion backbones.*

| Year | Model | Paper Title | Dataset | Performance | Official Code |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 2025 | **VoCov2** | Large-Scale 3D Medical Image Pre-Training With Geometric Context Priors | PreCT-160K, LUNA16 | **AUC: 0.960** (LUNA16) | [GitHub](https://github.com/Luchixiang/VoCo) |
| 2025 | **Hi-End-MAE** | Hi-End-MAE: Hierarchical encoder-driven masked autoencoders | BTCV, 10K CT Scans | **Dice: 85.1%** (BTCV) | [GitHub](https://github.com/FengheTan9/Hi-End-MAE) |
| 2025 | **MambaMIM** | Pre-training Mamba with State Space Token Interpolation | ACDC, Synapse | **Dice: 91.8%** (ACDC) | [GitHub](https://github.com/FengheTan9/MambaMIM) |
| 2025 | **DiffMIC-v2** | Medical Image Classification via Improved Diffusion Network | ISIC 2018, Chest X-ray | **AUC: 98.1%** (Skin) | [GitHub](https://github.com/scott-yjyang/DiffMICv2) |
| 2025 | **MiM** | Mask in Mask Self-Supervised Pre-Training | CC-CCII, MSD, BTCV | **AUC: 99.7%** (CC-CCII) | [GitHub](https://github.com/JiaxinZhuang/MiM) |
| 2025 | **MedMAE** | MedMAE: A Self-Supervised Backbone for Medical Imaging Tasks | MID (2M+ Images) | SOTA Transfer | [GitHub](https://github.com/islamosmanubc/MedMAE) |
| 2024 | **HySparK** | Hybrid Sparse Masking for Large Scale Pre-Training | Large-Scale CT (6.8K) | **Dice: 84.2%** (BTCV) | [GitHub](https://github.com/FengheTan9/HySparK) |
| 2024 | **HTC-Net** | HTC-Net: A hybrid CNN-transformer framework for medical image segmentation | Synapse, ACDC | **Dice: 91.8%** (ACDC) | [GitHub](https://github.com/Tanghui2000/HTC-Net) |

## 2. Chest X-Ray (2D Radiography)
*Foundational studies adapting ViT-MAE for label-efficient disease classification.*

| Year | Model | Paper Title | Dataset | Performance | Official Code |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 2025 | **DINOv3** | Vision Transformers Need Gram Anchors | ChestX-ray14, MIMIC | **AUC: ~0.89** (Avg) | [GitHub](https://github.com/facebookresearch/dinov3) |
| 2024 | **Vis-MAE** | An Efficient Self-supervised Learning Approach on Segmentation | RadImageNet, MIMIC | **AUC: 0.946** (MIMIC) | [GitHub](https://github.com/lzl199704/VIS-MAE) |
| 2024 | **PediCXR-MAE**| Self-Supervision for Pediatric Chest X-Ray Diagnosis | PediCXR (7k Scans) | SOTA (Pediatric) | [GitHub](https://github.com/kayvanlabs/PediCXR-MAE) |
| 2023 | **Medical-MAE** | Delving into Masked Autoencoders for Multi-Label Thorax Disease | NIH-CXR14, CheXpert | **AUC: 0.823** (NIH) | [GitHub](https://github.com/lambert-x/medical_mae) |
| 2023 | **MedIM** | Boost Medical Image Representation via Report-Guided Masking | MIMIC-CXR (Text-Img) | **F1: +5.7%** (vs Random) | [GitHub](https://github.com/YtongXie/MedIM) |
| 2023 | **MSMAE** | Medical Supervised Masked Autoencoders | Chest X-ray (Public) | SOTA (Supervised) | [GitHub](https://github.com/Talented-Q/MSMAE) |

## 3. 3D Volumetric Analysis (CT, MRI & PET)
*Frameworks optimized for high-dimensional volumetric data.*

| Year | Model | Paper Title | Dataset | Performance | Official Code |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 2025 | **DiaMond** | Dementia Diagnosis with Multi-Modal Vision Transformers | ADNI (MRI + PET) | **Acc: 92.4%** (Diagnosis) | [GitHub](https://github.com/ai-med/DiaMond) |
| 2024 | **SuPreM** | Supervised Pre-Trained 3D Models for Medical Image Analysis | TotalSegmentator | SOTA (Seg) | [GitHub](https://github.com/MrGiovanni/SuPreM) |
| 2023 | **Green-MIM** | Green Hierarchical Vision Transformer | BTCV, LUNA16 | **Dice: 81.6%** | [GitHub](https://github.com/LayneH/GreenMIM) |
| 2022 | **SparK** | Spatial-aware Masked Autoencoder for ConvNets | ImageNet / Medical | **mIoU:** SOTA (Dense) | [GitHub](https://github.com/keyu-tian/SparK) |
| 2023 | **Vox2Vec** | Self-supervised Contrastive Learning of Voxel-level Representations | 3D Volumetric | SOTA Segmentation | [GitHub](https://github.com/mishgon/vox2vec) |

## 4. Histopathology, Ultrasound & Specialized
*Specialized architectures for Gigapixel WSI, Ultrasound, and Hyperspectral data.*

| Year | Model | Paper Title | Dataset | Performance | Official Code |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 2024 | **HSIMAE** | Unified Masked Autoencoder for Hyperspectral Pre-training | SpectralEarth | High Accuracy | [GitHub](https://github.com/Ryan21wy/HSIMAE) |
| 2024 | **MAE-WSI** | Masked Autoencoders with handcrafted feature predictions | Esophageal WSI | **Acc: 93.07%** | [GitHub](https://github.com/Atten4Vis/CAE) |
| 2023 | **Swin-MAE** | Swin MAE: Masked autoencoders for small datasets | BUSI (Ultrasound) | **Acc: 90.1%** (BUSI) | [GitHub](https://github.com/Zian-Xu/Swin-MAE) |
| 2023 | **PosMAE** | Position-Aware Masked Autoencoder for Histopathology | Camelyon16, BreaKHis | **AUC: +5.2%** (Breast) | [GitHub](https://github.com/WkEEn/PAMA) |

## 5. Methodological Innovations (PEFT & Federated)
*Efficiency, privacy-preserving, and adaptation frameworks.*

| Year | Model | Paper Title | Dataset | Performance | Official Code |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 2025 | **LKA** | Large Kernel Adapter for Enhanced Classification | ISIC, ChestX | **Acc: +3.5%** | [GitHub](https://github.com/misswayguy/LKA) |
| 2024 | **MeLo** | Low-rank Adaptation is Better than Fine-tuning | Multiple Diagnosis | Comparable (Low Param) | [GitHub](https://github.com/JamesQFreeman/LoRA-ViT) |
| 2023 | **FedMAE** | Federated Self-Supervised Learning with One-Block MAE | Distributed Datasets | High Accuracy | [GitHub](https://github.com/mtics/FedDAE) |
| 2024 | **OSEL** | Optimizing breast cancer classification with ensemble methods | WDBC (Breast Cancer) | **Acc: 99.45%** | (-) |
| 2024 | **MAE-EEG** | MAE-EEG-Transformer: Cross-individual data augmentation | BCI Competition IV | **Acc: 90.09%** | (-) |
