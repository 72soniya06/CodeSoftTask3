# CodeSoftTask3
# 📈 Sales Prediction using Machine Learning

This project predicts product sales based on advertising and marketing data.  
By analyzing past sales figures and features such as TV, radio, and newspaper advertising spend, the model estimates the expected sales for new campaigns.

---

## 📌 Project Overview

Sales prediction is a common business analytics problem.  
This project demonstrates how to:

- Load and explore a sales dataset.
- Preprocess and clean the data.
- Train a regression model to predict sales.
- Evaluate the model’s performance.
- Deploy a **Gradio** GUI for easy user interaction.

---

## 📂 Dataset Description

A typical dataset for sales prediction contains the following columns:

| Column     | Description |
|------------|-------------|
| TV         | Advertising budget for TV (in $ thousands) |
| Radio      | Advertising budget for Radio (in $ thousands) |
| Newspaper  | Advertising budget for Newspaper (in $ thousands) |
| Sales      | Sales in units (target variable) |

---

## ⚙️ Installation & Requirements

Make sure you have Python 3.7+ installed.

Install dependencies:

```bash
pip install pandas numpy scikit-learn gradio
