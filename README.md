# Employee_Attrition_Analytics

# Introduction
Research results from https://toggl.com/blog/cost-of-hiring-an-employee :

*Hiring and retaining employees are extremely complex tasks that require capital, time and skills.

*Small business owners spend 40% of their working hours on tasks that do not generate any income such as hiring.

*Companies spend 15%-20% of the employee's salary to recruit a new candidate.

Since the cost of hiring is relevantly high, to discover factors influencing employees's resignation is preoccupying the minds of business owners around the world. Understanding this, I initiated to discover several features which may play an important role in staff's turnover rate.

This project is based on a dataset that contains information about 1,400 employees and 35 features. The complete dataset is from https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset. The goal of this report is to discover the factors impact the employees attribution and develop a model to predict the result.

# Methodology
First of all, I conducted exploratory data analysis and generated visualization to extract insights. After that, Logistic Regression, Random Forest, and ANN were applied on the dataset to predict whether the employees are more likely to quit.

# EDA
The target dataset contains 1470 rows and 35 features.
![dataset](https://user-images.githubusercontent.com/64850893/107973740-9835e580-6f83-11eb-8747-999eb9f7f5e9.jpg)

Basic statistics:
![stat](https://user-images.githubusercontent.com/64850893/107973793-ac79e280-6f83-11eb-99a8-74b21a6de72a.jpg)

# Data Visualization

For the response variable "Attrition", around 200 out of 1270 employee left the company last year.

![attrition](https://user-images.githubusercontent.com/64850893/107977484-2f516c00-6f89-11eb-820a-727a27bac865.jpg)

Attrition and Age: Employees from 28 to 33 years old tend to have a higher chance to resign.

![att_age](https://user-images.githubusercontent.com/64850893/107977767-abe44a80-6f89-11eb-84ec-68bad187dd55.jpg)

Attrition and JobRole: Sales Representitives tend to leave compared to any other jobs, while the Research Directors and Managers seldom left.

![att_job](https://user-images.githubusercontent.com/64850893/107978159-552b4080-6f8a-11eb-9c83-0ac09882699f.jpg)

Attrition and MaritalStatus: Single employees tend to leave compared to married and divorced.

![att_mar](https://user-images.githubusercontent.com/64850893/107978508-e00c3b00-6f8a-11eb-8ea8-090f8f461351.jpg)

Attrition and Distance: For the exployees who live over 11 kilos from home, the probablity that they left the company was higher.

![att_dis](https://user-images.githubusercontent.com/64850893/107978686-38dbd380-6f8b-11eb-9311-5e46747af222.jpg)

Attrition and Working Years: Employees with more than 8 years of working experience tend to stay compared to the less experienced.

![att_year](https://user-images.githubusercontent.com/64850893/107979323-6412f280-6f8c-11eb-819d-e9e520ea5788.jpg)

# Data Preparation

* OneHot Encoding
* MinMax Scaling
* Train Test Split

# Modeling

* Model1 - Logistics Regression

![lr1](https://user-images.githubusercontent.com/64850893/107980441-46df2380-6f8e-11eb-8b98-f06cb0a91f9e.jpg)

![lr2](https://user-images.githubusercontent.com/64850893/107980521-6bd39680-6f8e-11eb-92fd-8482cb9c5c7a.jpg)



* Model2 - Random Forest

* Model3 - ANN

# Conclustion

# Future
