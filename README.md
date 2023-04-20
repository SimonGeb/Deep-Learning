# Deep-Learning
Repository for the Deep Learning reproducability project. It is based on the Learning to See in the Dark paper.

**Scripts**

This repository contains several scripts.
- Testing: use this to test your own images on a trained model
  - Ensure you set the directories for both input, output and model correctly
  - Do not forget to change the file extention correctly as this is different depending on the camera
  - Do not forget to change the bit level of the camera
  - The code will automatically select the right black level and bayer filter arrangement
- Training: use this for training your own model
  - Ensure you set the directories for input and output correctly
- PSNR and SSIM: use this to calculate PSNR and SSIM values for pairs of output/ground truth images
  - Again, ensure you set the directories correctly
- Plot loss: use this to plot the loss of your own trained models

**Data**

This repository also contains data of several trained models.
- The checkpoint directory contains various trained models
  - Because of the size, they are available here: https://drive.google.com/drive/folders/1orE2XH5PN_G73QLLj4jhee4oJ8mzaxZw?usp=sharing
  - The 'full' models are trained with the same number of epochs and images as the original model so will have the best performance
  - The other models are all trained with 40 images and 15 epochs, mainly to compare performance
- The dataset directory should be used to save training or testing images
  - The dataset for the original paper is available here: https://github.com/cchen156/Learning-to-See-in-the-Dark
