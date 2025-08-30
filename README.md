
# Water Pollution Detection – Week 1 Project

This repository contains a baseline ML solution to predict **Potability** (0/1) from common water-quality indicators.

## Contents
- `data/water_quality.csv` – sample dataset (synthetic, Kaggle-like schema)
- `Water_Pollution_Detection_Week1.ipynb` – end-to-end notebook (EDA → modeling → export)
- `requirements.txt` – install dependencies
- `model_random_forest.joblib` – saved model (created after running the notebook)

## How to Run (Locally or Colab)
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Open and run the notebook:
   ```bash
   jupyter notebook Water_Pollution_Detection_Week1.ipynb
   ```
   or upload to Google Colab and run all cells.

3. (Optional) Replace `data/water_quality.csv` with your dataset having columns:
   `ph, Hardness, Solids, Chloramines, Sulfate, Conductivity, Organic_carbon, Trihalomethanes, Turbidity, Potability`

## What to Submit (Week 1)
- Push all files to a **public GitHub repo** named `Week1` (or any name).
- Paste the **GitHub repository link** in your **LMS → Week 1 Project Submission** field and click **Submit**.

## Notes
- This is a baseline model. You can improve with hyperparameter tuning, additional features, and model comparison in Week 2.
