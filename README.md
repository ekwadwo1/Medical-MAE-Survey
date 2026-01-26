# Medical-MAE-Survey
Official repository for the survey: 'Transformer-Masked Autoencoder (MAE) for Robust Medical Image Classification'.

Abstract

Medical image classification underpins screening, diagnosis, and treatment planning, but conventional CNN pipelines remain label-hungry and brittle under noise, occlusion, and domain shift. Transformer-based masked autoencoders (MAEs) offer a compelling alternative by exploiting large unlabeled archives to learn anatomy-aware representations. This survey systematically synthesizes various studies on MAE-based encoders for X-ray, MRI, CT, ultrasound, and histopathology. We propose a modality-aware taxonomy spanning ViT/Swin backbones, masking strategies, and training regimes, and harmonize reported results against strong CNN and contrastive baselines. Across modalities, MAE initialization consistently improves label efficiency, calibration, and cross-scanner transfer, especially when combined with parameter-efficient fine-tuning. We distill practical design heuristics (mask ratios, encoder \& decoder depth, PEFT rank), highlight recurrent pitfalls in evaluation and reporting, and outline future directions in domain-aware masking, scalable 3D pretraining, cross-modal co-masking, and clinically grounded interpretability.

Our contributions include:

1. Comprehensive, modality-aware synthesis: Systematic categorization of existing methodologies based on architecture (ViT, Swin, hybrid), imaging modalities (X-ray, MRI, CT, histopathology, ultrasound), and training innovations (attention-driven masking, parameter-efficient fine-tuning, cross-domain transfer).

2. Quantitative evidence synthesis and harmonised summaries Harmonized comparisons of MAE models against contrastive learning and supervised CNN benchmarks. 

3. Implementation and deployment blueprint: Compilation of publicly available resources, including code repositories and open-source frameworks, and practical guidelines reducing computational costs by up to 87\% without significant performance losses.


Conclusion:

This survey establishes that while Transformer-masked autoencoders (MAEs) excel in label-scarce and imbalanced medical imaging scenarios, they are not universally superior to efficient CNNs or contrastive models in high-data or low-latency regimes. We found that current performance claims are often obscured by inconsistent benchmarking, necessitating stricter standards for reproducibility and transparent reporting. Ultimately, future progress depends on developing anatomy-aware and cross-modal masking strategies to transform MAEs from theoretical benchmarks into reliable clinical tools.
