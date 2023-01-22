# Style-Transfer-Using-CycleGAN

## Business Problem
Misdiagnosis in the medical field is a very serious issue but it’s also uncomfortably common to occur. Imaging procedures in the medical field requires an expert radiologist’s opinion since interpreting them is not a simple binary process ( Normal or Abnormal). Even so, one radiologist may see something that another does not. This can lead to conflicting reports and make it difficult to effectively recommend treatment options to the patient.

One of the complicated tasks in medical imaging is to diagnose MRI(Magnetic Resonance Imaging). Sometimes to interpret the scan, the radiologist needs different variations of the imaging which can drastically enhance the accuracy of diagnosis by providing practitioners with a more comprehensive understanding.

But to have access to different imaging is difficult and expensive. With the help of deep learning, we can use style transfer to generate artificial MRI images of different contrast levels from existing MRI scans. This will help to provide a better diagnosis with the help of an additional image.

## Business Solution
To build a Generative adversarial model(modified U-Net) which can generate artificial MRI images of different contrast levels from existing MRI scans.

We will use CycleGAN to translate the style of one MRI image to another, which will help in a better understanding of the scanned image. Using GANs you will create T2 weighted images from T1 weighted MRI image and vice-versa.

## Solution Demonstration

Refer this Jupyter Notebook File https://github.com/mrm1404/Style-Transfer-Using-CycleGAN/blob/main/Style_Transfer_Using_CycleGAN_with_Normalization.ipynb

![Predicted_CycleGan_TR1_TR2_Image](https://github.com/mrm1404/Style-Transfer-Using-CycleGAN/blob/main/cyclegan.gif)
