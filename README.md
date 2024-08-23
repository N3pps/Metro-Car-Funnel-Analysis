# Metro-Car-Funnel-Analysis
#### Data-driven Funnel Analysis on the Customer Journey
The dataset:
"postgresql://Test:bQNxVzJL4g6u@ep<area>-noisy-flower-846766-pooler.us-east-2.aws.neon.tech/Metrocar"

[Executive Summary](https://doc.clickup.com/9012190783/d/h/8cjp7hz-592/b6c873e7a7f6743)

[Here](https://colab.research.google.com/drive/1rmN6AVyNwf-so1Y2CaxPQPtrdfQoV8K0?usp=sharing) you can find the Jupyter Notebook used.

## 🎯 Objectives                                                          
Answering the following Questions:
* Are there any significant drop-off points preventing users from completing their first ride?
  * If yes, can our Data help us reduce the biggest drop-off points?
* What steps of the Customer Journey should we research and improve? 

## 🔍 Methodology                                                     
Our first task was extracting the raw data working on a  Jupyter Notebook hosted on Google Colab, using "SQL Alchemy" Python Library to exctract data from a PostgreSQL Database, across five key tables, generating a wide array of metrics. The data was then further processed and analyzed using several other Python Librarys. To classify customers into distinct groups we created a Users lost and Orders fullfilled Funnel. 


## 💡 Key Findings                                                        

### Users lost Funnel
![image](https://github.com/user-attachments/assets/4be1a6e2-2094-41bd-900d-8475c4bbd002)


## 

### Orders fullfilled
![image](https://github.com/user-attachments/assets/c6fcc9b5-403c-458c-9da7-4207b1638db9)

<br>&nbsp;<br>

## 📈 Recommendations                                              
### 1. Implementation of a tailored rewards program
To enhance customer loyalty and maximize the effectiveness of our marketing efforts, we recommend the implementation of a tailored rewards program based on the insights gained from the Customer Segmentation Analysis. By aligning rewards with the specific preferences and behaviors of our identified customer segments, we can create more personalized and appealing incentives that drive engagement and repeat business.

### 2. A/B testing
Additionally, to ensure the rewards program delivers optimal results, we propose conducting A/B testing during the rollout phase. This will allow us to evaluate the effectiveness of different perks and promotional strategies in real-time, providing actionable data to fine-tune the program. By continuously monitoring customer responses, we can adapt and improve the rewards offering, ultimately leading to higher satisfaction and loyalty.

## 📄 Appendix
[Here](https://colab.research.google.com/drive/1rmN6AVyNwf-so1Y2CaxPQPtrdfQoV8K0?usp=sharing) you can find the Jupyter Notebook.
Decision Tree used in the Segmentation:

![image](https://github.com/user-attachments/assets/1681af00-9ef3-4673-9a3d-6a2d1c1b868b)



