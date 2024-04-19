# NTU SC1015 Data Science Mini Project Group 8
---

## About
---

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on the [Titanic Dataset](https://kaggle.com/competitions/titanic) from Kaggle.

## Introduction
---

The RMS Titanic was a British luxury passenger as well as mail carrying ocean liner. Before the disaster, the RMS Titanic was deemed "unsinkable" However, on 15 April 1912, during its voyage from Southhampton, England to New York City, United States, it crashed into an iceberg at the North Atlantic Ocean and as a result sank. Tragically, about 1,500 of the estimated 2,224 passengers and crew aboard perished as the ship was not equipped with enough lifeboats for everyone, triggering the deadliest sinking of a single ship during that period. 

The Titanic dataset from Kaggle consists of some information of 892 passangers. 

![alt text](https://www.worldhistory.org/img/r/p/1500x1500/14047.png.webp?v=1706789164 "RMS Titanic")

## Dataset Attributes
---

| **Attributes** | **Definition** | **Key** |
|----------------|----------------|---------|
| **survival**       | Whether the passenger survived | 0 = No, 1 = Yes |
| **pclass** | Ticket class | 1 = 1st, 2 = 2nd, 3 = 3rd |
| **sex** | Gender of the passenger | male, female |
| **Age** | Age in years | |
| **sibsp** | number of siblings/spouses aboard the Titanic | |
| **parch** | number of parents/children aboard the Titanic | |
| **ticket** | Ticket number | |
| **cabin** | Cabin number | |
| **embarked** | Port of Emabarkation | C = Cherbourg, Q = Queenstown, S = Southhampton | |

**Features Notes**

**age:** Age is fractional if less than 1. If the age is estimated, it is in the form of xx.5  <br/><br/>

**sibsp:** The dataset defines family relations in this way,

Sibling = brother, sister, stepbrother, stepsister

Spouse = husband, wife (mistresses and fiancés were ignored)  <br/><br/>


**parch:** The dataset defines family relations in this way,

Parent = mother, father

Child = daughter, son, stepdaughter, stepson

Some children travelled only with a nanny, therefore `parch = 0` for them.

---

## Problem Definition
---

* Which features is able to predict the survivability of the passengers onbaord the Titanic.   
* Which machine learning models will be able to give a better accuracy to predict the survivability of the passengers onboard the Titanic. 

## Models Used
---

1. Random Forest Classifier   
2. Decision Tree Classifier 

## Conclusion
---

* Key features found: Sex_female, Sex_male, Pclass.
* Gender likely affects survivability due to evacuation policies prioritizing women and children.
* Ticket class played a significant role, possibly due to proximity to evacuation points.
* Both Decision Tree and Random Forest models performed similarly, with Decision Tree slightly better.
* No overfitting detected in either model.
* Performance could potentially be improved with dataset refinements.
* Upsampling and feature removal did not significantly change model performance.
* Consideration of model configurations and hyperparameters may also impact performance. 

## What did we learn from this project?
---

1. Random Forest Classifier from sklearn 
2. Concepts about Precision, Recall and F1 Score 
3. Handling imbalanced datasets using upsampling methods  
4. How to use the LIME library to explain predictions of machine learning models 
5. Interpreting what the ROC curve means 
6. Interpreting the Classification Report of the models 
7. Collborate using GitHub repository 

## Contributions 
--- 
 
* [@TanRyan](https://github.com/TanRyan) - Exploratory Data Analysis
* [@Kaien21](https://github.com/Kaien21) - Data Upsampling, Decision Tree Classification
* [@georginacyc](https://github.com/georginacyc) - Random Forest Classifier, Feature Refining, Results Analysis


## References:
---

* Cukierski, W. (2012). Titanic - Machine Learning from Disaster. Kaggle. https://kaggle.com/competitions/titanic 
* Cottle, P. (2012). learnGitBranching. GitHub. https://learngitbranching.js.org/ 
* Titanic. (2024). Wikipeida. https://en.wikipedia.org/wiki/Titanic 
* Tikkanen, A. (2024) Titanic. Encyclopedia Britannica. https://www.britannica.com/topic/Titanic 
* Thaker, T. (2021). What is upsampling and downsampling with examples?. Kaggle. https://www.kaggle.com/discussions/general/262007
