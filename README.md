# Pattern Recognition - Facial Expression Classification

This project explores different machine-learning classifiers to recognize happy and sad faces from grayscale 48×48 facial images.
It was developed as part of a Pattern Recognition homework assignment.

The project includes three parts:
```
Part 1 - Logistic Regression
Part 2 - SVM Classification
Part 3 - CNN Classification
```

---

## Project Structure
```
Pattern-Recognition-LRnNN/
│
├── .gitignore
├── DeshpandeAryaa_hw2.ipynb        # main notebook 
├── DeshpandeAryaa_hw2.pdf          # final report
│
├── helper.py                       # preprocessing + helper functions
├── Homework2.pdf                   # original assignment sheet
│
├── README.md                       
├── requirements.txt                

```

---

## Setup Instructions

### 1. Clone the repository
```
git clone https://github.com/aryaa-deshpande/Pattern-Recognition-LRnNN.git
cd Pattern-Recognition-LRnNN
```

### 2. Create a virtual environment 
```
python3 -m venv myenv
source myenv/bin/activate   

```

### 3. Install dependencies
```
pip install -r requirements.txt
```

---

## How to Run
	1.	Open the DeshpandeAryaa_hw2.ipynb notebook in Jupyter or VS Code.
	2.	Run the cells in order:
        •	Part 1 -> Logistic Regression
        •	Part 2 -> SVM Classification
        •	Part 3 -> CNN Classification
	3.	Each section trains a different model and reports:
        •	Validation and test accuracies
        •	Confusion matrix (printed and visualized)

---

## Results Summary

| **Model**              | **Validation Accuracy** | **Test Accuracy** | **Key Notes**                                      |
|-------------------------|-------------------------|-------------------|----------------------------------------------------|
| Logistic Regression     | ~68%                    | ~71%              | Simple linear model; baseline                      |
| SVM (Linear Kernel)     | ~70%                    | ~66%              | Similar to logistic regression                     |
| SVM (RBF Kernel)        | ~76%                    | ~74%              | Captures nonlinear boundaries                      |
| **CNN**                 | **~89%**                | **~85%**          | Best performance; learns spatial patterns in faces |


---
