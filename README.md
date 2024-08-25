# Project Overview
Misdiagnosis in the medical field is a serious concern, yet it occurs more frequently than one might expect. Interpreting medical imaging, particularly  magnetic resonance imaging (MRI), requires the expertise of a skilled radiologist. This task is complex because interpreting these images is not simply a matter of labeling them as normal or abnormal. Different radiologists might interpret the same scan differently, leading to conflicting reports that can complicate treatment decisions.

MRI diagnosis is especially challenging, often requiring multiple variations of imaging to improve diagnostic accuracy. These variations provide a more comprehensive understanding, but access to such diverse imaging can be difficult and expensive.

We can generate artificial MRI images with different contrast levels from existing scans using deep learning, specifically style transfer techniques. This approach enhances diagnostic capabilities by providing additional imaging perspectives at a lower cost.

# Capstone Project Goal
In this capstone project, a CycleGAN framework was used to translate the style of one MRI image to another, facilitating a deeper understanding of the scanned image. Specifically, T2-weighted images were generated from T1-weighted MRI scans and vice versa.

## Problem Statement 
Develop a Generative Adversarial Network (GAN) model, based on a modified U-Net architecture, to generate artificial MRI images with different contrast levels from existing MRI scans.

## Project Pipeline
The project pipeline is structured as follows:

1. **Data Understanding:** Load and prepare the dataset.
2. **Image Processing:** Apply various processing techniques to the images.
3. **Model Building and Training:** Develop the Generators and Discriminators using a modified U-Net architecture similar to CycleGAN. Define the loss function and implement the training process.
