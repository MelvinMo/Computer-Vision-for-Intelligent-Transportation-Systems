# Computer-Vision-for-Intelligent-Transportation-Systems

During one of my internships, which was at a private computer vision company, I undertook a project focused on developing and assessing computer vision and machine leaning techniques for automated quality control of manufactured parts in the field of intelligent transportation systems. The following is a concise summary of the key learnings from this project, which I will now provide in English:

I experimented with several machine learning algorithms on image data. The main techniques I applied were PCA for dimensionality reduction, SVM for classification, deep learning for image feature extraction, and shape context descriptors for shape matching. Key outcomes and results from my work are highlighted below.

## PCA for Dimensionality Reduction

- Used PCA to reduce high-dimensional image data to a lower dimension while preserving key information. This condenses large datasets down to their main components.

- Performed PCA on sample 8x8 image patches to obtain a reduced 39-component feature vector representation of each patch. This summarizes the patches using fewer variables.

## SVM for classification

- Developed SVM models to classify image patches into defect vs. non-defect. SVM aims to maximize the margin between classes during training.

- Tested models on sample patches and evaluated performance using recall and precision metrics. The best results were obtained with PCA inputs and an RBF kernel.

## Deep Learning for Feature Extraction

- Experimented with different deep neural network architectures for learning image features from scratch. Focused on convolutional and locally connected models.

- Convolutional models extracted more meaningful features and had higher validation accuracy compared to locally connected networks.

## Shape matching with context descriptors

- Used the shape context approach to characterize the shape of an object by the distribution of points relative to each contour point.

- Applied technique to match manufactured parts against good sample images to identify defects.

- Achieved over 98% accuracy on test data using SVM on shape context descriptor inputs.
