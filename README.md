# Brain Tumor Detection
<p align="center">
  <img src=https://youtu.be/Wgy91IoWjjM />
</p>

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](https://youtu.be/Wgy91IoWjjM)

## MOTIVATION

A brain tumor is one of the most hostile diseases affecting
over 700,000 people within the United States alone. Once
formed, it has the ability to infiltrate the remaining portions of
the brain and spinal cord, resulting in death among adults and
children. Caution and care are taken in the accuracy of the
diagnosis, treatment, and planning to increase the life
expectancy of that patient. Due to such caution being
instrumental in the patient’s life, radiologists and clinical
experts are tasked with the tedious task of ensuring not only
detecting the tumor but also segmentation. To reduce the
introduction of human error when evaluating these MRI scans,
Machine Learning (ML) can be implemented for automatic
classification. We want to implement a model with the ability
to detect and identify the presence of a brain tumor.

## DATA SET DESCRIPTION

We have decided to use a data set that is publicly available.
The Brain Tumor Dataset, found on Kagle, consists of 3,
565 raw MRI images with brain tumors in varying locations of
the brain [1]. The images are segmented into tumor types:
Glioma, Meningioma, No Tumor, and pituitary. This dataset is
divided into training and testing sets.

## METHODOLOGY

The initiation for this problem is at the image classification
stage where we have to identify tumor types from MRI
images. We will be using a basic Convolutional Neural
Network (CNN) as our baseline model and the proposed
model will be a variant of this.

