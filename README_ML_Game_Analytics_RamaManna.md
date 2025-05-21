# ML-Powered Game Analytics

## 👤 Prepared by:
**Rama Manna'**

---

## 📌 Project Overview
This project uses machine learning to analyze player behavior in a simple 2D game. It aims to identify gameplay patterns, predict outcomes, and generate automatic suggestions to improve game design.

---

## 🧰 Technologies Used
- **Python** (Google Colab)
- **pandas** for data handling
- **matplotlib** and **seaborn** for visualizations
- **scikit-learn** for ML models (K-Means, Decision Tree)

---

## 🕹️ Game Description
- Simple browser-based 2D game
- Data includes: number of moves, session duration, win/lose result
- Player sessions were logged and saved in CSV format (`game_Rama_data.csv`)

---

## 📊 Analytics Dashboard
Key visualizations:
- Distribution of move counts by result
- Duration of gameplay by result
- Clustering players using K-Means
- Decision Tree for predicting win/lose

---

## 🤖 Machine Learning Implementation
- **K-Means Clustering:** Grouped players into 3 behavior clusters
- **Decision Tree Classifier:** Predicted player outcome based on session data
- **Insight Generation:** Automated recommendation: add tutorial around 10 moves / 30 seconds

---

## 🧪 How to Run
1. Open the Colab notebook
2. Upload `game_Rama_data.csv`
3. Run each cell in order
4. Outputs will show charts, clustering results, and predictions

---

## 📂 Repository Structure
```
/ML-Game-Analytics
├── game_Rama_data.csv
├── game_analytics.ipynb
├── report.pdf
├── video_script.docx
└── README.md
```

---

## 📝 Author Note
This project was completed as part of a coursework assignment on machine learning for games. It shows how simple models can give valuable insights for developers.

---

## 📎 License
This project is for academic use only.
