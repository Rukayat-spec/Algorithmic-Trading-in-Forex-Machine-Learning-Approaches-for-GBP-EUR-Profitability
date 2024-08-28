**Project Title**

<h5> Algorithmic Trading in Forex: Machine Learning Approaches for GBP/EUR Profitability.</h5>

**Project Overview** 

<h6> Forex trading involves the exchange of currency pairs, aiming to profit from changes in exchange rates. Algorithmic trading leverages computer programs to execute trades based on predefined rules, often informed by historical data and predictive models. This project focuses on creating and assessing algorithmic trading strategies for the GBP/EUR currency pair. It will utilize machine learning models such as Gated Recurrent Unit(GRU), Extreme Gradient Boosting (XGBoost), and Gaussian Processg to predict market trends and improve trading outcomes. The strategies will be evaluated through backtesting on historical data and compared against baseline trading strategies to assess their profitability and robustness. This exploration aims to provide valuable insights into the efficacy of machine learning in developing profitable forex trading strategies.</h6>

**Project Structure**
1. Data Collection
Forex Price Historical data dated from Septmeber 2003 to May 2024.
2. Data cleaning, preprocessing, Exploratory Data Analaysis (EDA)
Clean the dataset: Handle missing values, drop unused columns(Adjascent close and Volume).
Compute and add technical indicators: EMA (50, 200), RSI (14), MACD (12, 26, 9), ADX to the historical dataset.
Data Augmentation to increase records of dataset to increase the robustness of modelling.
3. Model Development
Dataset Split, create sequences, and scale data for modeling.
Build and Train three models: GRU, XGBoost, and Guassian Process Regressor.
Hyperparameter Tuning: Optimize model performance using Grid search Hyper parameter tuning for GRU model
4. Model Performance Evaluation
Model Performance Metrics: Evaluate models using performance metrics like MAE, RMSE,R2 Score, MSE, and MAPE.
5. Creating Trading Strategy
Define trading strategy rules; buy and sell signals 
Trade Simulation and Strategy Performance Metrics
6. Trading Strategy Performance Evaluation
Analyze the results and compare them with existing literature.
Limitations and Future work
7. Conclusion
Summary of Achievements
Reflection
Future research and Recommendations 


**Data Overview**

<h6> The dataset used in this project consists of 5402 records of historical GBP/EUR forex data spanning over 20 years. It includes the following columns: Date, Open, Close, Low, High, Adjacent Close, and Volume prices. The data has been ethically sourced from Yahoo Finance and preprocessed to ensure quality and accuracy. The dataset has been thoroughly checked to ensure GDPR compliance.
Technical Indicators are calculated and added to the data to inrease the robustness of the models. </h6>

**Dependencies**

<h6>Install or use any Python IDE preferably Google Colab or Jupyter notebook.</h6>

<h6>Install any required Python library packages for EDA, Model Development, and Performance Evaluation, preferably using pip, pip install -r requirements.txt</h6>
<h6>Libraries: pandas, numpy, scikit-learn, keras, matplotlib, tensorflow, joblib.</h6>

**Results**
<h6>This project demonstrated that integrating machine learning models with traditional technical indicators can improve Forex trading strategies. The GRU, XGBoost, and GPR models each contributed valuable insights, with the GPR model particularly excelling in maximizing returns. The project successfully met its goal by developing and evaluating these models, highlighting their potential in algorithmic trading.</h6>

**How to Use the Project**

<h6> Data Analysis: Use the Google Colab in the notebooks directory to explore the data and identify trends.</h6>
<h6> Model Development: Modify and run the model training script to develop and compare different machine-learning models.</h6>
<h6> Strategy Creation: Utilize the predictions from the trained models and combine them with technical indicators to create trading strategies.</h6>
<h6> Backtesting and Optimization: Use the evaluation script to backtest the strategies on historical data and optimize their performance.</h6>
<h6> Trading Execution: Identify the best-performing strategy, you can use it to inform your trading decisions in a live environment.</h6>
