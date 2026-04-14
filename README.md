#  ANN Date Fruit Classification

A deep learning-based multi-class classification model built using an Artificial Neural Network (ANN) to classify date fruits into 7 classes.

---

##  Project Overview

This project focuses on classifying date fruits into different categories using a deep learning approach.  
An ANN model is trained on a real-world dataset to learn patterns between input features and the corresponding date fruit class.

---

##  Dataset Information

The dataset consists of multiple numerical features describing physical and chemical properties of date fruits.

###  Features include:
- Area
- Perimeter
- Major Axis Length
- Minor Axis Length
- Eccentricity
- Convex Area
- Extent
- Solidity
- Roundness
- Aspect Ratio

###  Target Variable:
- Date Fruit Class (7 categories)

---

##  Workflow

1. Data preprocessing  
2. Splitting dataset into training and testing sets  
3. Feature scaling using StandardScaler  
4. Building ANN model using PyTorch  
5. Training the model  
6. Evaluating performance using:
   - Accuracy 

---

##  Model Architecture

- Input Layer (based on number of features)
- Hidden Layer 1: 64 neurons (ReLU)
- Hidden Layer 2: 64 neurons (ReLU)
- Output Layer: 7 neurons (Softmax for multi-class classification)

---

##  Model Performance

- Achieved strong classification performance on test data  
- Evaluated using accuracy

---

##  Tech Stack

- Python  
- PyTorch  
- NumPy  
- Pandas  
- Scikit-learn  

---


##  Project Structure

```
ann-date-fruit-type-classification/
│
├── DateFruit_ANN_Classification.ipynb
├── DateFruit_Dataset.csv
├── README.md
```


##  Future Improvements

- Hyperparameter tuning  
- Adding data visualization dashboards  

---

##  Author

Mahathi
