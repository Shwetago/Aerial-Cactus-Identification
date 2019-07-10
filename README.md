# Aerial-Cactus-Identification

This is a kaggle challenge in which we have to identify specific type of cactus in aerial imagery.
*  https://www.kaggle.com/c/aerial-cactus-identification

**Background:** To assess the impact of climate change on Earth's flora and fauna, it is vital to quantify how human activities such as logging, mining, and agriculture are impacting our protected natural areas. Researchers in Mexico have created the VIGIA project, which aims to build a system for autonomous surveillance of protected areas. A first step in such an effort is the ability to recognize the vegetation inside the protected areas.

**Dataset Overview:**
This dataset contains a large number of 32 x 32 thumbnail images containing aerial photos of a columnar cactus (Neobuxbaumia tetetzo). Kaggle has resized the images from the original dataset to make them uniform in size. The file name of an image corresponds to its id.

You must create a classifier capable of predicting whether an images contains a cactus.

Two files has been uploaded:

1.) Using Keras on tensorflow backend and use Image Data Generator for Image Processing which gives me `99.70%` accuracy on public Lb.

2.) Using pretrained model VGG16 with keras which gives me `99.80%` accuracy on public LB.
