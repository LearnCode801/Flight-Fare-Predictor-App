# Flight Fare Prediction Project

![Flight Fare Prediction Screenshot](https://github.com/LearnCode801/Flight-Fare-Predictor-App/blob/main/Screenshot%202024-10-30%20125817.png)

This project was focused on predicting flight prices in India. The goal was to build a system where users can select their trip details — departure city, destination city, travel date, time, airline, and number of stops — and then receive a predicted ticket price.

For example, if I wanted to travel from Delhi to Hyderabad, I could select the date, time (AM/PM), airline (such as Air Vistara or Jet Airways), and whether I preferred a nonstop or one-stop flight. After submitting these details, the system would predict the expected price — in one case, the prediction returned was ₹13,979.57.

To build this project, I worked extensively in Jupyter Notebook. I began by loading and exploring the dataset. I performed both **automatic EDA (Exploratory Data Analysis)** and **manual EDA** to fully understand the data. Then, I did **feature engineering** to extract relevant features such as journey date, month, departure time, and number of stops.

I also performed thorough data preprocessing and visualization to better prepare the dataset for modeling. After that, I implemented several regression algorithms including **Linear Regression**, **Decision Tree Regression**, **Random Forest Regression**, and others. I used techniques like **hyperparameter tuning** to improve model performance.

I evaluated the models using metrics like **R² score** to measure how well the models were predicting prices. To boost performance, I also tried **advanced gradient boosting algorithms** such as CatBoost, LightGBM, and XGBoost, which gave more accurate results.

Once the best-performing model was selected, I moved on to **model deployment**. I built a **Flask web application** that allows users to input their trip details and receive price predictions in real time. I pushed all the code to **GitHub** and deployed the app to **Heroku**, making it accessible online.

Overall, this project gave me hands-on experience with end-to-end machine learning pipelines, including data preprocessing, model building, hyperparameter tuning, model evaluation, and deployment.

---

📂 **Project Links:**

* 📄 **Code:** [Flight Price Notebook](https://github.com/LearnCode801/Flight-Fare-Predictor-App/blob/main/FlightPriceNotebookCode.ipynb)
* 📝 **Full Documentation Report:** [Read the Report](https://github.com/LearnCode801/Flight-Fare-Predictor-App/blob/main/Report.pdf)
* 🎥 **Video Demo:** [Watch Here](https://lnkd.in/p/dC2Q563F)

---
