# Underwater-Image-Enhancer
Marine engineering heavily relies on underwater imagery, yet generating
accurate and high-quality underwater images remains a significant
challenge. Issues such as blurriness, low contrast, and unnatural color
distortions—caused by light scattering, absorption, and spatial
segmentation—make underwater image analysis particularly difficult.
Traditional enhancement methods like histogram equalization often fall
short, and even Convolutional Neural Networks (CNNs) struggle to recover
fine image details. These limitations highlight the need for a more adaptive
and powerful approach to underwater image enhancement.

This project proposes a Hybrid Swin-based FUnIE-GAN model that
combines the strengths of the Swin Transformer and FUnIE-GAN for
superior underwater image enhancement. The Swin Transformer enhances
feature extraction by capturing both local textures and global structural
information, while FUnIE-GAN leverages generative adversarial learning
to restore natural colors and intricate image details. The integration of
edge-aware convolution ensures the preservation of sharp edges, and
spectral normalization contributes to stable training.
This report explores the key challenges in underwater image enhancement

Some Enhanced Images by our Model are: 

![image](https://github.com/user-attachments/assets/ddbff1fa-e7c3-4d4f-9144-ca7ac7b41e09)
![image](https://github.com/user-attachments/assets/6168fe1e-5360-4fe7-9181-8b5f15c0db60)

The Model Evaluation Metrics are:
![image](https://github.com/user-attachments/assets/2d6271c1-5c5c-4a57-94f3-44afd2173a8e)
