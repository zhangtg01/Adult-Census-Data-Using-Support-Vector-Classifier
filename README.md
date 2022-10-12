# Adult-Census-Income-Data-Using-Support-Vector-Classifier

## Project Description

In this project we work on  [the adult census dataset](https://www.kaggle.com/uciml/adult-census-income#) which I have downloaded as `adult.csv`. [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Census+Income). The goal of this project is to profile people in the above dataset based on available demographic attributes.

Objectives:

Construct Exploratory Data Analysis on the dataset and visualize the correlations.
Construct a machine learning model that accurately predicts whether an individual makes more than $50,000.  


### Data

- `adult.data`  
- `adult.test`  
48842 instances, mix of continuous and discrete    (train=32561, test=16281)  
45222 if instances with unknown values are removed (train=30162, test=15060)

**Features**  
- `age`: continuous.  
- `workclass`: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.  
- `fnlwgt`: final weight, continuous.  
- `education`: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.  
- `education-num`:  continuous.  
- `marital-status`: Represents the responding unit’s role in the family. Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.  
- `occupation`: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.  
- `relationship`: Represents the responding unit’s role in the family. Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.  
- `race`: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.  
- `sex`: Female, Male.  
- `capital-gain`: income from investment sources, apart from wages/salary, continuous.  
- `capital-loss`: losses from investment sources, apart from wages/salary, continuous.  
- `hours-per-week`: continuous.  
- `native-country`: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands. 

**Target**
- `income`: Income Class (<=50K, >50K)  
- clustering data set
