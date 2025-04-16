
### 📝 **Project Description**

This Jupyter Notebook is dedicated to the **preprocessing** of the [Simple Gender Classification](https://www.kaggle.com/datasets/muhammadtalharasool/simple-gender-classification) dataset from Kaggle. The dataset contains demographic information such as age, height, weight, education level, marital status, occupation, income, and favorite color, along with the target variable — **Gender** (Male or Female).

The goal of this project is to **prepare the dataset for machine learning model training** by performing the following steps:

- Loading and inspecting the raw data
- Cleaning and formatting feature names
- Removing duplicate entries and irrelevant columns
- Encoding categorical variables (one-hot, label, frequency, and manual mappings)
- Detecting and visualizing outliers using boxplots
- Scaling numerical features using MinMaxScaler
- Mapping the target variable `Gender` to numeric format
- Saving the processed dataset in both CSV and Pickle formats for future model training

This preprocessing ensures that the dataset is clean, consistent, and ready for use in supervised learning models for gender prediction.
