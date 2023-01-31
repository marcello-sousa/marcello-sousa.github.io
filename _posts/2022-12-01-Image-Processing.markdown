---
layout: post
title:  "Presentation - Image Processing - IMPA"
date:   2022-12-01 14:00:40 -0300
categories: jekyll update
image: /asserts/images/img1.jpg
---

### Paper: 
Pu, W., Sober, B., Daly, N., Sabetsarvestani, Z., Higgitt, C., Daubechies, I., & Rodrigues, M. R. (2020). Image Separation with Side Information: A Connected Auto-Encoders Based Approach. arXiv. <a href="https://doi.org/10.48550/arXiv.2009.07889">https://doi.org/10.48550/arXiv.2009.07889</a>

### Abstract: 
X-radiography (X-ray imaging) is a widely used imaging technique in art investigation. It can provide information about the condition of a painting as well as insights into an artist's techniques and working methods, often revealing hidden information invisible to the naked eye. In this paper, we deal with the problem of separating mixed X-ray images originating from the radiography of double-sided paintings. Using the visible color images (RGB images) from each side of the painting, we propose a new Neural Network architecture, based upon 'connected' auto-encoders, designed to separate the mixed X-ray image into two simulated X-ray images corresponding to each side. In this proposed architecture, the convolutional auto encoders extract features from the RGB images. These features are then used to (1) reproduce both of the original RGB images, (2) reconstruct the hypothetical separated X-ray images, and (3) regenerate the mixed X-ray image. The algorithm operates in a totally self-supervised fashion without requiring a sample set that contains both the mixed X-ray images and the separated ones. The methodology was tested on images from the double-sided wing panels of the Ghent Altarpiece, painted in 1432 by the brothers Hubert and Jan van Eyck. These tests show that the proposed approach outperforms other state-of-the-art X-ray image separation methods for art investigation applications.


### [Presentation slide.]({{ site.url }}/asserts/apresentacao.pdf)



