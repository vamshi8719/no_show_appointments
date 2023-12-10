# Investigate a No-show Appointment Dataset
This is a Udacity nano degree project to investigate a medical appointments dataset from Brazil. The goal is to predict whether a patient will show up to their scheduled appointment.  

# Software and Packages
Jupyter Notebook  
Pandas  
Numpy  
Matplotlib  

# What I did

Data Wrangling  
Exploratory Data Analysis (EDA)  

# Research Questions

Analysis was performed on several characteristics and three of them were identified to predict whether a patient will show up for appointment.  

**Research question 1:** How is patient age related to their chance of showing up for the appointment?  

<img width="407" alt="image" src="https://github.com/vamshi8719/no_show_appointments/assets/56979563/5e6e6a9a-19c9-4877-b7b1-1ed2ac4f1d8a">  

<img width="410" alt="image" src="https://github.com/vamshi8719/no_show_appointments/assets/56979563/ecc6f520-9bb9-4fa9-94ba-09c63422de44">  

Number of appointments where patients do not show up for appointment reduces with age. The same was observed across both genders. The noshow data on male is more skewed to the right.  
 

**Research question 2:** What is the relation between sms received for an appointment to patient actually showing up for the appointment?  

<img width="660" alt="image" src="https://github.com/vamshi8719/no_show_appointments/assets/56979563/062371ef-8fc5-4bb1-9e5c-0bac011eaae5">  


**Research question 3:** Are patients more likely to not show up for an appointment on a certain weekday?  

<img width="660" alt="image" src="https://github.com/vamshi8719/no_show_appointments/assets/56979563/91d5ee93-ba8e-4ce7-afec-9b332ef40163">  

# Limitations

The dataset does not have the same number of appointments for both genders.  
Although patient with 4 disabilities and that received an sms always missed an appointment, but it represents only 1 record in over 100,000 records. For this reason the data in column handcap has been changed to whether or not a patient has a disability.  
Some of the observations are not large enough to make a recommendation.  







