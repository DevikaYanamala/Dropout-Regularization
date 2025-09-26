# Dropout-Regularization

# 🧠 Dropout Regularization on Sonar Dataset

This project demonstrates the effect of **Dropout Regularization** in a neural network using the **Sonar dataset**.  
The dataset contains **208 sonar signals**, each with **60 numeric features**, classified into two categories:
- **R** → Rock  
- **M** → Mine  

The goal is to show how dropout reduces **overfitting** and improves generalization in deep learning models.

---

## 📊 Project Workflow
1. Load the dataset (`pandas`, `numpy`)  
2. Encode categorical labels into numeric format  
3. Split dataset into **train/test sets**  
4. Build a baseline **neural network classifier** with Keras  
5. Train and evaluate the baseline model  
6. Add **Dropout layers** to reduce overfitting  
7. Compare performance before vs after dropout  

---

## ⚙️ Features
- Data preprocessing and encoding  
- Baseline deep learning model without dropout  
- Regularized model with dropout  
- Evaluation with accuracy and classification report  

---

## 🚀 Tech Stack
- **Python 3**  
- **pandas** → data handling  
- **NumPy** → numerical computations  
- **scikit-learn** → preprocessing, train-test split, evaluation  
- **TensorFlow/Keras** → neural networks & dropout  


---

## 🔧 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/DevikaYanamala/dropout-regularization.git
   cd dropout-regularization
   pip install -r requirements.txt
   jupyter notebook dropout_regularization.ipynb
