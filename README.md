# Signature-Classification-Using-Siamese-Network
This project aims to develop and implement a Siamese Network for Classifying handwritten signature as genuine or forged.

## Overview
This project aims to develop and implement a **Siamese Network** for classifying handwritten signatures as **genuine** or **forged**. The network is trained using **contrastive loss** and **triplet loss**, leveraging distance-based learning to differentiate between authentic and counterfeit signatures.  

The dataset used for this project is available on **Kaggle - Signature Forgery Dataset**, containing images of handwritten signatures labeled as **genuine** or **forged**.  

## Problem Statement
**Signature verification** is an essential task in **security, banking, and legal applications**. Traditional classification models struggle with this problem due to:  

**High intra-class variability**: Genuine signatures may have slight variations in stroke pressure, pen type, and style.  
**Subtle differences between genuine and forged signatures**: Some forgeries closely resemble authentic signatures.  

A **Siamese Neural Network** is particularly suited for this task as it learns a **similarity function** rather than explicit class labels.  

### **Project Objectives**
Implement a **Siamese Network** to classify signatures as **genuine or forged**.  
Train the network using **contrastive loss** and **triplet loss**.  
Evaluate the model using standard metrics: **accuracy, precision, recall, and F1-score**.  
Analyze the results and provide insights into model performance.  

## Dataset Details
The dataset consists of **handwritten signature images**.  
**Two classes**: Genuine signatures and Forged signatures.  
The dataset is **split into training, validation, and test sets**.  
**Pairs of images** (genuine-genuine, genuine-forged) are used for training.  

## Challenges in the Dataset
**Intra-class variations**: Genuine signatures may vary slightly based on stroke pressure, pen type, and signature style.  
**Inter-class similarities**: Some forgeries can be very close to genuine signatures.  
**Limited labeled data**: Few examples per person, making it suitable for **Few-Shot Learning**.
