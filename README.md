# project_6_brainhack_2022
workflow for automated classification of sMRI images of psychiatric disorders using neural networks

# Abstract: 
Despite the advances in medicine, there are still no diagnostic methods for psychiatric disorders depending mainly on the subjective description of the condition by the patients. Among different neuroimaging techniques, structural MRI is considered the most convenient methods that can be used for diagnosis of different psychiatric disorders because it is widely available and less biased. Using deep learning for diagnosis of psychiatric disorders are widely explored, however, in this study, we will test the possibility of classification of different disorders using neural networks. We will develop workflow for sMRI images that automatically do the processing, segmentation into gray and white matter using FSL, conversion into video, using ResNet for the classification, and identification of significant regions of the brain. This workflow will be deployed into a website that psychiatrist can upload sMRI and get the most probable diagnosis. The model will undergo continuous updates. We will use the data from openMRI dataset (https://openneuro.org/datasets/ds000030/versions/1.0.0) and other datasets will be discussed with participants.

# A list of 1-5 key papers summarising the subject:

Latest advances in this field https://www.nature.com/articles/s41380-019-0365-9/
https://academic.oup.com/pcm/article/3/3/202/5898685/
https://www.sciencedirect.com/science/article/pii/S2213158221000280/
one of the packages we will use https://github.com/miykael/gif_your_nifti/
nextflow resources https://www.nextflow.io/docs/latest/script.html
