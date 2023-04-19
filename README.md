# Bellabeat_Case_Study
Case study on Bellabeat - a company focused on empowering women's health through smart technology. The repository contains data cleaning, data analysis, and data visualization of various data sets related to user activity, sleep, steps, and weight. 


# Introduction 
Bellabeat is a high-tech company founded in 2013 by Urška Sršen and Sando Mur, with a mission to empower women with knowledge about their own health and habits. The company manufactures health-focused smart products that collect data on activity, sleep, stress, and reproductive health. By using beautifully designed technology, Bellabeat inspires and informs women around the world to take control of their well-being. In just a few years, Bellabeat has grown rapidly and positioned itself as a tech-driven wellness company for women, with offices around the world and a growing number of online retailers selling their products. The company invests heavily in digital marketing, using Google Search, Facebook, Instagram, Twitter, Youtube, and the Google Display Network to engage with consumers. However, Bellabeat believes that an analysis of their available consumer data could reveal even more opportunities for growth. To this end, Bellabeat has asked their marketing analytics team to analyze smart device usage data and provide high-level recommendations for how these trends can inform their marketing strategy. This case study will focus on one Bellabeat product and explore the insights gained from analyzing the data.

### Objective:
The objective of this case study is to use data analytics to analyze the usage patterns of Bellabeat's smart device and provide high-level recommendations for improving their marketing strategy. This will involve gathering and processing data from various sources, analyzing the data to identify trends and insights, and sharing the findings with Bellabeat's stakeholders. By taking action on the recommendations, Bellabeat can continue to grow and innovate in the wellness technology industry

## 1. Ask

#### About Stakeholders
- Urška Sršen: Bellabeat’s cofounder and Chief Creative Officer
- Sando Mur: Mathematician and Bellabeat’s cofounder; key member of the Bellabeat executive team

### Business Task
- Our task is to analyze the usage data of non-Bellabeat smart devices in order to gain insights into how consumers use these devices. The objective is to select one Bellabeat product and apply these insights to enhance the marketing strategy for that particular product.

#### Questions that will guide our analysis
1. What are some trends in smart device usage?
2. How could these trends apply to Bellabeat customers?
3. How could these trends help influence Bellabeat marketing strategy?

## 2. Prepare
#### The data 
Sršen encourages us to use public data that explores smart device users’ daily habits. She points us to a specific data set:

● [[FitBit Fitness Tracker Data]](https://www.kaggle.com/datasets/arashnic/fitbit) (CC0: Public Domain, dataset made available through Mobius): 

This contains personal fitness tracker from thirty fitbit users. Thirty eligible Fitbit users consented to the submission of
personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. It includes
information about daily activity, steps, and heart rate that can be used to explore users’ habits.

### Data Overview
#### Who
- Collected by Amazon mechanical Turk
- Sample size: 30 people

#### What 
1. Physical Activity
    - Activity
    - Intensity
    - steps
2. Physiology 
    - Calories
    - Heartrate
3. Monitoring
    - Sleep
    - Weight
    
#### When 
- Collected over 31 days in 2016
- 03/12/2016 - 05/12/2016

#### Limitations
- Small sample size of only 30 participants
- Not recent as data was collected in 2016. 

## 3. Process
- Processed daily_activity, daily_steps, and weight csv data in Google Sheets
- Checked for duplicates and missing values and cleaned the data
- Created pivot tables to select only the necessary data for analysis
- Used pivot tables to create line and bar charts for visual analysis
- Line charts were used to analyze trends in daily activity
- Bar charts were used to analyze trends in daily activity, steps, and weight

## 4. Analyze

#### Daily Activity
In the Daily Activity CSV, a line graph was created to show the trend in daily VeryActiveMinutes. A trendline was added to the graph, which shows a downward trend. This indicates that the amount of VeryActiveMinutes decreased from the beginning of the data collection period until the last day.
![image.png](attachment:565f9a8f-ade3-4821-9c32-16d80472c7c5.png)

After analyzing the data in the daily_activity CSV file, I created a bar graph comparing the average sedentary minutes to the average active minutes.
The average sedentary minutes per day was found to be 749, while the average daily active minutes was 223. The average daily active minutes was found by combining the data from the very, moderate, and light active minutes.
By comparing these two values, I found that the average sedentary minutes were 334.65% more than the average active minutes per day.
![image.png](attachment:86586c8c-04a0-426c-944f-6688049f86cf.png)

#### Steps
In the next analysis, I focused on the step count data. After cleaning and processing the data, I created a pivot table to calculate the average daily steps taken for each week. The results showed that the steps stayed mostly consistent over the five-week period. Specifically:

- The highest average daily steps occurred in week 18, with an average of 8550 steps per day.
- The lowest average daily steps occurred in week 20, with an average of 8086 steps per day. This value is close to 500 steps less than the highest week.
- The average daily steps for all five weeks combined was 8290.
- The participants do not meet the recommended 10,000 daily step count

These findings suggest that the users in the dataset maintained a relatively consistent level of physical activity over the five-week period.
![image.png](attachment:cb673928-2aa3-4d4a-b352-6c1c36aab773.png)

#### Weight
The weight data showed that out of all 30 participants, only 8 chose to log their weight.
- The average weight of the participants who logged their weight was 171 lbs.
- The average BMI of the participants who logged their weight was 28.
- Based on the BMI values, it can be inferred that most of the participants who logged their weight are overweight.
- The range of weight for the participants who logged their weight is from 115 lbs to 294 lbs.
- It's worth noting that the one participant who weighs 294 lbs heavily increases the average BMI and weight values.
![image.png](attachment:d2ce3533-7ffc-4838-af60-6f6a0422c5e5.png)
## 5. Share
[BellaBeat .pdf](https://github.com/LunaDGD/Bellabeat_Case_Study/files/11268190/BellaBeat.pdf)

## 6. Act

Based on the analysis conducted, it is recommended that Bellabeat implement the following strategies to better cater to their target audience:

- Increase promotion of active minutes: As the analysis showed, there is a significant difference between the average sedentary and active minutes. Bellabeat can target customers by promoting and incentivizing them to increase their active minutes. This could be done through gamification, rewards, or personalized coaching.
- Obtain more data: To ensure accurate analysis, it is recommended that Bellabeat collects more data on the weight and BMI of its customers. Only 8 out of 30 participants logged their weight, which is a small sample size. By increasing the number of participants who log their weight, Bellabeat can gain a more accurate understanding of the weight and BMI trends among its customers.
Conduct surveys: Bellabeat should conduct surveys to gain a deeper understanding of the reasons behind the downward trend in very active minutes. The company can use the survey results to identify the factors that are discouraging customers from being active and adjust its products and marketing strategy accordingly. Surveys can also be used to gain insights into the types of products and features that customers are looking for, which can inform the development of new products.
- Consider implementing a feature in the wearable technology that vibrates to remind users to be more active after a prolonged period of sedentary activity. This could help increase the daily active minutes and promote a healthier lifestyle.
Based on the analysis of the step count, Bellabeat can focus on creating new features that encourage users to increase their step count. For instance, gamifying the experience with challenges, providing personalized recommendations to reach daily goals, or integrating with social media to create a sense of community and friendly competition. These features could help motivate users to be more active and engaged with the product.
