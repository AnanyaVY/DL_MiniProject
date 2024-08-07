# Tuberculosis Detection Using CNN Models

## Introduction

A highly contagious bacterial infection, tuberculosis (TB) mainly affects the lungs but can also spread to other regions of the body. 
The World Health Organization (WHO) estimates that there were 10 million new cases of tuberculosis (TB) and 1.4 million deaths from 
the disease in 2019 alone, making it one of the top 10 causes of death worldwide. In order to stop the spread of tuberculosis and 
enhance patient outcomes, early detection is essential. 
Even while TB control has made great progress, the disease has become less of a priority in many nations, which has led to lower 
financial support and declining public awareness. Rapid population expansion and greater mobility are two factors that have further 
aided in the spread of tuberculosis (TB), making it a serious problem for both emerging and developed countries.
Apart from its health consequences, tuberculosis (TB) imposes a significant socio-economic cost, highlighting the necessity of 
ongoing efforts in both prevention and treatment. An interdisciplinary strategy with a focus on research and innovation is needed to
effectively eradicate tuberculosis.

## Problem Statement: 

Develop and compare CNN models for automated tuberculosis detection from chest X-ray images, enhancing early diagnosis and treatment.


## Problem Description: 

In 2020, 1.4 million people died from tuberculosis, with 550,000 women and 750,000 men. Survival rates vary by age 
group, with 90% for under 15 years, 65% for over 40 years, and 85% for 15-39 years, highlighting the need for improved 
diagnosis and treatment. It is detected by Chest X-ray images of lungs.
Low contrast chest X-ray images are crucial for diagnosing tuberculosis due to technical constraints, patient-related 
issues, and environmental problems. Radiologists struggle to accurately diagnose TB lesions due to lung tissue distribution 
and background noise. Manual screening increases workload, potentially causing longer wait times and postponing treatment. 
Insufficient competent workers exacerbate these challenges.


## Solution: 

Automated solutions for diagnosing and classifying tuberculosis are increasingly important. Deep learning techniques 
can optimize detection, reduce interpretation time, and enhance diagnosis precision. These systems can identify and 
classify anomalies on chest X-ray images, enabling early intervention and treatment. Deep learning models, such as 
Convolutional Neural Networks (CNNs), are particularly effective in extracting high- and low-level characteristics 
from chest X-ray images, making them essential in various therapeutic applications. 
Convolutional neural networks (CNNs) have demonstrated potential in the diagnosis and treatment of tuberculosis by 
identifying complex patterns in medical images. As processing power has increased, CNNs have shown remarkable results in 
image classification applications, such as the diagnosis of tuberculosis from chest X-ray images.
For this project, we are using chest X-ray images as the primary source of data. We will explore the use of three different 
CNN architectures: ResNet50, InceptionV3, VGG19 and Exception VGG19, known for its hierarchical feature extraction, ResNet50, 
utilizing residual connections for training deep networks, InceptionV3, with multiple filter sizes for capturing diverse image 
aspects and Xception, which employs depth wise separable convolutions for efficient learning. By leveraging these models, we aim 
to enhance the accuracy and efficiency of TB detection from chest X-ray images.


## Software Requiremnents:

1.	Operating System: Windows 10 or higher, macOS, or Linux.

2.	Programming Language: Python 3.6 or higher.

3.	Libraries used:

o	TensorFlow: For deep learning model implementation and training.

o	Keras: High-level neural networks API, running on top of TensorFlow.

o	scikit-learn: For performance evaluation and metrics.

o	Pandas: For data manipulation and analysis.

o	NumPy: For numerical operations and array manipulations.

o	Matplotlib: For plotting and visualization.

o	mlxtend: For extended machine learning utilities, particularly for plotting confusion matrices.

o	Tools: Jupyter Notebook, Kaggle, or Google Colab.

