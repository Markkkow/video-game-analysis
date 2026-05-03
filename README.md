# Video Game Sales Analysis

> Exploratory Data Analysis and Machine Learning to predict global video game sales based on platform, genre, publisher, and regional market data.

---

## Overview

This project analyzes a dataset of **16,598 video games** released between 1980 and 2016, covering global sales across 4 regions (North America, Europe, Japan, and Other markets).

**Main objectives:**
- Discover sales trends and patterns in the global video game market
- Identify the most popular genres, platforms, and publishers
- Explore how sales differ across regions
- Build a Machine Learning model to predict a game's global sales

---

## Key Insights

| Insight | Finding |
|---|---|
| Top Genre | Action |
| Top Platform | PS2 |
| Largest Market | North America (~49%) |
| Peak Year | 2008–2009 |
| Best ML Model | Random Forest |

---

## Project Structure

```
video-game-analysis/
│
├── data/
│   └── vgsales.csv                     # Dataset
│
├── notebooks/
│   └── video_game_analysis.ipynb       # Main notebook (EDA + ML)
│
├── images/
│   ├── yearly_trend.png
│   ├── genre_analysis.png
│   ├── platform_sales.png
│   ├── regional_sales.png
│   ├── genre_trend.png
│   ├── top_publishers_games.png
│   ├── model_comparison.png
│   └── feature_importance.png
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Markkkow/video-game-analysis.git
cd video-game-analysis
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the notebook
```bash
jupyter notebook notebooks/video_game_analysis.ipynb
```

Then go to **Kernel → Restart & Run All** to execute all cells.

---

## Dependencies

```
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.4.0
seaborn>=0.11.0
scikit-learn>=0.24.0
jupyter>=1.0.0
```

---

## Analysis Results

### Sales Trend
Global game sales peaked around **2008–2009** with the rise of the PS3, Xbox 360, and Wii. The market has since declined with fragmentation across mobile and digital platforms.

### Genre & Platform
- **Action** is the most popular genre by total sales volume
- **PS2** holds the all-time record for platform sales
- North America accounts for nearly half of all global sales

### Machine Learning Results

| Model | RMSE | R² Score |
|---|---|---|
| Linear Regression | ~0.55 | ~0.12 |
| Random Forest | ~0.48 | ~0.28 |
| Gradient Boosting | ~0.50 | ~0.22 |

**Random Forest** performs best. Regional sales (NA, EU, JP) are the strongest predictors of global sales.

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-1.3-lightblue?logo=pandas)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0.24-orange?logo=scikit-learn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

---

## Author

**[Marko Hasbi Rahman]**
📧 markohasbi@gmail.com
🔗 [LinkedIn](https://www.kaggle.com/markohasbirahman) | [GitHub](https://github.com/Markkkow)

---
