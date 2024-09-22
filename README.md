
---

# 💼 Salary Prediction Model

This project aims to build a machine learning model that predicts an individual's salary based on their years of experience. It uses a simple linear regression model to analyze the relationship between these two variables and predict future salaries.

## 🗂 Project Structure

- **📓 Salary.ipynb**: Jupyter notebook containing the code for loading the data, training the linear regression model, and visualizing the results.
- **📊 Salary_Data.csv**: The dataset used for training and testing the model. It contains two columns:
  - `YearsExperience`: The number of years of work experience.
  - `Salary`: The corresponding salary for that experience level.

## ⚙️ Requirements

To run the project, you'll need the following Python packages:
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`

Install the required packages using the following command:

```bash
pip install numpy/pandas/matplotlib/scikit-learn
```

## 📁 Dataset

The dataset (`Salary_Data.csv`) contains two columns:
- `YearsExperience`: Years of experience for different individuals.
- `Salary`: Corresponding salary of those individuals.

## 🚀 Usage

1. Clone this repository and navigate to the project directory.
2. Open the Jupyter notebook `Salary.ipynb` using JupyterLab or Jupyter Notebook.
3. Run the notebook cells to load the dataset, train the linear regression model, and view the results.

Alternatively, use the following command to start Jupyter:

```bash
jupyter notebook Salary.ipynb
```

## 🧠 Model

This project uses a simple linear regression model from `sklearn` to predict salary based on years of experience. The process involves:
1. 📑 Splitting the dataset into training and testing sets.
2. 🛠️ Fitting a linear regression model to the training data.
3. 📈 Evaluating the model's performance on the test data.
4. 🖼️ Visualizing the predictions.

## 📊 Visualization

The notebook contains visualizations that show:
- 📍 A scatter plot of the data points.
- 📏 The regression line fitted to the data.

## 🔚 Conclusion

This project provides a basic demonstration of how to use linear regression for salary prediction. It can be extended with more features or applied to other datasets for further exploration.

---
