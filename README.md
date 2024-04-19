# NTU SC1015 Data Science Mini Project Group 8
---

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

**Attribute Notes**

**age:** Age is fractional if less than 1. If the age is estimated, it is in the form of xx.5  <br/><br/>

**sibsp:** The dataset defines family relations in this way,

Sibling = brother, sister, stepbrother, stepsister

Spouse = husband, wife (mistresses and fiancés were ignored)  <br/><br/>


**parch:** The dataset defines family relations in this way,

Parent = mother, father

Child = daughter, son, stepdaughter, stepson

Some children travelled only with a nanny, therefore `parch = 0` for them.

---
## References:
Cukierski, W. (2012). Titanic - Machine Learning from Disaster. Kaggle. https://kaggle.com/competitions/titanic
