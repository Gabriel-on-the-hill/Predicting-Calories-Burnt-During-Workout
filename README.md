# Predicting Calories Burnt

## Overview

This project analyzes a workout dataset to predict the number of calories burned during an exercise session. The dataset includes key biometric and exercise features such as age, gender, height, weight, workout duration, heart rate, and body temperature.

The aim is to assist personalized fitness planning by helping trainers and health professionals tailor safe and effective workouts for their clients.

## Project Phases

The project was executed in five key phases:

1. **Data Understanding and Cleaning**
2. **Exploratory Data Analysis (EDA)**
3. **Feature Engineering and Selection**
4. **Model Building (Linear Regression)**
5. **Insights and Conclusion**

## Dataset

- **Features Used:**
  - Age
  - Gender
  - Height
  - Weight
  - Duration (minutes)
  - Heart Rate
  - Body Temperature (°C)
- **Target Variable:** Calories Burned

> The dataset is assumed to be clean and ready for analysis, although standard preprocessing steps were carried out.

## Installation & Setup

1. Install [Anaconda](https://www.anaconda.com/) and launch **Jupyter Notebook**.
2. Open the notebook file: `Predicting Calories Burnt.ipynb`.
3. Run all cells to perform data analysis and prediction.

Required Python libraries:

```bash
pandas
numpy
matplotlib
seaborn
mplcursors
```

These libraries are typically bundled with Anaconda.

## Key Insights

- Strong correlations were found between workout duration, heart rate, and calories burned.
- Gender showed minor variation in calorie burning after controlling for other variables.
- A **Linear Regression model** was used to predict calorie expenditure, providing interpretable results with good performance for practical use cases.

## License

This project is licensed under the [MIT License](LICENSE).

## 👤 Author

**Gabriel Amao**  
📧 [Email](mailto:ojoayoamao9418@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/ojoayo)

---

*This project supports evidence-based fitness decisions using data-driven predictions.*
