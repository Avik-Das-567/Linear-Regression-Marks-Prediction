# Linear Regression with Streamlit - Marks Prediction
### App Link
- https://linear-regression-marks-prediction.streamlit.app/
---
### What is Linear Regression?
- Linear Regression is a **math method** used to **predict numbers**.
- It draws a **straight line** through data points.
- It helps **understand relationships** between two things.
- Example: Predicting **marks** based on **study hours**.
---
### Why Use Streamlit?
- **Streamlit** helps to build **data apps** in Python.
- We can **show our projects** with buttons and charts.
- It is **easy** and **quick** to use.
---
### Required Python Packages
- **`scikit-learn`** - To build machine learning models
- **`streamlit`** - To build data apps
- **`pandas`** - To work with the dataset
---
### Example Problem
- We have data about **Hours Studied** and **Marks Scored**.

| Hours\_Studied | Marks\_Scored |
| -------------- | ------------- |
| 2              | 50            |
| 3              | 60            |
| 4              | 70            |
| 5              | 80            |
| 6              | 90            |

---
### How It Works
- **Load the data** using **`pd.read_csv()`**.
- **Train a model** using **`LinearRegression()`**.
- Ask for **user input** using **`st.number_input()`**.
- **Show the result** using **`st.write()`**.
---
