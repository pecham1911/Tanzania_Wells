## Tanzanian Water Well Project 
##### by Allison Ward, Sarah Prusaitis, and Monica Pecha

### Keep it Simple, Keep it Clean

![image](https://github.com/pecham1911/Tanzania_Wells/assets/159095917/4629b6ed-d51e-44ba-9cae-f3ca08df71a9)

## Overview
This project analyzes the factors of successful wells in the Lake Victoria basin of Tanzania and provides key recommendations to initiate investment in further development of wells in the basin to ensure clean potable water for all residents.

## Business Understanding
NGOs are looking to invest in the establishment of wells to provide clean drinking water for all Tanzanians beginning with the Lake Victoria basin. This analysis provides recommendations for well type, water source, and managment practices to ensure the most successful well development model.
        
## Data Understanding and Analysis
The dataset was taken from DrivenData, supplied by Taarifa and the Tanzanian Ministry of Water. These data were collected from 2011-2013.
    
## Description of data
#### Data shape
The data used for these analyses contained the following features: region, extraction_type_class, management_group, payment, quality_group, source_class, waterpoint_type_group, and the target was well funtionality. Focusing on hand pumps and standpipes, there were 8330 observations with non-missing data in the Lake Victoria basin. These features were selected from teh full dataset based on domain knowledge, data completeness, and exploratory data analysis. 

#### Data manipulation
The categorical features were engineered to combine similar categories within a feature, e.g., for quality_group salty, milky, colored, and flouride were combined into an other category for a total of three categories for the feature: good, other, and unknown. ------

The target, well functionality, was engineered from a ternary feature to a binary feature. The binary target was functional versus non-functional wells. In the ternary feature wells that were categorized as functional but in need of repair were included with the functional wells in the binary feature. 

#### Data limitations        
There are limitations to this dataset and analysis. The year of construction of the well was thought to be an important factor, but due to the large volume of missing data it was not included in the analysis. This analysis focused on buidling new well systems based on the predicton of successful wells from existing wells. For this reason we categorized the ternary well functionality target as binary and included the functioning but in need of repair wells with the non functioning wells to ensure our. This could have led to misclassification. Regression model coefficeints were exponentiated and probabilities were calculated making for interpretable results, but without confidence intervals for these coefficients it's difficult to understand what factors are significant. 

#### Data statistics and interpretation
Exploratory data analysis showed differences in several features by well functionality. To better understand the features and their impact on prediction of successful wells we conducted a Decision Tree analysis to assist with feature selection for logistic regression classification models. We focused on three key features with the highest probabilities from these models.

(1) There’s a 58% probability a hand pump well will be functioning.

(2) Wells that extract water manually are 62% more likely to be functioning.

(3) Wells managed by commercial groups are 72% more likely to be functioning.

All models were evaluated looking at precision values to ensure minimization of incorrectly predicting a functional well when in fact it was non functional or in need of repair.

#### Visualizations

#### Resources

JUPYTER NOTEBOOK:

PRESENTATION:

TABLEAU:

OTHER RESOURCES:

