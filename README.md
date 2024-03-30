Abstract

Our paper introduces a robust framework for the automated identifica- tion of diseases in plant leaf images. 
The framework incorporates several key stages to enhance disease recognition accuracy. In the pre-processing phase, 
a thumbnail resizing technique is employed to resize images, minimizing the loss of critical image details while ensuring 
computational efficiency. Normalization procedures are applied to standardize image data before feature extraction. 
Feature extraction is facilitated through a novel framework built upon Vision Trans- formers, a state-of-the-art approach in image analysis. 
Additionally, alternative versions of the framework with an added layer of linear projection and blockwise linear projections are explored. 
This comparative analysis allows for the evalua- tion of the impact of linear projection on feature extraction and overall model performance. 
To assess the effectiveness of the proposed framework, various Convolutional Neural Network (CNN) architectures are utilized, 
enabling a comprehensive evaluation of linear projection's influence on key evaluation metrics. The findings demonstrate the efficacy of the proposed framework, 
with the top- performing model achieving a Hamming loss of 0.054. Furthermore, we propose a novel hardware design specifically 
tailored for scanning diseased leaves in an omnidirectional fashion. The hardware implementation utilizes a Raspberry Pi Compute 
Module to address low-memory configurations, ensuring practicality and affordability. This innovative hardware solution enhances the overall 
feasibility and accessibility of the proposed automated disease identification system. 
This research contributes to the field of agriculture by offering valuable insights and tools for the early detection and management of plant diseases, 
potentially leading to improved crop yields and enhanced food security.
