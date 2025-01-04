# Generative Adversarial Networks (GANs)

Generative Adversarial Networks (GANs) are a class of machine learning frameworks designed for generative tasks, introduced by Ian Goodfellow in 2014. GANs consist of two neural networks: a **generator** and a **discriminator**, which are trained simultaneously in a competitive process. 

- **Generator**: Creates synthetic data resembling the real dataset.
- **Discriminator**: Distinguishes between real and synthetic data.

The generator aims to fool the discriminator, while the discriminator improves its ability to differentiate real from generated data, resulting in high-quality synthetic data.

---

## Types of GANs

| GAN Type                       | Description                                                                                     | Implemented |
|--------------------------------|-------------------------------------------------------------------------------------------------|-------------|
| Vanilla GAN                    | The basic GAN model introduced in the original paper.                                           | [x]         |
| Deep Convolutional GAN (DCGAN) | Uses convolutional layers for stable training and high-quality outputs.                        | [x]         |
| Conditional GAN (cGAN)         | Generates data conditioned on labels or specific input.                                        | [ ]         |
| Wasserstein GAN (WGAN)         | Introduces Wasserstein distance for more stable training and better gradient flow.             | [x]         |
| WGAN with Gradient Penalty     | Enhances WGAN by adding a gradient penalty to further improve training stability.              | [ ]         |
| CycleGAN                       | Translates images between two domains without paired samples (e.g., photo ↔ painting).         | [ ]         |
| StyleGAN                       | Generates high-quality, controllable images with style transfer capabilities.                  | [ ]         |
| Progressive Growing GAN (PGGAN)| Trains GANs progressively, starting from low resolutions to high resolutions for stability.    | [ ]         |
| BigGAN                         | Optimized for large-scale image generation using larger architectures and datasets.            | [ ]         |
| StarGAN                        | Enables multi-domain image-to-image translations.                                              | [ ]         |
| InfoGAN                        | Extends GANs by introducing disentangled, interpretable latent representations.                | [ ]         |
| Pix2Pix                        | Performs paired image-to-image translation (e.g., sketches to realistic images).               | [ ]         |

---

---

## References

1. **Ian Goodfellow et al.** - Generative Adversarial Networks (GANs), 2014. [Paper](https://arxiv.org/abs/1406.2661)  
2. **Radford, A., Metz, L., & Chintala, S.** - Deep Convolutional Generative Adversarial Networks (DCGANs), 2015. [Paper](https://arxiv.org/abs/1511.06434)  
3. **Mirza, M., & Osindero, S.** - Conditional Generative Adversarial Nets (cGANs), 2014. [Paper](https://arxiv.org/abs/1411.1784)  
4. **Arjovsky, M., Chintala, S., & Bottou, L.** - Wasserstein GAN (WGAN), 2017. [Paper](https://arxiv.org/abs/1701.07875)  
5. **Gulrajani, I., et al.** - Improved Training of Wasserstein GANs with Gradient Penalty, 2017. [Paper](https://arxiv.org/abs/1704.00028)  
6. **Zhu, J.-Y., et al.** - Unpaired Image-to-Image Translation using CycleGAN, 2017. [Paper](https://arxiv.org/abs/1703.10593)  
7. **Karras, T., et al.** - Progressive Growing of GANs for Improved Quality, Stability, and Variation, 2018. [Paper](https://arxiv.org/abs/1710.10196)  
8. **Karras, T., et al.** - A Style-Based Generator Architecture for Generative Adversarial Networks (StyleGAN), 2019. [Paper](https://arxiv.org/abs/1812.04948)  
9. **Brock, A., Donahue, J., & Simonyan, K.** - Large Scale GAN Training for High Fidelity Natural Image Synthesis (BigGAN), 2019. [Paper](https://arxiv.org/abs/1809.11096)  
10. **Choi, Y., et al.** - StarGAN: Unified Generative Adversarial Networks for Multi-Domain Image-to-Image Translation, 2018. [Paper](https://arxiv.org/abs/1711.09020)  
11. **Chen, X., et al.** - InfoGAN: Interpretable Representation Learning by Information Maximizing Generative Adversarial Nets, 2016. [Paper](https://arxiv.org/abs/1606.03657)  
12. **Isola, P., et al.** - Image-to-Image Translation with Conditional Adversarial Networks (Pix2Pix), 2017. [Paper](https://arxiv.org/abs/1611.07004)  

---
