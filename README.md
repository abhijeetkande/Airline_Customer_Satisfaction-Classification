# Airline_Customer_Satisfaction-Classification
This project aims to classify airline customer satisfaction based on various features that influence the customer experience. The dataset contains several attributes related to customer behavior and service quality, and the goal is to predict whether a customer is satisfied or not.


**Table of Contents:**


 - Project


 - Overview


 - Problem Statement


 - Data Description


 - Objective


 - Features


 - Target


 - Data Preprocessing


 - Modeling

   
 - Technologies Used

---

**Project Overview:**


This project focuses on predicting airline customer satisfaction based on their experiences with various services. The classification problem aims to classify customers as either satisfied or dissatisfied based on the attributes provided in the dataset. The project involves data preprocessing, exploratory data analysis, model selection, and performance evaluation.

----

**Problem Statement:**


Airlines and aviation companies need to continuously improve their customer service to retain passengers and ensure customer loyalty. However, predicting customer satisfaction can be complex due to the variety of factors that influence a customer's experience. These factors include but are not limited to, flight distance, seat comfort, service quality, delays, and even factors like the convenience of online check-in.

The problem at hand is to classify airline passengers into two categories: satisfied or dissatisfied, based on a variety of features related to their flight experience. This classification can help airlines to identify and address the areas most affecting customer satisfaction, enabling them to improve service offerings and tailor future experiences.

---


**Data Description:**


The dataset includes several columns representing customer feedback on different aspects of their flight experience. Here’s an overview of the dataset:


- **Gender:** The gender of the customer (Male/Female).


- **Customer Type:** Whether the customer is a Loyal Customer or a Disloyal Customer.


- **Age:** The age of the customer.


- **Type of Travel:** Whether the customer is traveling for Business or Personal.


- **Class:** The class of travel, which can be Economy, Economy Plus, or Business.


- **Flight Distance:** The distance of the flight in miles.


- **Seat comfort:** Rating for seat comfort (scale from 1 to 5).


- **Departure/Arrival time convenient:** Whether the departure/arrival times were convenient (Yes/No).


- **Convenient online check-in:** Rating for the convenience of the online check-in process (scale from 1 to 5).


- **Food and drink:** Rating for food and drink service (scale from 1 to 5).


- **Online support:** Rating for the online support service (scale from 1 to 5).


- **Ease of Online booking:** Rating for the ease of online booking (scale from 1 to 5).


- **On-board service:** Rating for the on-board service (scale from 1 to 5).


- **Leg room service:** Rating for legroom service (scale from 1 to 5).


- **Baggage handling:** Rating for baggage handling (scale from 1 to 5).


- **Checkin service:** Rating for check-in service (scale from 1 to 5).


- **Cleanliness:** Rating for cleanliness (scale from 1 to 5).


- **Online boarding:** Rating for online boarding (scale from 1 to 5).


- **Departure Delay in Minutes:** The number of minutes of departure delay.


- **Arrival Delay in Minutes:** The number of minutes of arrival delay.

---


**Objective:**


The goal of this project is to build a machine learning model that classifies whether a customer is **satisfied** or **dissatisfied** with their flight experience, using the various features from the dataset

---

**Features:**


- **Gender:** The gender of the customer. (Categorical)


- **Customer Type:** The loyalty status of the customer. (Categorical)


- **Age:** The age of the customer. (Numerical)


- **Type of Travel:** The purpose of the trip. (Categorical)


- **Class:** Travel class chosen by the customer. (Categorical)


- **Flight Distance:** Distance traveled in miles. (Numerical)


- **Seat comfort, Departure/Arrival time convenient, Convenient online check-in, Food and drink, Online support, Ease of Online booking, On-board service, Leg room service, Baggage 
handling, Checkin service, Cleanliness, Online boarding: Customer feedback on specific services (Ratings: 1-5)
Departure Delay in Minutes:** Delay in departure time. (Numerical)


- **Arrival Delay in Minutes:** Delay in arrival time. (Numerical)

---

**Target:**


- **Satisfaction:** The target variable which indicates whether the customer is satisfied or dissatisfied. (Binary)

---

**Data Preprocessing:**


In the preprocessing stage, the following steps were performed:


- **Missing Value Handling:** Any missing or null values were handled either by filling with the mean or mode (depending on the feature) or removing rows with significant missing data.


- **Encoding Categorical Features:** Categorical variables like 'Gender', 'Customer Type', and 'Type of Travel' were encoded using one-hot encoding or label encoding.


- **Feature Scaling:** Numerical features like 'Age', 'Flight Distance', 'Departure Delay in Minutes', and 'Arrival Delay in Minutes' were scaled using standardization or normalization.


- **Outlier Detection:** Outliers in numerical features were detected and removed if necessary.


- **Splitting Data:** The dataset was split into training and testing sets, usually in an 75-25 ratio.


---


**Modeling:**

The following machine learning model were applied to predict customer satisfaction:

- **Logistic Regression**

---

**Technologies Used**


**Programming Language:** Python


**Libraries:**

- Pandas


- NumPy


- Matplotlib


- Seaborn


- Jupyter Notebook


**How to Run the Code**


**Clone the repository to your local machine:**


git clone https://github.com/abhijeetkande/airline-customer-satisfaction.git


**Navigate to the project directory:**


cd Airline_Customer_Satisfaction-Classification
