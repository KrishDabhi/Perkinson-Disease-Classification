# Parkinson’s Disease Classification using XGBoost  

## 📌 Overview  
This project applies the **XGBoost Classifier** to detect Parkinson’s Disease from biomedical voice measurements. The model learns to differentiate between healthy individuals and patients with Parkinson’s Disease, providing a decision-support tool for healthcare applications.  

---

## 📊 Dataset  
- **Source**: UCI Machine Learning Repository – Parkinson’s Disease Dataset  
- **Samples**: 195  
- **Features**: 23 biomedical voice attributes  
- **Target**:  
  - `1` → Parkinson’s Disease  
  - `0` → Healthy  

---

## ⚙️ Workflow  
1. Data preprocessing: scaling and cleaning  
2. Correlation analysis (heatmap)  
3. Train-test split  
4. Model training with **XGBoost Classifier**  
5. Evaluation using accuracy, precision, recall, F1-score, ROC-AUC  

---

## 🚀 Model  
- **Algorithm**: XGBoost Classifier  
- **Key Parameters**:  
  - `learning_rate = 0.1`  
  - `max_depth = 10`  
  - `scale_pos_weight = 1.5`  
  - `eval_metric = "mlogloss"`  

---

## 📈 Results  
- **Accuracy**: ~94% on test set  
- Evaluated with precision, recall, and F1-score  
- Results consistent across different runs  

---

## 💻 How to Run  

1. Clone repository:  
```bash
git clone https://github.com/your-username/Parkinson-XGBoost.git
cd Parkinson-XGBoost
```

2. Install dependencies:  
```bash
pip install -r requirements.txt
```

3. Run Jupyter Notebook:  
```bash
jupyter notebook Perkinson_Disease_Classification.ipynb
```

---

## 🔮 Future Work  
- Hyperparameter tuning for optimization  
- Feature importance analysis  
- Deploy with Streamlit or Flask  

---

## 📜 License  
MIT License  
