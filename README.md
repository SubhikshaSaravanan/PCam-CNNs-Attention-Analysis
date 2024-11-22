# PCam-CNNs-Attention-Analysis

### Overview 
This project explores the use of Convolutional Neural Networks (CNNs) enhanced with attention mechanisms to improve the classification of metastatic tissue in histopathological images from the PatchCamelyon (PCam) dataset. The dataset consists of 327,680 labeled images from lymph node sections, which serve as a benchmark for automated cancer detection. By integrating attention layers (channel and spatial attention) into the CNN architecture, the model can focus on the most critical regions in the images, improving classification accuracy and interpretability. The results show that the CNN with attention outperforms the baseline model, achieving higher accuracy (83.1% vs. 78.6%), F1 score (80.8% vs. 73.6%), and recall (70.9% vs. 59.8%), while reducing false negatives and improving generalization. This work demonstrates the effectiveness of attention mechanisms for enhancing CNN models in complex tasks like medical imaging, with potential applications in automated cancer detection.

### Files 

#### a) demo.py
This contains the data loading, data prepreocessing/augmentation, EDA, selected model run, and model evaluation. No training is required to run this file. It directly imports the trained model. (placeholder google colab link)

#### b) CNN_Training.inpyb <placeholder name>
This contains the training process for the baseline CNN model. (placeholder google colab link)

#### c) CNN_Attention_Training.ipnyb <placeholder name>
This contains the training process for the selected model which includes CNN + Attention Architecture. (placeholder google colab link)

### How to Run?
1. For ".ipnyb" files ( using Google Colab/Jupyter) - For google colab, Please use above corresponding links and paste in your Google Chrome browser. Navigate to the first cell, In the "Runtime" option in the menu bar, select "Run All". Similar steps to be followed for Jupyter.
2. For ".py" file - Python needs to be installed on your local system. Please use either command line or any code editor to run the ".py" file
   
### Requirements 
Infrastructure supporting:
1. ".ipnyb" files i.e. either Google Colab and Jupyter
2. ".py" files.


