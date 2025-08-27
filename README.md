# 🎬 Movie Success Prediction

This project focuses on creating a dataset for movie success prediction and uses a **Random Forest Classifier** to predict whether a movie will be successful based on key features like `genre`, `year`, and `duration`. Built with mythic modularity and diagnostic clarity, the model is versioned, logged, and ready for reproducible deployment.

---

The dataset is created by taking data from IMDb.  
Libraries used to extract data include: **requests**, **BeautifulSoup**, **Selenium**


## 📊 Model Performance

| Metric         | Value    |
|----------------|----------|
| **Accuracy**   | `84.67%` |
| **F1 Macro**   | `0.85`   |
| **Version**    | `v1.0.0` |
| **Date**       | `2025-08-27` |

> 🔮 _Entropy-based splits and balanced class weights ensure mythic precision across genres and runtimes._

---

## ⚙️ Features Used

- `genre`: Categorical feature representing movie genre (e.g., Action, Drama, Comedy)
- `year`: Release year of the movie
- `duration`: Runtime of the movie in minutes
- `director`: Categorical feature representing the filmmaker whose reputation and style may influence a movie's success.
---

[For the director column i took only those names which have movies more than or equal to 10 and the rest are labeled as "others"]
