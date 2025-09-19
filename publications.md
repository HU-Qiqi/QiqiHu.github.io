---
layout: page
permalink: /publications/index.html
title: Publications
---


## Projects
- Hybrid thermal management scheme combining PCM and air cooling for suppressing thermal runaway in LIBs
- [WM_encoder_decoder for copyright protection in image-to-image based on diffusion models](https://github.com/HU-Qiqi/WM_encoder_decoder) [PPT](https://github.com/HU-Qiqi/WM_encoder_decoder/blob/main/Introduction.pptx)<br>
  This project aims to address the challenges in image security and copyright protection posed by generative models (such as Diffusion Model), by proposing a dual-protection scheme that integrates digital watermarking with adversarial perturbations. The approach effectively suppresses image tampering and generative manipulation based on Diffusion Model by performing PGD adversarial attacks in the latent space on original images. Meanwhile, it employs a pre-trained encoder-decoder network to achieve invisible embedding and high-accuracy extraction of original author information. The method operates solely on the image itself without relying on model fine-tuning, offering excellent transferability and anti-attack capability. Experiments demonstrate that the solution maintains high visual quality (PSNR ≈ 34.5) while achieving completely accurate watermark bit extraction (Bit Accuracy = 1.0), and significantly degrades the quality of generated images under various manipulation strengths. It provides a practical protection mechanism for artistic copyright and privacy-sensitive images that supports traceability and tampering resistance.<br>
  本项目致力于应对生成模型（如Diffusion Model）带来的图像安全和版权保护挑战，提出了一种融合数字水印与对抗性扰动的双重保护方案。该方案通过对原始图像在潜空间进行PGD对抗攻击，有效抑制基于Diffusion Model的图像篡改与生成操纵，同时利用预训练的编码-解码网络实现原作者信息的不可见嵌入与高精度提取。该方法不依赖模型微调，仅作用于图像本身，具备良好的迁移性和抗攻击能力。实验表明，本方案在保持图像视觉质量的同时（PSNR ≈ 34.5），能够实现比特水印的完全准确提取（Bit Accuracy = 1.0），并在多种生图强度下显著降低篡改后的生成质量，为艺术版权和隐私敏感图像提供了可溯源、防篡改的实用化保护机制。<br>
  
- [SSNN: Privacy-Preserving Secure Shared Nearest Neighbor Clustering Scheme in internet of things](https://www.researchgate.net/publication/385489004_Privacy-Preserving_Secure_Shared_Nearest_Neighbor_Clustering_Scheme_in_Internet_of_Things)<br>
  This project designed and implemented a cloud-assisted privacy-preserving clustering scheme to enable resource-constrained IoT devices to perform Shared Nearest Neighbor (SNN) clustering efficiently and securely. It introduced a novel orthogonal matrix transformation technique to encrypt sensitive data before outsourcing to the cloud, ensuring end-to-end privacy. This scheme developed a lightweight verification mechanism allowing devices to detect invalid cloud-computed results with optimal probability 1. Achieved significant reduction in local computation overhead—time cost of the most complex step decreased from 10.859s to 1.183s—while maintaining clustering accuracy. It is validated through comprehensive experiments on real-world datasets including smart meter data and hyperspectral images, demonstrating practicality for IIoT applications such as pattern recognition and image segmentation.<br>
  本项目旨在解决资源受限的物联网设备在进行共享近邻（SNN）聚类分析时面临的计算效率与数据隐私保护问题，提出了一种支持云端安全外包的隐私保护聚类方案。通过设计创新的正交矩阵变换技术，对原始数据进行加密后再传输至云服务器处理，有效防止敏感信息在计算和传输过程中泄露。方案还构建了高效的结果验证机制，使设备能够以最优概率1检测云返回结果的正确性，保障计算完整性。实验表明，本方案在保持聚类精度的同时，显著降低了设备端计算开销——SNN最复杂步骤耗时从10.859秒降至1.183秒，适用于智能电网、图像分割等多种IIoT实际场景，具备良好的可扩展性与实用性。<br>

---

## Degree Thesis

- SNLM: a secure and efficient image denoising algorithm in internet of things (Advisor: Hanlin ZHANG).
  In my undergraduate thesis project, I led the development of "SNLM: A Secure and Efficient Image Denoising Algorithm for the Internet of Things." The project aimed to address the challenges of efficiency and privacy faced by computationally limited IoT devices when performing resource-intensive image denoising tasks. I designed a comprehensive secure outsourcing scheme that delegates the most computationally expensive components—matrix decomposition and similarity evaluation within an enhanced Non-Local Means (NLM) algorithm—to a cloud server. By employing Householder transformation to encrypt and blind all input and output data, the solution ensured the privacy of sensitive image information. Additionally, an efficient verification mechanism was implemented to detect invalid results from the cloud with optimal probability 1, enhancing the system's security and reliability. Theoretical analysis and experimental results demonstrated that the scheme significantly reduced computational overhead on the client side while maintaining denoising accuracy (PSNR ≈ 20–21 dB), offering a practical and secure solution for IoT applications such as medical imaging and intelligent surveillance.
  <br>
  在本科毕业设计中，我主导开发了“SNLM：物联网中一个安全高效的图像去噪算法”项目。该项目致力于解决资源受限的物联网设备在执行计算密集型图像去噪任务时面临的效率与隐私挑战。设计了一套完整的安全外包方案，将改进的非局部均值算法中最耗时的矩阵分解与相似性评估任务委托至云服务器执行。通过引入豪斯霍德变换对所有输入输出数据进行加密盲化，确保了敏感图像数据的隐私性；同时设计了高效的验证机制，能以最优概率1检测云端的无效计算结果，保障了系统的安全性与可靠性。理论分析与实验结果表明，该方案在几乎保持原有去噪精度（PSNR约20-21dB）的同时，显著降低了客户端的计算开销，为医疗影像、智能监控等物联网应用提供了可行的安全高效去噪解决方案。

<br>
