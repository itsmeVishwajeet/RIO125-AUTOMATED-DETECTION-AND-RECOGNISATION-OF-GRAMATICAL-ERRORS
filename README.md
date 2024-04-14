**Grammatical Error Detection using BERT**

This project aims to develop a grammatical error detection system using BERT (Bidirectional Encoder Representations from Transformers). The system is trained on a dataset containing labeled sentences, with 0 indicating error sentences and 1 indicating grammatically correct sentences.

**Project Overview: -**
 
Project Name: - RIO125-Automated Detection and Recognition of Grammatical Errors. 
 
**User Need:**
 
The project aims to meet user needs by delivering an accurate and efficient automated 
grammatical error detection tool. Prioritizing ease of use, the system ensures a user-friendly 
interface with clear feedback and adaptability to diverse writing styles. Privacy measures and 
seamless integration with existing tools are emphasized, and optional features like 
customization and learning resources cater to individual preferences, creating a valuable tool 
for enhancing the writing experience. 
 
**Objective:**
 
The project's objectives include developing an accurate and efficient system for automated 
grammatical error detection. Utilizing machine learning and NLP techniques, the goal is to 
TKIET, Warananagar  2 
create a versatile tool that adapts to diverse writing styles. The project emphasizes user-friendly 
interfaces, thorough testing, and documentation to ensure robustness and accessibility. 
Continuous improvement, collaboration with mentors, and potential implementation of error 
correction suggestions contribute to the project's overarching objective of enhancing the quality 
of written language. 
 
**Problem Statement: -** The objective entails constructing a system entirely from the ground 
up, designed to identify and rectify grammatical errors within user-provided words and 
sentences. The entirety of the project is delineated into two distinct components:    
               I) The Grammatical Error Detection. 
    II) The Grammatical Error Recognition. 
 
Built a system from scratch in Python, which can detect grammatical errors in each word and 
sentence, respectively. 

**Dataset**

The dataset used in this project consists of labeled sentences, where each sentence is labeled as either 0 (error) or 1 (no error). The dataset is split into training, validation, and test sets for model development and evaluation.
Input Dataset Filename : input_file.csv

**Usage**

Training the Model: Use the provided code grammatical_error_detection.ipynb to train the grammatical error detection model. Make sure to adjust the paths to your dataset accordingly.

**It is important to run this code in devlopment environment which is GPU enabled**

Evaluation: Evaluate the trained model using the evaluation metrics provided in the notebook. Additionally, you can use the provided functions to calculate accuracy, precision, recall, and F1-score.

Inference: Once trained, the model can be used for inference on new sentences to detect grammatical errors. Use the provided functions for tokenization and inference.

**Results**

The results of the grammatical error detection model, including accuracy and other evaluation metrics, are presented in the notebook and can be further analyzed and visualized.

Also get two output file:
                  1.output_file_only_labeled(The output file which contains only lebels.)  
                  2.outpu_file (Which contains both labels and type of the error)
