# Classification and Hypothesis Testing Project

## Project Overview

The **Classification and Hypothesis Testing Project** aims to support an EdTech startup, in identifying the most promising leads who are likely to convert into paid customers. This is achieved by analyzing lead data, building a predictive model, and performing hypothesis testing to understand the factors influencing conversions. The insights from this project will help EdTech Co allocate resources effectively, streamline the lead nurturing process, and boost conversion rates.

## Context

With the recent surge in the EdTech industry, particularly due to the Covid-19 pandemic, online education has become increasingly popular. The Online Education market was projected to reach $286.62 billion by 2023, with a steady growth rate of 10.26% annually. This growth is fueled by features such as ease of access, personalized learning experiences, and transparent assessments, which make online education more attractive than traditional methods.

In this competitive landscape, EdTech Co faces the challenge of converting a high volume of leads generated through digital marketing efforts. These leads are gathered from various sources, including social media interactions, website visits, brochure downloads, and direct email inquiries. By analyzing lead behavior and characteristics, EdTech Co can identify high-potential leads and improve conversion rates.

## Objective

As a data scientist at EdTech Co, your objectives are to:

1. **Build a Predictive Model**: Identify which leads are more likely to convert into paid customers.
2. **Analyze Conversion Factors**: Determine the factors influencing lead conversion to optimize marketing and sales efforts.
3. **Develop a Lead Profile**: Create a profile for leads who are most likely to convert, enabling targeted engagement strategies.

## Data Description

The dataset contains attributes about the leads and their interactions with EdTech Co. Each attribute provides valuable information to assess the likelihood of a lead converting into a customer. Below is a description of the data columns:

### Data Dictionary

| Column                  | Description                                                                                           |
|-------------------------|-------------------------------------------------------------------------------------------------------|
| **ID**                  | Unique identifier for each lead.                                                                      |
| **age**                 | Age of the lead.                                                                                      |
| **current_occupation**  | Current occupation status of the lead (e.g., Professional, Unemployed, Student).                      |
| **first_interaction**   | Channel through which the lead first interacted with EdTech Co (e.g., Website, Mobile App).         |
| **profile_completed**   | Percentage of the profile completed on the website or mobile app (Low, Medium, High).                 |
| **website_visits**      | Number of visits the lead made to the website.                                                        |
| **time_spent_on_website** | Total time the lead spent on the website (in minutes).                                              |
| **page_views_per_visit** | Average number of pages viewed per website visit.                                                    |
| **last_activity**       | Last recorded activity with EdTech Co (e.g., Email, Phone, Website interactions).                  |
| **print_media_type1**   | Flag indicating if the lead saw EdTech Co’s ad in a Newspaper (0 = No, 1 = Yes).                    |
| **print_media_type2**   | Flag indicating if the lead saw EdTech Co’s ad in a Magazine (0 = No, 1 = Yes).                     |
| **digital_media**       | Flag indicating if the lead saw EdTech Co’s ad on digital platforms (0 = No, 1 = Yes).              |
| **educational_channels** | Flag indicating if the lead heard about EdTech Co through educational channels (e.g., forums).     |
| **referral**            | Flag indicating if the lead was referred to EdTech Co (0 = No, 1 = Yes).                            |
| **status**              | Conversion status (1 if converted to a paid customer, 0 otherwise).                                   |

## Steps Involved

1. **Data Preprocessing**: 
   - Clean and preprocess the dataset.
   - Handle missing values and encode categorical variables for model compatibility.

2. **Exploratory Data Analysis (EDA)**:
   - Analyze the distributions of different features.
   - Visualize relationships and patterns in lead behaviors to identify conversion factors.

3. **Hypothesis Testing**:
   - Test hypotheses related to lead characteristics and their likelihood of conversion.
   - Identify statistically significant factors that impact lead conversion.

4. **Model Building**:
   - Develop a classification model (e.g., Decision Tree, Random Forest, Logistic Regression) to predict lead conversion probability.
   - Evaluate model performance using metrics like accuracy, precision, recall, and F1-score.

5. **Lead Profiling**:
   - Use model insights to develop profiles of high-potential leads.
   - Identify attributes that characterize leads who are more likely to convert.

6. **Recommendations**:
   - Provide actionable insights and recommendations for optimizing lead management.
   - Suggest ways to allocate marketing and sales resources based on lead conversion probability.

## Usage

### Dependencies

- Python 3.6+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

### Instructions

1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Jupyter Notebook or Python script to load and preprocess the data, explore insights, and build the predictive model.

## Results

- **Predictive Model**: A machine learning model was developed to predict lead conversion probability with an accuracy of X%.
- **Key Conversion Factors**: Factors such as [list key factors identified from analysis, e.g., occupation, time spent on website] were found to significantly impact the likelihood of lead conversion.
- **Lead Profile**: Profiles of high-potential leads were developed to guide targeted marketing and sales efforts.

## Top Important Features
The most important features driving lead conversion for ExtraaLearn are:

1. **Website Engagement:**
    - Time Spent on Website, Page Views Per Visit, and Website Visits are top predictors. Leads who spend more time, view more pages, and visit frequently show higher engagement, indicating a stronger likelihood of conversion.
  - 
2. **First Interaction (Website):**
    - Leads whose initial contact was through the website have a higher conversion rate, suggesting that website visitors may have more intent to explore and enroll.
  
3. **Profile Completion Level:**
    - Leads with medium profile completion are more likely to convert. Encouraging profile completion could increase engagement and conversions.
  
4. **Age:**
    - Certain age groups are more likely to convert, allowing for targeted marketing strategies tailored to these demographics.
  
5. **Last Activity (Phone Activity):**
    - Leads whose last interaction was a phone call have a higher conversion likelihood, highlighting the effectiveness of personalized follow-up calls.

## Insights and Recommendations
1. **Focus on Engaging Unconverted Leads**
   - Perhaps a retargeting campaign for the unconverted leads who show interest but not converted.
  
2. **Prioritize Website Engagement**
   - Enchance the user experience and improve website usability and content quality.
  
3. **Encourage Profile Completion**
   - Highlight benefits of completing the profile to access additional resources.
  
4. **Focus Follow-ups on Phone and Website Interactions**
   - Ensure leads receives prompt follow-up.
  
5. **Continuously Monitor and Adjust Based on Data**
   - Model's feature importance indicate current key predictors, but these may change over time as user behavior shifts. 

## Future Work

- Experiment with additional machine learning models (e.g., XGBoost, Gradient Boosting).
- Implement real-time lead scoring to assist the sales team in prioritizing leads.
- Explore additional data sources, such as social media interactions, to enrich lead profiles.

---

### Note

This project provides a foundation for understanding and predicting lead conversion in the EdTech industry. By analyzing lead data and implementing machine learning, EdTech companies can improve conversion rates and optimize resource allocation for maximum impact.

---
