---
title: "A New Method for Detecting Altered Text in Document Images"
collection: publications
permalink: /publication/2020-10-9-Altered-Text
excerpt: 'The proposed method explores the relationship between positive and negative coefficients of a DCT to extract the effect of distortions caused by tampering operations.'
date: 2020-10-09
venue: 'International Conference on Pattern Recognition and Artificial Intelligence (ICPRAI)'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-030-59830-3_8'
pdf: '/files/ICPRAI_handwriting_compressed.pdf'
citation: 'Nandanwar, L., Shivakumara, P., Pal, U., Lu, T., Lopresti, D., Seraogi, B., & Chaudhuri, B. B. (2020). A New Method for Detecting Altered Text in Document Images. https://doi.org/10.1007/978-3-030-59830-3_8'
---
As more and more office documents are captured, stored, and shared in digital format, and as image editing software becomes increasingly more powerful, there is a growing concern about document authenticity. For example, texts in property documents can be altered to make an illegal deal, or the date on an airline ticket can be altered to gain entry to airport terminals by breaching security. To prevent such illicit activities, this paper presents a new method for detecting altered text in a document. The proposed method explores the relationship between positive and negative coefficients of a DCT to extract the effect of distortions caused by tampering operations. Here we divide DCT coefficients into positive and negative classes, then reconstructs images from the inverse DCT of the respective positive and negative coefficients. Next, we perform Laplacian filtering over reconstructed images for widening the gap between the values of text and other pixels. Then filtered images of positive and negative coefficients are fused by an average operation. For a fused image, we generate Canny and Sobel edge images in order to investigate the effect of distortion through quality measures, namely, MSE, PSNR and SSIM used as features. In addition, for the fused image, the proposed method extracts features based on histograms over the residual images. The features are then passed on to a deep Convolutional Neural Network for classification. The proposed method is tested on our own dataset as well as two standard datasets, namely IMEI and the ICPR 2018 Fraud Contest dataset. The results show that the proposed method is effective and outperforms existing methods.

[Download paper here](/files/ICPRAI_handwriting_compressed.pdf)
