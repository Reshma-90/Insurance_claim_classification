# Insurance_claim_classification
This repository contains code for building a ML classification model for insurance claim status.
## Goal of this project:
The goal of this model is to predict tour insurance claim status for a new customer from the give details.
- The data set here conatains 3000 customer details about their tour insurance details and claim status.
### Head of the data set:
![image](https://user-images.githubusercontent.com/95558910/147240293-4dcbccaf-eedf-4281-a246-1b8483978d4e.png)
## Data Description:
Target: Claim Status 

Code of tour firm (Agency_Code)

Type of tour insurance firms (Type)

Distribution channel of tour insurance agencies (Channel)

Name of the tour insurance products (Product)

Duration of the tour (Duration in days)

Destination of the tour (Destination)

Amount worth of sales per customer in procuring tour insurance policies in rupees (in 100’s)

The commission received for tour insurance firm (Commission is in percentage of sales)

Age of insured (Age)

## EDA
- All preprocesseing steps like checking missing values,duplicate values,random error checking,outliers checking were performed and necessary steps taken.
- An Exploratory Data Analysis were performed on the dataset by doing univariate,bivariate and multivariate analysis.
- From EDA some insights were noted down.
 
## Data Splitting
- The dataset were splitted into 70:30 ratio of 70% of data as train set and rest 30% as test set.

## Model bulding
- 3 classification models Decision Tree,Random Forest and ANN were build on the data.
- Hyperparameter tuning has been performed on all the three models for better performance.

## Performance Check:
- All the basic as well as tuned models were evaluated on some performance metrics such as accuracy score,ROC-AUC score,confusion matrix,classification reports.

## Model Comparision:
-All of the models were compared based on performance metrics.
![image](https://user-images.githubusercontent.com/95558910/147257242-5cd1ed1f-4902-4196-9f31-95a9cb0d38cc.png)
- ROC curve for all models on test data
![image](https://user-images.githubusercontent.com/95558910/147257411-a59034ea-9014-4997-958d-ceee4522f4b2.png)

## Final model selection:
- It has been observed that Random Forest has performed slightly better than rest two models. Hence it has been selected as the final one for this data.

