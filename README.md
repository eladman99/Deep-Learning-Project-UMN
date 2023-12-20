# CSCI 5527 Deep-learning-project (University Of Minnesota)

# ENHANCED IMAGE COLORIZATION USING CONDITIONAL WASSERSTEIN GANS AND UNBALANCED OPTIMAL TRANSPORT

## Project Overview

This repository hosts our cutting-edge implementation focusing on imagecolorization, utilizing Conditional Wasserstein Generative Adversarial Networks (WGANs) augmented with Optimal Transport (OT) theory, coined as OT CWGAN. Our project specifically tackles the inherent challenges associated with traditional GAN frameworks. By integrating a WGAN architecture and further enhancing it with OT principles. This framework aims to elevates the stability, quality, and robustness of the image colorization process.


## Repository Contents
- **Code**: The complete code for implementing and training the models.
- **Base Code**: The foundational code for CGAN, upon which our models are built.



## Milestones

1. **Model Implementation**: Establishing a baseline model (CGAN).
2. **WGAN Integration**: adapted the base code for WGAN model.
3. **OT WGAN- OT principles are being attempted to be added to the WGAN model we created, but with no success.
4. **Training and Optimization**
5. **Evaluation**: Assessing the models.
6. **Documentation**: Reporting our findings and methodologies.



## Expected Outcomes
- Higher quality colorization with improved fidelity and realism.
- Consistency and stable model.


## Previous works

In the realm of generative models, significant advancements have been made, starting with Goodfel- low et al. (2014)’s introduction of Generative Adversarial Networks (GANs) in their seminal work. Building on this foundational concept, Isola et al. (2017) later introduced a general-purpose ap- proach for image-to-image translation tasks using cGANs. Concurrently, Arjovsky1 et al. (2017) proposed the WGAN, an advancement over the standard cGAN that addressed issues like mode collapse and training instability, which are detailed in the problem section of our report. Recently, Abu-Srhan et al. (2022) investigated various loss function combinations for image-to-image trans- lation tasks, revealing the effectiveness of combining WGAN with L1 loss for the adversarial and non-adversarial components, influencing our choice of loss functions.

Recent advancements in generative modeling have leveraged Optimal Transport (OT) and its robust variants. Traditional OT methods, crucial in training models like Wasserstein GANs, face challenges with outliers. To overcome this, robust OT formulations have been developed, effectively handling outliers by assigning them lower weights in optimization. This approach, particularly in robust Wasserstein GANs, has improved performance in applications such as generative modeling and domain adaptation by ignoring outlier samples in the generative distribution (Balaji et al., 2020).


## Refrences

1. Alaa Abu-Srhan, Mohammad A.M. Abushariah, and Omar S. Al-Kadi. "The effect of loss function on conditional generative adversarial networks." _Journal of King Saud University - Computer and Information Sciences_, 34(9):6977–6988, 2022. ISSN 1319-1578. [DOI](https://doi.org/10.1016/j.jksuci.2022.02.018). [URL](https://www.sciencedirect.com/science/article/pii/S1319157822000519).

2. Martin Arjovsky, Soumith Chintala, and Léon Bottou. "Wasserstein GAN." _arXiv_, 2017. [URL](https://arxiv.org/abs/1701.07875).

3. Yogesh Balaji, Rama Chellappa, and Soheil Feizi. "Robust Optimal Transport with Applications in Generative Modeling and Domain Adaptation." _arXiv_, 2020. [URL](https://arxiv.org/abs/2006.06520).

4. Salim Benhamadi. "Pix2pix: Image colorization with conditional WGAN." Kaggle, 2023. Accessed: 12/01/2023. [URL](https://www.kaggle.com/code/salimhammadi07/pix2pix-image-colorization-with-conditional-wgan/notebook).

5. Jaemoo Choi, Jaewoong Choi, and Myungjoo Kang. "Generative Modeling through the Semi-Dual Formulation of Unbalanced Optimal Transport." _arXiv_, 2023. [URL](https://arxiv.org/abs/2301.00000).

6. Ian J. Goodfellow, Jean Pouget-Abadie, Mehdi Mirza, Bing Xu, David Warde-Farley, Sherjil Ozair, Aaron Courville, and Yoshua Bengio. "Generative Adversarial Networks." _arXiv_, 2014. [URL](https://arxiv.org/abs/1406.2661).

7. Phillip Isola, Jun-Yan Zhu, Tinghui Zhou, and Alexei A. Efros. "Image-to-Image Translation with Conditional Adversarial Networks." _arXiv_, 2017. [URL](https://arxiv.org/abs/1611.07004).

8. mberkay0. "Image Colorization with U-Net and GAN Tutorial." GitHub, 2022. Accessed: 12/01/2023. [URL](https://github.com/mberkay0/image-colorization).





