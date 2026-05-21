🏏 IPL 2026 Winner Prediction

A data science project predicting the IPL 2026 winner using historical IPL match data from 2008-2025 and current IPL 2026 standings.

🏆 Prediction Result

Royal Challengers Bengaluru
Gujarat Titans
Sunrisers Hyderabad
📊 Dataset

Ball-by-ball IPL data from 2008-2025
278,205 rows x 64 columns
Source: Kaggle

Current IPL 2026 points table data is added manually for prediction updates.

🔧 Method

Feature engineering using win rate, current points, net run rate, and recent form
Improved weighted scoring model with normalized features
Current standings are saved as JSON for the webpage
Libraries used: pandas, numpy, scikit-learn, matplotlib, seaborn

🌐 Webpage

A simple localhost webpage displays the final prediction table.

Run from the project folder:

py -m http.server 8000 -d web

Then open:

http://localhost:8000

📁 Project Structure

ipl-prediction/
├── data/
│ ├── IPL.csv
│ ├── ipl_2026_predictions.csv
│ └── model_features.csv
├── notebooks/
│ └── ipl_prediction.ipynb
└── web/
├── index.html
└── predictions.json

⚠️ Note

This project currently uses a weighted scoring model, not a full machine learning classifier.
