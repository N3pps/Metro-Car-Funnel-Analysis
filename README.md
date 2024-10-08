# Metro-Car-Funnel-Analysis
#### Data-driven Funnel Analysis on the Customer Journey
<img src="https://github.com/user-attachments/assets/5337e307-7934-453d-9606-1558fa22890c" alt="Funnel Analysis" width="400"/>


## 🌎 Background
Metrocar's business model is based on a platform that connects riders with drivers through a mobile application. Metrocar acts as an intermediary between riders and drivers, providing a user-friendly platform to connect them and facilitate the ride-hailing process

[Executive Summary](https://doc.clickup.com/9012190783/d/h/8cjp7hz-592/b6c873e7a7f6743)

[Here](https://colab.research.google.com/drive/1HEiP4kOojeOjysy5AUcG5eqFUgBsenFy?usp=sharing) you can find the Jupyter Notebook used.

[Here](https://github.com/N3pps/Metro-Car-Funnel-Analysis/blob/main/Metro%20Car%20Presentation%20Slides.pdf) you can find the Presentation Slides

## 🔭 Project Overview:
This project focuses on analyzing the customer and rider experience of Metrocar. We aimed to identify opportunities for improvement and optimization through a funnel analysis. We used a [Jupyter Notebook](https://colab.research.google.com/drive/1HEiP4kOojeOjysy5AUcG5eqFUgBsenFy?usp=sharing) and SQLAlchemy to query data from the PostgreSQL database. For analysis and data visualization, we used Pandas, NumPy, Plotly, Seaborn, and Matplotlib  and **SQLAlchemy** to query the Data from the **PostgreSQL Database**. For analysis, and data Vizualisation we used **pandas, numpy, plotly, seaborn** and **matplotlib**.


## 🎯 Objectives                                                          
Answering the following Questions:
* Are there any significant drop-off points preventing users from completing their first ride?
  * If yes, can our Data help us reduce the biggest drop-off points?
* What steps of the Customer Journey should we research and improve?
* Are there any significant drop-off points preventing drivers from fullfilling orders?

## 🔍 Methodology                                                     
### Data Cleaning and Preparation
Our first task was extracting the raw data working on a  Jupyter Notebook hosted on Google Colab, using "SQL Alchemy" Python Library to exctract data from a PostgreSQL Database, across five key tables, generating a wide array of metrics. The main focus was on understanding the dataset using Pandas and creating a main Table to work with.

### Exploratory Data Analysis (EDA)
In this process we answered several Business related Questions like:
What is the average time of a ride from pick up to drop off?
We build some visualize our data to make it easy to understand. 

### Funnel Analysis
Next we collected the Data Necessary to build our Funnels to find out where we lose most users to complete their first ride.
For the User Table it was the following Steps:
1. App download
2. Signup
3. Ride request
4. Driver acceptance
5. Ride finished
6. at least one payment
7. Review

For the driver related "Orders fullfilled" Funnel it was the following Steps:
1. Ride request
2. Driver acceptance
3. Ride finished
4. Ride paid
5. Ride reviewed

## 💡 Key Findings                                                        

### Users lost Funnel
![image](https://github.com/user-attachments/assets/4be1a6e2-2094-41bd-900d-8475c4bbd002)
* Nearly half of the users, who have a driver accepting their request, do not proceed to complete the ride.

## 

### Orders fullfilled
![image](https://github.com/user-attachments/assets/c6fcc9b5-403c-458c-9da7-4207b1638db9)
* 35.6 % of ride requests are not accepted. 

## 📈 Recommendations                                              
### 1. Tracking cancellation source
By pinpointing these sources, we can develop targeted strategies to address and reduce cancellations, ultimately improving the overall success rate of ride completions.

### 2. Potential Survey for Cancellations
Potential questions could address aspects such as satisfaction with the app's usability. Simply adding this additional step in the cancellation process could help reduce churn by itself.

### 3. Investigating the Reason why one-third of ride requests are not accepted
This could be due to various reasons such as driver unavailability, mismatches between driver and rider locations, or system inefficiencies. We could start by surveying a select Group of our drivers who are in this group to find out about some of the Reasons they didnt accept a ride.

## 📄 Appendix

Presented by: [Anastasios Mastorakis](https://www.linkedin.com/in/anastasios-mastorakis/), [Slides](https://github.com/N3pps/Metro-Car-Funnel-Analysis/blob/main/Metro%20Car%20Presentation%20Slides.pdf)

Collaborators: [Faustina Owusu Afriyie](https://www.linkedin.com/in/faustina-owusu-afriyie-878452290/), [Felix Agyei-Sasu, PhD](https://www.linkedin.com/in/felix-agyei-sasu/)

The dataset:
"postgresql://Test:bQNxVzJL4g6u@ep<area>-noisy-flower-846766-pooler.us-east-2.aws.neon.tech/Metrocar"

[Here](https://colab.research.google.com/drive/1HEiP4kOojeOjysy5AUcG5eqFUgBsenFy?usp=sharing) you can find the Jupyter Notebook.





