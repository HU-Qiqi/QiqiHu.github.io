---
layout: page
permalink: /publications/index.html
title: Publications
---


## Projects
- Hybrid thermal management scheme combining PCM and air cooling for suppressing thermal runaway in LIBs <br>
- [WM_encoder_decoder for copyright protection in image-to-image based on diffusion models](https://github.com/HU-Qiqi/WM_encoder_decoder) [PPT](https://github.com/HU-Qiqi/WM_encoder_decoder/blob/main/Introduction.pptx)<br>
  - This project addresses image security and copyright issues caused by generative models (such as diffusion models) by proposing a dual-protection scheme that integrates digital watermarking with adversarial perturbations.
  - The approach suppresses tampering and generative manipulation through adversarial attacks in the latent space of images, while employing a pre-trained encoder-decoder network to achieve highly accurate watermark embedding and extraction.
  - Without requiring model fine-tuning, the method offers strong transferability and robustness, maintains high visual quality, enables reliable traceability, and significantly degrades the quality of generated images. It provides a practical protection mechanism for artistic copyright and privacy-sensitive images.<br>
  项目针对生成模型（如扩散模型）带来的图像安全与版权问题，提出了一种结合数字水印和对抗扰动的双重保护方案。该方法通过在图像隐空间中进行对抗攻击，有效抑制篡改和生成操纵，并利用预训练编解码网络实现高精度水印嵌入与提取。方案无需模型微调，具有良好迁移性和抗攻击能力，在保持高视觉质量的同时能准确追溯来源并显著降低生成图像质量，为艺术版权和隐私敏感图像提供实用保护。<br>
  
- [SSNN: Privacy-Preserving Secure Shared Nearest Neighbor Clustering Scheme in internet of things](https://www.researchgate.net/publication/385489004_Privacy-Preserving_Secure_Shared_Nearest_Neighbor_Clustering_Scheme_in_Internet_of_Things)<br>
  <img src="/images/SSNN.png">
  - This project developed a cloud-assisted privacy-preserving scheme for efficient and secure Shared Nearest Neighbor (SNN) clustering on resource-limited IoT devices.
  - It employs orthogonal matrix transformation to encrypt sensitive data before outsourcing, and a lightweight verification mechanism to detect invalid cloud results with optimal probability.
  - The approach drastically reduces local computation—cutting the most complex step from 10.859s to 1.183s—while preserving accuracy. Experiments on real-world datasets confirm its practicality for IIoT applications like pattern recognition and image segmentation.<br>
  该项目开发了一种云辅助隐私保护方案，用于在资源有限的物联网设备上实现高效安全的共享最近邻（SNN）聚类。该方案采用正交矩阵变换技术在数据外包前加密敏感信息，并通过轻量级验证机制以最优概率检测云端无效计算结果。该方法大幅降低了本地计算开销——将最复杂步骤的耗时从10.859秒减少至1.183秒，同时保持聚类精度。基于智能电表数据和高光谱图像等真实数据集的实验验证了该方案在工业物联网应用（如模式识别和图像分割）中的实用性。<br>

---

## Degree Thesis

- SNLM: a secure and efficient image denoising algorithm in internet of things (Advisor: Hanlin ZHANG).<br>
  <img src="/images/SNLM.png">
  - The project introduced an outsourcing scheme for image denoising in IoT that offloads computationally intensive matrix decomposition and similarity evaluation to the cloud, while protecting data privacy through Householder transformation.
  - A verification mechanism was implemented to detect invalid cloud results with optimal probability.
  - The scheme significantly reduces client-side computation while maintaining denoising accuracy (PSNR ≈ 20–21 dB), offering a practical solution for IoT applications like medical imaging and surveillance.
  <br>该项目提出了一种面向物联网图像去噪的安全外包方案，将计算密集的矩阵分解和相似性评估任务卸载至云端处理，同时通过豪斯霍尔德变换保护数据隐私。该方案采用可验证机制，能以最优概率检测云端返回的无效计算结果，在显著降低客户端计算开销的同时保持去噪精度（PSNR ≈ 20–21 dB），为医疗影像和智能监控等物联网应用提供了实用解决方案。

<br>
