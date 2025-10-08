# Credit Risk Scoring Model

This project develops a machine learning model to predict borrower credit risk levels using financial and demographic features. It demonstrates the end-to-end process of cleaning data, training models, and interpreting results with SHAP.

## Overview
- **Goal:** Predict credit risk (low vs. high) based on borrower data.  
- **Tech Stack:** Python, Pandas, Scikit-learn, XGBoost, SHAP  
- **Key Steps:**
  1. Data preprocessing and cleaning  
  2. Exploratory data analysis (EDA)  
  3. Feature engineering  
  4. Model training and evaluation  
  5. Explainability using SHAP  

## Key Insights
- XGBoost achieved the highest performance with ~89% accuracy.  
- SHAP analysis revealed that income, credit history, and DTI ratio strongly influence predictions.  

## Files
- `Credit Risk Scoring.ipynb` — main notebook with full workflow  
- `requirements.txt` — list of libraries used  

## Future Improvements
- Add hyperparameter tuning  
- Deploy using Streamlit for interactive scoring  
- Include more granular financial features  

## License
Released under the MIT License.

---
> **Author:** Yusuf Babatunde Jubril  
> Linkedin - www.linkedin.com/in/babatunde-jubril-yusuf 
