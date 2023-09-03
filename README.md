# Determining-the-simultaneity-factor-of-electricity-consumption-distribution-level
In this repository, we use deep learning approaches to detect the simultaneity factor in electricity consumption distribution levels in Iran. The code for this analysis can be found in the 'article-features.ipynb' file. Please note that the dataset used contains confidential information about electricity consumption in Tehran and cannot be shared due to privacy concerns.
<br>
Determining electricity consumption simultaneity at the distribution level using machine learning is a complex and valuable task in the field of energy management and distribution. Simultaneity refers to the correlation or synchronization of electricity consumption patterns among multiple consumers within a distribution network. Understanding simultaneity can help utilities and grid operators optimize resource allocation, plan for peak demand, and improve overall grid efficiency.

## our high-level approach to determining electricity consumption simultaneity using machine learning:

1. **Data Collection**:
   - Dataset was provided by a smart-home company in Tehran. This data includes timestamps, consumption values. We also took into provided other relevant features such as weather data, holidays, and customer demographics.

2. **Data Preprocessing**:
   - We cleaned and preprocessed the data by handling missing values, outliers, and noise.
   - Then we normalized the data to ensure consistent input for the model.

3. **Feature Engineering**:
   - Next, we extracted relevant features that can capture the factors affecting electricity consumption simultaneity, such as time of day, day of the week, seasonality, and any external variables like temperature.

4. **Target Variable**:
   - Then, defined the target variable that quantifies simultaneity..

5. **Model Selection**:
   - We tested various ML algorithms(Time-series forecasting models, clustering algorithms, neural networks, etc) for the task.

6. **Training**:
   - Splited the data into training and validation sets.
   - Trained the machine learning model on the training data, using the defined target variable and relevant features.

7. **Evaluation**:
   - Assessed the model's performance.
