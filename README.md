# Deep-Learning
Repository for the Deep Learning reproducability project. It is based on the Learning to See in the Dark paper.

**Scripts**

This repository contains several scripts.
- Testing: use this to test your own images on a trained model
  - Ensure you set the directories for both input, output and model correctly
  - Do not forget to change the file extention correctly as this is different depending on the camera
  - Do not forget to change the bit level of the camera
  - The code will automatically select the right black level and bayer filter arrangement
- PSNR and SSIM: use this to calculate PSNR and SSIM values for pairs of output/ground truth images
  - Again, ensure you set the directories correctly


**Data**

This repository also contains data of several trained models.
- The checkpoint directory contains various trained models
- The dataset directory should be used to save training or testing images
