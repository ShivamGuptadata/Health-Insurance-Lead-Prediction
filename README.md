# **Health-Insurance-Lead-Prediction-** Job-A-Thon Project

# Job-A-Thon - Analytics Vidhya, Health Insurance

![](https://github.com/ShivamGuptadata/Health-Insurance-Lead-Prediction/blob/main/extra/HMI.jpg)

# Project Methodology

FinMan is a financial services company that provides various financial services like loan, investment funds, insurance etc. to its customers. FinMan wishes to cross-sell health insurance to the existing customers who may or may not hold insurance policies with the company. The company recommends health insurance to its customers based on their profile once these customers land on the website. Customers might browse the recommended health insurance policy and consequently fill up a form to apply. When these customers fill-up the form, their Response towards the policy is considered positive and they are classified as a lead.

# Objective Of The Project
Now the company needs your help in building a model to predict whether the person will be interested in their proposed Health plan/policy given the information about:

1 Demographics (city, age, region etc.)

2 Information regarding holding policies of the customer

3 Recommended Policy Information

# Related Variable
1. **ID** - Unique id.
2. **City_Code** - Code for the city of users.
3. **Region_Code** - Code for the region of the users.
4. **Accomodation_Type** - Customer owns/rents the house.
5. **Reco_Insurance_Type** - Joint or individual type for the recommended insurance.
6. **Upper_Age** - Maximum age of the customer.
7. **Lower_Age** - Minimum age of the customer.
8. **Is_Spouse** - If the customer is married or not.
9. **Health Indicator** - Encoded values for health of the customer.
10. **Holding_Policy_Duration** - Duration in year of holding policy.
11. **Holding_Policy_Type** - Type of holding policy.
12. **Reco_Policy_Cat** - Encoded values of recommended health insurance.
13. **Reco_Policy_Premium** - Annual premium(INR) for the recommended health insurance.

# Exploratory Data Analysis
I explored how our features are distributed, how they work together. For more you can look at my EDA part, there are a lot of graphs, which is interesting and helpful. They helped us to understand how our data works. Below you can see most important graphs

![](https://github.com/ShivamGuptadata/Health-Insurance-Lead-Prediction/blob/main/extra/pic1.png)

**Maximum number of customers are coming from C1 city, So the company opened a new branch in the city C1 to attract more and more customers.**

![](https://github.com/ShivamGuptadata/Health-Insurance-Lead-Prediction/blob/main/extra/pic2.png)

**Insurance companies should be focused on Unmarried customers such as students, bachelor's and young generation.**

![](https://github.com/ShivamGuptadata/Health-Insurance-Lead-Prediction/blob/main/extra/pic3.png)

**Plotting Graph to see who is responding in the Insurance while they have Rent/Own house.**

![](https://github.com/ShivamGuptadata/Health-Insurance-Lead-Prediction/blob/main/extra/pic4.png)

**Plotting Graph between Number of customers| upper and Lower age of the customers.**

![](https://github.com/ShivamGuptadata/Health-Insurance-Lead-Prediction/blob/main/extra/pic5.png)

**Plotting Graph between Number of customers| Combined upper and Lower age of the customers. By the distribution plot**

# Some Pie Chart which is interesting and helpful. They helped us to understand the data.

![](https://github.com/ShivamGuptadata/Health-Insurance-Lead-Prediction/blob/main/extra/pic6.png)

![](https://github.com/ShivamGuptadata/Health-Insurance-Lead-Prediction/blob/main/extra/pic7.png)

![](https://github.com/ShivamGuptadata/Health-Insurance-Lead-Prediction/blob/main/extra/pic8.png)

![](https://github.com/ShivamGuptadata/Health-Insurance-Lead-Prediction/blob/main/extra/pic10.png)

![](https://github.com/ShivamGuptadata/Health-Insurance-Lead-Prediction/blob/main/extra/pic11.png)

![](https://github.com/ShivamGuptadata/Health-Insurance-Lead-Prediction/blob/main/extra/pic12.png)

![](https://github.com/ShivamGuptadata/Health-Insurance-Lead-Prediction/blob/main/extra/pic13.png)

![](https://github.com/ShivamGuptadata/Health-Insurance-Lead-Prediction/blob/main/extra/pic14.png)

![](https://github.com/ShivamGuptadata/Health-Insurance-Lead-Prediction/blob/main/extra/pic15.png)

# This is the Group data of Customer Acq(Level of valuable customer) and Upper and Lower age  group customers. 
1. 
![](https://github.com/ShivamGuptadata/Health-Insurance-Lead-Prediction/blob/main/extra/pic17.png)

2. 
![](https://github.com/ShivamGuptadata/Health-Insurance-Lead-Prediction/blob/main/extra/pic18.png)

# Scikit-learn Modeling

XGBOOST using XGBClassifier was performed.

# Model Validation

![](https://github.com/ShivamGuptadata/Health-Insurance-Lead-Prediction/blob/main/extra/pic19.png)

# Configuration Matrix

![](https://github.com/ShivamGuptadata/Health-Insurance-Lead-Prediction/blob/main/extra/pic16.png)

**Complete Report of train and test data set**

![](https://github.com/ShivamGuptadata/Health-Insurance-Lead-Prediction/blob/main/extra/pic20.png)

