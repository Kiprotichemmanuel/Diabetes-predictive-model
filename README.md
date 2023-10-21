**Next-Gen Diabetes Management: Pioneering Solutions**

**Project Overview**

This project aims to investigate and analyze various factors related to diabetes management and health outcomes. The dataset consists of several important variables related to diabetes, lifestyle choices, health conditions, and socioeconomic factors. By conducting a thorough examination of these variables, the project aims to identify potential patterns, correlations, and insights that can contribute to enhanced diabetes care and overall health improvements.

**Business Problem**
A health insurance company wants to identify individuals at risk of developing diabetes or prediabetes based on the Behavioral Risk Factor Surveillance System (BRFSS) survey data for the year 2015. The company aims to use this information to design targeted prevention and intervention programs to reduce the risk of diabetes and improve the overall health of their policyholders.

**Business Objectives**
* To improve diabetes care, the project aims to analyze the dataset and identify key factors that can lead to better diabetes outcomes and overall health for patients.
* To determine personalized treatment plans for diabetic patients based on identified patterns and correlations in the dataset.
* To develop a robust predictive model that accurately estimates the probability of individuals contracting diabetes.
* 
**Hypothesis**
* H0: Diabetes is not influenced by our feature variables
* H1: Diabetes is caused by certain feature variables
  
**Data Understanding**
Dataset used
Diabetes _ binary _ health _ indicators _ BRFSS2015.csv is a clean dataset of 253,680 survey responses to the CDC's BRFSS2015. The target variable Diabetes_binary has 2 classes. 0 is for no diabetes, and 1 is for prediabetes or diabetes. This dataset has 21 feature variables and is not balanced.

It is a csv of the dataset available on Kaggle for the year 2015 can be found on this link .

**About Columns** :

* Diabetes_binary : you have diabetes (0,1)

* HighBP : Adults who have been told they have high blood pressure by a doctor, nurse, or other health professional (0,1)

* HighChol : Have you EVER been told by a doctor, nurse or other health professional that your blood cholesterol is high? (0,1)

* CholCheck : Cholesterol check within past five years (0,1)

* BMI : Body Mass Index (BMI)

* Smoker : Have you smoked at least 100 cigarettes in your entire life? [Note: 5 packs = 100 cigarettes] (0,1)

* Stroke : (Ever told) you had a stroke. (0,1)

* HeartDiseaseorAttack : Respondents that have ever reported having coronary heart disease (CHD) or myocardial infarction (MI) (0,1)

* PhysActivity : Adults who reported doing physical activity or exercise during the past 30 days other than their regular job (0,1)

* Fruits : Consume Fruit 1 or more times per day (0,1)

* Veggies : Consume Vegetables 1 or more times per day (0,1)

* HvyAlcoholConsump : Heavy drinkers (adult men having more than 14 drinks per week and adult women having more than 7 drinks per week)(0,1)

* AnyHealthcare : Do you have any kind of health care coverage, including health insurance, prepaid plans such as HMOs, or government plans? (0,1)

* NoDocbcCost : Was there a time in the past 12 months when you needed to see a doctor but could not because of cost? (0,1)

* GenHlth : Would you say that in general your health is: rate (1 ~ 5)

* MentHlth : Now thinking about your mental health, which includes stress, depression, and problems with emotions, for how many days during the past 30 days was your mental health not good? (0 ~ 30)

* PhysHlth : Now thinking about your physical health, which includes physical illness and injury, for how many days during the past 30 days was your physical health not good? (0 ~ 30)

* DiffWalk : Do you have serious difficulty walking or climbing stairs? (0,1)

* Sex : Indicate sex of respondent (0,1) (Female or Male)

* Age : Fourteen-level age category (1 ~ 14)

* Education : What is the highest grade or year of school you completed? (1 ~ 6)

* Income : Is your annual household income from all sources: (If respondent refuses at any income level, code "Refused.") (1 ~ 8)

  **Inferences from loading dataset**
  
* The majority of people in the dataset do not have diabetes, high blood pressure, high cholesterol, and have received a cholesterol check.

* There is a large number of people with BMI values ranging between 25 and 30, which indicates a prevalence of overweight individuals.

* The number of people engaging in physical activity is higher than those who don't.

* A considerable proportion of people consume fruits and vegetables regularly.

* A significant number of people do not consume heavy alcohol.

* The majority of individuals have access to healthcare.

* The data includes a diverse age range, with the highest count in the 9-11 age group.

* There is a broad distribution of education levels, with the majority having completed up to grade 6.

* Income levels show various values, with the highest count in the 8 category.

  **Exploratory Data Analysis**

* **Univariate Analysis**

 * ![image](https://github.com/Kiprotichemmanuel/Diabetes-predictive-model/assets/126081203/12b9e21d-0a25-472f-a771-e965791b5ccc)

* **Bivariate Analysis**

we are checked for the relationship between various features and our target variable

![image](https://github.com/Kiprotichemmanuel/Diabetes-predictive-model/assets/126081203/8ed156cd-7f8b-4b87-b730-0a156b1d5e9d)

**MODELING**

* **XGBoost**

* ![image](https://github.com/Kiprotichemmanuel/Diabetes-predictive-model/assets/126081203/e2d53686-d870-4b6d-93a3-5ca5eefb788d)

  
