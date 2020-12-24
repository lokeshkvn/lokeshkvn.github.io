---
title: "A New Common Points Detection Method for Classification of 2D and 3D Texts in Video/Scene Images"
collection: publications
permalink: /publication/2020-7-26-2D-3D-Word-Classification
excerpt: 'This work aims at classification of 2D and 3D texts in video or scene images such that one can choose an appropriate method in the classified text for achieving better results.'
date: 2020-07-26
venue: 'IAPR 14th International Workshop on Document Analysis System'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-030-57058-3_36'
citation: 'L. Nandanwar, P. Shivakumara, A. Kumar, T. Lu, U. Pal, D. Lopresti, "A New Common Points Detection Method for Classification of 2D and 3D Texts in Video/Scene Images," Document Analysis Systems. DAS 2020. Lecture Notes in Computer Science, vol 12116. Springer, Cham. https://doi.org/10.1007/978-3-030-57058-3_36'
---
Achieving high quality recognition result for video and natural scene images that contain both standard 2D text as well as decorative 3D text is challenging. Methods developed for 2D text may fail for 3D text due to the presence of pixels representing shadow and depth in the 3D text. This work aims at classification of 2D and 3D texts in video or scene images such that one can choose an appropriate method in the classified text for achieving better results. The proposed method explores Generalized Gradient Vector Flow (GGVF) for finding dominant points for input 2D and 3D text line images based on opposite direction symmetry. For each dominant point, our approach finds distance between neighbor points and plots a histogram to choose points which contribute to the highest peak as candidates. Distance symmetry between a candidate point and its neighbor points is checked and if a candidate point is visited twice, a common point is created. Statistical features such as the mean and standard deviation of the common points and candidate points are extracted to feed to Neural Network (NN) for classification. Experimental results on dataset of 2D-3D text line images and the dataset collected from standard natural scene images show that the proposed method outperforms exiting methods. Furthermore, recognition experiments before and after classification show recognition performance improves significantly as a result of applying our method.

[Download paper here](http://academicpages.github.io/files/paper3.pdf)

