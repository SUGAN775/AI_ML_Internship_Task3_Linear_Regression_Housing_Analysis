# 🏠 AI/ML INTERNSHIP TASK 3: MULTIPLE LINEAR REGRESSION FOR CALIFORNIA HOUSING PRICE PREDICTION

This repository showcases the successful execution of **AI/ML Internship Task 3**, focusing on a comprehensive **Multiple Linear Regression (MLR)** analysis of the California Housing Dataset. The core objective was to build a robust predictive model for the **median house value**, demonstrating proficiency in the full Machine Learning pipeline, from data preparation to rigorous statistical validation. This project highlights the ability to extract meaningful insights from large-scale geographical and demographic data.

## 🛠️ Methodology and Data Preprocessing

### Data Wrangling and Feature Engineering

The workflow commenced with meticulous data handling using **Pandas** ($\text{🐼}$). Initial steps addressed minor data quality issues, such as missing values in `total_bedrooms`, which were handled through **median imputation**. Crucially, the categorical feature $\text{ocean\_proximity}$ was successfully converted into a numerical format via **One-Hot Encoding**, a necessary transformation to satisfy the input requirements of the linear model. This stage ensured that all features were optimized for high-quality model training.

### ⚙️ Model Training and Execution

The refined dataset was partitioned using a **train-test split** ($\text{🔪}$) to establish a separate, unseen validation set. The **Scikit-learn** ($\text{🧠}$) library was utilized to implement and train the **Multiple Linear Regression** model. This step involved fitting the optimal linear coefficients that map the influence of features—such as median income and house age—onto the target median house value, thereby creating a transparent and interpretable predictive function.

## 📈 Statistical Evaluation and Inference

### Robust Performance Assessment

The predictive performance of the MLR model was rigorously evaluated on the held-out test data. This objective assessment utilized three industry-standard metrics, providing a comprehensive view of the model's accuracy, precision, and overall fit. The evaluation results are crucial for understanding the model's reliability in a real-world deployment scenario.

### Key Evaluation Metrics

* **Mean Absolute Error (MAE):** Represents the **average prediction error** ($\text{🎯}$) in the original currency units, providing an intuitive measure of accuracy.
* **Mean Squared Error (MSE):** **Heavily penalizes larger errors** ($\text{⚠️}$) by squaring the residuals, ensuring the model is robust against significant outliers in housing prices.
* **Coefficient of Determination ($\mathbf{R^2}$ Score):** Quantifies the **proportion of variance explained** ($\text{🌟}$) by the input features. A high $R^2$ confirms the strong explanatory power of the developed model.

## 🌟 Conclusion and Key Technologies

This task successfully demonstrates expertise in applying statistical learning techniques to solve real-world prediction problems. The project leverages **Python** ($\text{🐍}$), **Pandas**, and **Scikit-learn** to deliver a fully functional and statistically validated housing price prediction solution.

---
