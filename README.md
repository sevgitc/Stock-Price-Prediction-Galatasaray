# 📊 Galatasaray Stock Price Prediction

This is an end-to-end data analytics and machine learning project aiming to predict the stock prices of *Galatasaray Sports Club*, a publicly traded Turkish football club. The project compares multiple models and techniques including ARIMA, LSTM, Ridge Regression, and Random Forest.

---

## 📊 Data Sources

The project is based on two datasets:

1. **Galatasaray Stock Prices**  
   - Historical daily stock prices from **01/01/2014 to 03/18/2024**  
   - Columns: `Date`, `Open`, `High`, `Low`, `Close`, `Adj Close`, `Volume`  
   - Source: Yahoo Finance / Borsa Istanbul

2. **Galatasaray Match Results**  
   - Results of Galatasaray’s football matches from various leagues  
   - Chosen because Galatasaray is a sports club company and football is the most popular sport in Turkey  
   - Columns: `LeagueName`, `Date`, `LeagueMatchNo`, `isHome`, `GF` (Goals For), `GA` (Goals Against), `GD` (Goal Difference), `PlaceInLeague`, `PlaceOfOp` (Opponent Ranking)  
   - Retrieved from official match result archives

---

## 🔧 Technologies Used

- **Python** (pandas, scikit-learn, statsmodels, keras, matplotlib, seaborn)
- **Selenium & BeautifulSoup** (for web scraping)
- **Jupyter Notebook**
- **PowerPoint** (for final presentation)

---

## 🧠 Models Compared

| Model               | Summary |
|---------------------|---------|
| **ARIMA**           | Time-series model with stationarity assumptions, sensitive to autocorrelation |
| **LSTM**            | Sequence modeling with memory cell structure, better at temporal dynamics |
| **Ridge Regression**| Linear model with regularization, handled correlation better than Linear Regression |
| **Random Forest**   | Robust ensemble model, handled categorical + time-based splits better in this context |

> 📈 Full comparison and results are included in the presentation file.

---

## 📂 Project Files

| File/Folder | Description |
|-------------|-------------|
| [`notebooks/1_data_scraping.ipynb`](notebooks/1_data_scraping.ipynb) | Web scraping logic for collecting stock data |
| [`notebooks/2_modeling.ipynb`](notebooks/2_modeling.ipynb)      | Model development, evaluation, and comparison |
| [`documentation/final_presentation.pptx`](documentation/final_presentation.pptx) | Project summary and visualized results |
| [`documentation/model_results.xlsx`](documentation/model_results.xlsx) |  Model performance comparison table |

---

## 📌 Highlights

- End-to-end pipeline: scraping → cleaning → feature engineering → modeling → evaluation
- Real-world stock data used from a popular sports club
- Multi-model comparison with performance metrics (RMSE, MAE)
- Includes web scraping logic using Selenium
- Model performances were evaluated and summarized in a comparison table. See: [model_results.xlsx](documentation/model_results.xlsx)


---

## 👩‍💻 Author

**Sevgi Toprak Cetin**  
Developed as an individual project for **CSIS-4260 – Special Topics in Data Analytics**  
Post-Baccalaureate Diploma in Computer & Information Systems  
**Douglas College, Canada**

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

