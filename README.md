# NSW-towaway-crash-predictive-modelling
Supervised machine learning modelling of NSW road crash data to predict towaway crashes. Focuses on hyperparameter optimization and model evaluation. 

## Introduction 

### Backgrond 
Road traffic incidents remain a significant public issue in Australia, with high fatalities recorded across most states. New South Wales recorded the highest number of deaths at 375, followed by Queensland with 311 deaths. To address this, NSW launched the Road Safety Action Plan 2026, which aims to achieve a 30% reduction in serious injuries by 2030. While extant literature has extensively documented factors contributing to fatal and serious injury crashes, research concerning property- damage- only (PDO) crashes remains sparse. This research addresses this gap by examining specific risk factors and patterns associated with tow- away crashes. Although frequently overlooked in favor of injury severity analysis, tow- away crashes constitute the majority of reported incidents, and provide critical insights into property damage and underlying road design risks. By analyzing this segment, this research seeks to broaden the understanding of crash dynamics beyond fatal outcomes. 

### Objectives 
1. Evaluate machine learning models for predicting tow- away crash outcomes
2. Identify key predictor variables associated with tow- away crashes

## Workflow diagram: 
Raw dataset 
↓
Preprocesisng 
↓
Modelling approach 
↓
Model Tuning 



## Dataset Description 
The dataset consists of 107,425 police reported crashes in New South Wales between 2016 and 2020, released by the Transport for NSW. Each record contains a view of crash locations and characteristics, environmental conditions, as well as the involved vehicle types, driver, passenger demographics and injury outcomes. A total of 14 predictor variables were used in the analysis with four injury outcomes (fatal (1.5%), serious (20.9%), moderate (27.5%), tow- away crashes (31.9%)). The outcome of interest is tow- away crashes, defined as events in which no casualties occured but at least one vehicle required towing, accounting for the largest proportion of injury outcomes. 

 ## Data Pre- Processing: 

 ### Data cleaning 

 ### Handling missing values 

 ### Encoding variables (feature engineering?) 

 ### Feature selection 

 ## Modelling approach

 ### Train/ test split 
 The dataset was partitioned into training (80%) and testing (20%) subsets using stratified sampling to maintain consistent class proportions across crash outcomes. Model training was conducted on the balanced training set and model evaluation on predictive performance was done on the independent test set. 

 ### Stratified sampling 
 ### Handling class imbalace (SMOTE) 
 ### Model justification/ used/ tested? 
 ### Hyperparameter tuning 
 ### Evaluation metrics 

 ## Results 
 ### Model performance 
 ### Variable importance 

## Discussion 
### ? why did that model work? 
### Limitations 
 
