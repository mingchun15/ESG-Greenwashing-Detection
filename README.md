# ESG-Greenwashing-Detection

## Project Overview
This project aims to detect corporate greenwashing behavior by analyzing ESG/CSR reports using a combination of Large Language Models (LLMs) and machine learning techniques.

The framework integrates semantic (LLM-based), lexical, and financial features to improve prediction performance and analyze model behavior.

---

## Rsults

- Best Model: XGBoost (ChatGPT semantic features)
- F1-score: 0.7788
- ROC-AUC: 0.9779
- Llama F1 improved: 0.5150 → 0.7235 (+40.5%)

---

##  Key Insights

- Lexical features → improve Recall  
- Financial features → improve Precision  
- ChatGPT → more stable  
- Llama → more sensitive to prompts  

---

## 📈 Visualization

### SHAP (ChatGPT)
![ChatGPT SHAP](./plots/M6 Semantic + Lexical + Financial_shap_summary_chatgpt(4).png)

### SHAP (Llama)
![Llama SHAP](./plots/M6 Semantic + Lexical + Financial_shap_summary_llama(3).png)

### Prompt Sensitivity
![Prompt](ESG Greenwashing Detection with LLM + ML/plots/prompt_sensitivity_vs_discrimination_georgia.jpg)

---

## Tech Stack

Python / Pandas / Scikit-learn / XGBoost / PyTorch / LLM / yFinance
