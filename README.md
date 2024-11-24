# RockPaperScissor-Classification

I created this project while participating in the beginner class scholarship program from IDCamp 2023 in studying the Data Scientist learning path at Dicoding Indonesia.

![image](https://github.com/user-attachments/assets/af899821-e8d4-442b-9185-b064f3251e32)


## Overview

The dataset I used comes from the Indonesian dicoding asset and contains images of rock, paper, and scissors.

![image](https://github.com/user-attachments/assets/974685dd-1714-45b5-89c5-f0a4bd01d00b)
![image](https://github.com/user-attachments/assets/86c844c6-ae06-4be6-a935-2c8ed1e81c59)
![image](https://github.com/user-attachments/assets/bade6827-cbdf-46fe-862c-8465b3480585)

About | Description
:---|:---
Dataset | RockPaperScissors [Click here](https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip).
Data All  | 2188 images.
Categories | Rock, Paper, Scissors.
Data Training | 1312 Images.
Data Testing | 876 Images.

The main folder contains 2188 Images divided in 3 categories each containing images with 250x300 RGB resolution and PNG file extension.

## Installation

This project requires pandas, matplotlib, seaborn, sklearn, Pillow, OpenCV, tensorflow libraries. So, you may need to install these packages if you want to test it. 

To get started with this project, follow these installation steps:

Setup environment - Anaconda:
- Open Anaconda Terminal
- Run the following command to create a new environment:
```
conda create --name main-ds python=3.11
```
- Activate the virtual environment by running the following command:
```
conda activate main-ds
```
- Install the library to use:
```
pip install -r requirements.txt
```

## Objective

The process I did was as follows:

- Data Understanding
- Split Training and Test data
- Augmentation & ImageDataGenerator
- Modeling: Sequential Algorithm (LSTM)
- Evaluation
- Testing

## Result

I obtained an accuracy rate of 97%, so I can conclude that the model works effectively using the LSTM architecture. In addition, I evaluated the model using the AUC-ROC curve, Confusion Matrix, and Classification Report.

**AUC-ROC curve**

![image](https://github.com/user-attachments/assets/199eaf4d-6f32-43db-b50c-ad075409a43f)

![image](https://github.com/user-attachments/assets/132021cd-5aa7-4070-aa48-49d15518b4a5)

**Confusion Matrix**

![image](https://github.com/user-attachments/assets/e9d3ff10-7436-4b78-be26-c955b353d92e)

**Classification Report**

![image](https://github.com/user-attachments/assets/4c3c70fc-473f-43f0-8edc-3a1d418d4663)

**Testing**

![image](https://github.com/user-attachments/assets/c22c92cc-5bf7-4e1a-9cba-f07ad9cc96c2)