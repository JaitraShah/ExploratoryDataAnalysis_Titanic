# ExploratoryDataAnalysis_Titanic
- Generated summary statistics using `df.describe()` and `df.info()`
- Plotted:
  - **Histogram** of `Age` to observe distribution
  - **Boxplot** of `Fare` to detect outliers
- Encoded categorical features (`Sex`, `Embarked`) to prepare for correlation
- Created a **Correlation Matrix** using Seaborn’s heatmap
- Used **Pairplot** to visualize relationships between key features

### Key Insights:
- Majority of passengers were aged 20–35
- Fare distribution is right-skewed with many outliers
- `Pclass` negatively correlates with both `Fare` and `Survived`
- `Sex` positively correlates with survival (females more likely to survive)
