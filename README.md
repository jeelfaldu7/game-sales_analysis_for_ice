# 🎮 Game Sales Analysis for Ice
## 📘 Project Overview
This prject analyzes video game sales data for the online store Ice, which sells games globally. The goal is to identify patterns that help predict whether a game will succeed, so the company can identify potential htis and plan more effective advertising campaigns. 
Using historical data up to 2016, this analysis assumes it is December 2016 and aims to forecast game performance for 2017. The project includes data cleaning, exploratory analysis, regiobal user profiling, and hypothesis testing. 

## 🧠 What I Learned
- How to clean and preprocess real-world messy data?
- Identifying patterns in time-series game release trends.
- Analyzing regional sales behaviors and genre/platform popularity.
- Applying hypothesis testing to real business questions.
- Understanding correlation in user reviews and sales.

## 🛠 Tools & Technologies
  - Python (Pandas, Matplotlib, Seaborn, SciPy)
  - Jupyter Notebook
  - Data visualization
  - Statistical hypothesis testing

## 🗂 Table of Contents
  - Project Overview
  - What I Learned
  - Tools & Technologies
  - Key Findings
  - Hypothesis Testing
  - Conclusion
  - How to Run the Project
  - Credits

## 📊 Key Findings
### Trends in Game Releases
- Game releases peaked in 2008 and declined drastically after 2011.
- The decline may be due to incomplete data, changing platforms, or shifting industry dynamics.
### Platform Insights
- Platforms like Wii had high peak sales but faded instantly.
- PS4 and XOne showed the most potential heading into 2017.
- Older platforms like PS3, X360, and 3DS were declining.
### Genre Insights
Action is the most common genre but has low sales per game.
Shooter games, while fewer in number, are more profitable per title.
High average sales: Shooter, Sports, and Role-Playing.
Low average sales: Puzzle, Strategy, and Simulation.
### 🌍 Region-specific preferences by platform, genre, and ESRB rating.
  - North America & Europe:
      - Top-selling platforms: PS4, XOne
      - Preferred genres: Shooter, Sports, Action
      - ESRB ratings matter – M-rated (Mature) games sell the most followed by E-rated games
  - Japan:
      - Top platform: 3DS
      - Preferred genres: Role-Playing
      - ESRB ratings have less impact; more cultural variability - T-rated games are favored and shows a strong prefrence foor handheld platforms. 

## 🔬 Hypothesis Testing
Test 1: Are average user ratings the same for Xbox One and PC?
- Null Hypothesis (H₀): Mean ratings are equal
- Result: p > 0.05, fail to reject H₀ → No significant difference
Test 2: Are average user ratings different between Action and Sports games?
- Null Hypothesis (H₀): Mean ratings are equal
- Result: p < 0.05, reject H₀ → Significant difference found

## ✅ Conclusion
The analyasis provided a data-driven way to forecast game success for 2017. By focusing on top-performing platforms (PS4,XOne), understanding genre profitability, and analyzing regional preferences, Ice can make smarter decisions about game promotions and inventory. 
Most importantly, we found that while reviews have only a weak correlation with sales platform trends, genre choice, and regional preferences are strong predictors of success. 

## 💻 How to Run the Project
1. Clone the repo or download the notebook.
2. Install Python and required libraries:
``` bash
pip install pandas matplotlib seaborn scipy
```
3. Open the Jupyter Notebook and run each cell in order.

## 🤝 Credits
This project was created as part of the TripleTen Data Science program. Special thanks to:
Kaggle forthe original dataset
TripleTen instructors and peers for ongoing support and feedback

## 🛡️ License
This project is licensed under the MIT License.
