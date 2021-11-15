# AI / ML Project: BMI Assessment 🏋️

<p align="center"><img src="https://user-images.githubusercontent.com/54996245/141758659-95fbcedc-ecb2-4213-859c-765541a3ef3f.jpg" style="width: 1000px;"/></p>


### Description:

A simple yet challenging project, to estimate the BMI based on the Gender, Height & Weight.
The complexity arises due the fact that dataset has less samples, & is highly imbalanced.
Can you overcome these obstacles & build a good predictive model to classify them?

**This data frame contains the following columns:**

* Gender : Male / Female

* Height : Number (cm)

* Weight : Number (Kg)

* Index :
0 - Extremely Weak
1 - Weak
2 - Normal
3 - Overweight
4 - Obesity
5 - Extreme Obesity

**Source:**

Kaggle - 
https://www.kaggle.com/yersever/500-person-gender-height-weight-bodymassindex

### Objective:
- Understand the Dataset & cleanup (if required).
- Build classification models to predict the various categories of BMI.
- Compare the evaluation metrics of vaious classification algorithms.

### The Project is divided into the following steps:
1. Data Exploration
2. Exploratory Data Analysis
3. Data Preprocessing
4. Feature Selection/Extraction
5. Feature Scaling
6. Predictive Modeling
7. Project Outcomes & Conclusions

### Some Visuals of the Project:

**1. Target Variable Distribution**
<p align="left"><img src="https://user-images.githubusercontent.com/54996245/141759098-056607e4-8f0d-40e9-8bb4-4c006079c782.png" /></p>

**2. Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/141759248-04c88851-7edc-46c6-8ae4-3c5498ef7061.png)
![image](https://user-images.githubusercontent.com/54996245/141759303-b614aa1f-4923-437b-b927-06e795c4b4ae.png)
![image](https://user-images.githubusercontent.com/54996245/141759315-c15fd9a9-81fa-4901-b6c4-65245379491d.png)

**3. Relationship between the Feature-set**

![image](https://user-images.githubusercontent.com/54996245/140968656-574e4edc-3f4c-4c3a-9359-07bde41d538a.png)

**4. Data Retention after preforming preprocessing step**

![image](https://user-images.githubusercontent.com/54996245/140968701-7b426b4b-9740-4398-a3c0-0e5ae190cc8e.png)

**5. Correlation plot for features**

![image](https://user-images.githubusercontent.com/54996245/140968731-2d37bde1-3235-4a07-813d-1313339e481c.png)

**6. ROC Plots**

![image](https://user-images.githubusercontent.com/54996245/140968858-ac6271bb-f3a6-4a07-a353-6529eea56b2b.png)


**5. ML Algorithm's Scores for the Iris Dataset**
![image](https://user-images.githubusercontent.com/54996245/140968943-d4051d54-2b91-4b59-921f-0629c925a86d.png)
![image](https://user-images.githubusercontent.com/54996245/140968960-fb10b8e0-1787-46be-bf4b-af1d8bbb6418.png)


### Here are some of the key outcomes of the project:
- The Dataset was quiet small totally just 768 samples & after preprocessing 17.2% of the datasamples were dropped. 
- The diabetic samples were 30% more than non-diabetic ones, hence SMOTE Technique was applied on the data to  balance the classes, adding 11.8% more samples to the dataset.
- Visualising the distribution of data & their relationships, helped us to get some insights on the class seperability.
- Feature selection or feature extracting was not exercised, as there were only 8 features, which overall contributed towards the right prediction.
- Testing multiple algorithms with default hyperparamters gave us some understanding for various models performance on this specific dataset.
- Random Forest perform the best on the current dataset, followed by Support Vector Machines & Boosting Algorithms
- Yet it wise to also consider simpler models as they are more generalisable & take lesser training time.
