# Linear Regression: An E-Commerce Predictive Analysis
This is a Repository illustrating Linear Regression on an E-Commerce Data Set

# About the DataSet
The dataset contains information about customers who purchase clothes online from a store that provides in-store style and clothing advice sessions. The customers visit the store for personalized sessions with a personal stylist and then have the option to place orders using either a mobile app or the website.

To help the company make an informed decision on where to focus their efforts, the dataset includes various variables that capture customer behavior and preferences. Some key factors that are included in the dataset are:

- **Email Address**: The unique email address associated with each customer.
- **Avatar**: The customer's chosen avatar or profile picture.
- **Avg. Session Length**: The average duration of the in-store style and clothing advice sessions attended by customers.
- **Time on App**: The amount of time (in minutes) spent by customers on the mobile app.
- **Time on Website**: The amount of time (in minutes) spent by customers on the website.
- **Length of Membership**: The number of years the customer has been a member of the store.
- **Yearly Amount Spent**: The total amount of money (in currency) spent by the customer on purchases annually.

### Source
The data was sourced from Kaggle. Here is the [link](https://www.kaggle.com/datasets/kolawale/focusing-on-mobile-app-or-website?resource=download)



# Software Used

<div class="images">
<img src="xlstat_logo.png" alt="" width="20%" height="100px" class="alignleft size-full">
<img src="python_logo.png" alt="" width="20%" height="100px" class="alignleft size-full">
<img src="Scikitlearn_logo.png" alt="" width="20%" height="100px" class="alignleft size-full">
<img src="streamlit_logo.png" alt="" width="20%" height="100px" class="alignleft size-full">
<img src="Vscode_logo.jpg" alt="" width="15%" height="100px" class="alignleft size-full">
</div>


**XLSTAT**: as a statistical analysis software was used for data manipulation, exploration, and running linear regression models on the dataset.

**Python**: Python was used for tasks such as data preprocessing, model building, and evaluation, including linear regression, using libraries like scikit-learn.

**Scikit-learn**: as a popular machine learning library in Python, provided various tools and algorithms for data analysis, including linear regression. It was utilized to build, train, and evaluate linear regression models on the dataset.

**Streamlit**: Streamlit is a Python library used for creating interactive web applications. In this project, it was employed to build a user-friendly interface for running and visualizing the linear regression model results.

**Visual Studio Code**: Visual Studio Code is an integrated development environment (IDE) used for coding. It was utilized as the primary coding environment for writing and debugging Python code for data analysis, including the linear regression implementation.

**Joblib**: Joblib is a Python library used for serialization and deserialization of objects. It was used to save and load the trained linear regression model for later use in the application.

**NumPy**: NumPy is a fundamental library for numerical computing in Python. It provides support for large, multi-dimensional arrays and various mathematical functions. It would was used for numerical operations and manipulations required in the linear regression analysis.

**Seaborn**: Seaborn is a data visualization library in Python. It provides a high-level interface for creating visually appealing and informative statistical graphics. It was used to visualize the dataset, explore relationships, and display the results of the linear regression model.

# Modelling
The modeling process in the project involved building a linear regression model to predict the yearly amount spent by customers. Python and scikit-learn were used for data preprocessing, splitting the dataset, and training the model. Additional tools like NumPy and seaborn supported data manipulation and visualization tasks, respectively. The aim was to create a predictive model that could estimate customer spending based on various features.

Joblib was instrumental in saving and loading the trained linear regression model, allowing for easy persistence and reuse. With Joblib, the model can be stored as a file, eliminating the need for retraining each time the application is deployed. On the other hand, Streamlit simplifies the development of an interactive web interface for the prediction model. It enabled us to quickly create a user-friendly application that takes user inputs, such as Session length and Time on Platform, and utilizes the linear regression model to make predictions on customer spending. Together, Joblib and Streamlit provide the necessary tools for efficient deployment of the linear regression model in a web application, facilitating seamless prediction of customer spending.

# Summary of Key Findings
