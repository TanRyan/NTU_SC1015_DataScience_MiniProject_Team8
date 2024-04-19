# NTU SC1015 Data Science Mini Project Group 8
---

#About
---

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on the Titanic Dataset from Kaggle. 
#Contributors

# Introduction
---

The RMS Titanic was a British luxury passenger as well as mail carrying ocean liner. Before the disaster, the RMS Titanic was deemed "unsinkable" However, on 15 April 1912, during its voyage from Southhampton, England to New York City, United States, it crashed into an iceberg at the North Atlantic Ocean and as a result sank. Tragically, about 1,500 of the estimated 2,224 passengers and crew aboard perished as the ship was not equipped with enough lifeboats for everyone, triggering the deadliest sinking of a single ship during that period. 

The Titanic dataset from Kaggle consists of some information of 892 passangers. 

## Dataset Attributes

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

* Most impactful features : Sex_female, Sex_male and Pclass 
* 

## What did we lean from this project?
---

1. Random Forest Classifier from sklearn 
2. Concepts about Precision, Recall and F1 Score 
3. Handling imbalanced datasets using upsampling methods  
4. How to use the LIME library to explain predictions of machine learning models 
5. Interpreting what the ROC curve means 
6. Interpreting the Classification Report of the models 
7. Collborate using GitHub repository 




## References:
---

Cukierski, W. (2012). Titanic - Machine Learning from Disaster. Kaggle. https://kaggle.com/competitions/titanic
