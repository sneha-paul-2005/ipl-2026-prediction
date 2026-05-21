# 🏏 IPL 2026 Winner Prediction

A data science project predicting the IPL 2026 winner using 
historical match data from 2008–2025.

## 🏆 Prediction Result
1. Royal Challengers Bengaluru
2. Rajasthan Royals
3. Delhi Capitals

## 📊 Dataset
- Ball-by-ball IPL data (2008–2025)
- 278,205 rows × 64 columns
- Source: Kaggle

## 🔧 Method
- Feature engineering: win rate, toss advantage, current form, NRR
- Weighted scoring model with MinMaxScaler normalization
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

## 📁 Project Structure
ipl-prediction/
├── data/
│   ├── ipl_2026_predictions.csv
│   └── model_features.csv
└── notebooks/
    └── ipl_prediction.ipynb
