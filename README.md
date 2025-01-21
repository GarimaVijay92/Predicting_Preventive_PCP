# Title of the Project
Predicting Preventive PCP Visits

# Description
This project is done as a part of Humana-Mays Analytics Competition in September 2024. Me along with a team member participated in this and secured a place among top 50 teams out of 300+ teams across United States. 

The goal of this project is to develop a predictive model to identify Humana's Medicare Advantage LPPO (Local PPO) plan members who are unlikely to complete a preventive Primary Care Physician (PCP) visit within the current calendar year. As the LPPO plan continues to grow in market share due to its flexibility in member care choices, it is also facing a challenge with a higher proportion of unengaged members compared to the HMO plan. This lack of engagement can lead to adverse health outcomes and higher costs.

# Goals
1. Analyze member data to uncover key factors that influence engagement and preventive care utilization in the LPPO plan.
2. Create actionable insights to help Humana target unengaged members with tailored interventions, improving preventive care completion rates.
3. Enhance operational efficiency by enabling proactive member outreach based on model predictions, reducing long-term healthcare costs.

# Technologies Used
Python programming: For data preprocessing, model development, visualization and analysis.

Google Colab: For handling large dataset 

# Challenges
1. High Dimensionality: The dataset included a large number of variables (~300), which led to challenges with overfitting and model complexity. Feature selection and dimensionality reduction techniques were applied to ensure the model remained interpretable and effective.

2. Imbalanced Dataset: The dataset had a disproportionate number of members who completed preventive PCP visits compared to those who didn’t. Techniques like oversampling, undersampling, and cost-sensitive learning were utilized to address the class imbalance and improve prediction accuracy.

3. Large Dataset: With over 1.5 million rows of data, processing and training the model efficiently was a significant challenge. Optimized algorithms and computational resources were employed to ensure scalability and reduce processing time.

4. Missing or Incomplete Data: The dataset contained missing values and incomplete records, which impacted model accuracy. Data imputation strategies and feature engineering were implemented to address these gaps and minimize bias.


# Project Context
Humana’s LPPO (Local PPO) Medicare Advantage plan is experiencing growing market share due to its flexibility, allowing members greater freedom in choosing their healthcare providers. However, a significant challenge associated with the LPPO plan is the higher proportion of unengaged members compared to the HMO plan. These unengaged members result in fewer provider touchpoints, which are critical for conducting preventive health screenings, managing chronic conditions, monitoring medications, and addressing health risks, particularly for aging members.

The lack of engagement and reduced provider touchpoints can lead to lower stars ratings, which directly impact Humana's performance and result in incomplete risk documentation for LPPO members. As a consequence, Humana risks losing valuable bonus premiums, which would otherwise be reinvested into enhancing plan benefits. This cycle of disengagement and reduced performance has a downstream negative impact on member health outcomes and overall plan success.

# Project Objective
Develop a predictive model that identifies Humana LPPO Medicare Advantage plan members who are at high risk of not completing preventive PCP visits within the current calendar year. By accurately forecasting unengaged members, the model will enable targeted interventions to improve member engagement, increase provider touchpoints, and ensure timely preventive care. 

# AI Fairness 360 
To ensure fairness in the model, we incorporated the AI Fairness 360 (AIF360) toolkit, which provides a suite of algorithms designed to mitigate bias and ensure equitable outcomes for all demographic groups.

By leveraging AIF360, we aimed to reduce any potential discrimination in the model’s predictions based on sensitive attributes such as gender and race. This helped us ensure that all members, regardless of their background, are treated fairly when targeted for outreach and engagement interventions.



