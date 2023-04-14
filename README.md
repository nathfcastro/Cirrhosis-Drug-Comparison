# Cirrhosis Data 
---
## Cirrhosis Data Set 
### Brief Decscription of Data 

Data Source: https://www.kaggle.com/datasets/fedesoriano/cirrhosis-prediction-dataset

Total of 424 PBC patients that was referred by ther Mayo clinic during a ten-year interval had met an eligible criteria for a randomized placebo-control trial of the drug D-penicillamine. For the first 312 patients that participated in this clinical trial. However, 112 patients did not participate in the clinical trial, but consented to have the basic measurements recorded and siz of the cases were lost to follow-up shortly after diagnosis. 

#### Target: Drug - the type of drug that was given to the patients during the clinical trial (placebo or D-penicillamine).
#### Number of Features: 19 Features in this dataset. 
---
## Visual One:
![image](https://user-images.githubusercontent.com/122195358/232169717-92abfdc5-c933-4e23-9f45-1767507f9ad0.png)
#### Majority of patients who used the placebo drug has a lower Alkaline Phosphatase level which indicates the drug is not taking effect on the patients. 
Majority of patients who use the D-penicillamine has a higher Alkaline Phosphatase level which indicates the drug is working 
---
## Visual Two:
![image](https://user-images.githubusercontent.com/122195358/232169777-4083fb5b-56eb-49c0-9bd5-d9861ddae04a.png)
#### The visual above depicts that patients with a low bilirubin have taken the D-penicillamine and the patints with high biliburin have taken the placebo which indicates whether the drug was affected or not. 
---
## Conclusion: 
Using the random forest classifier was the best method because it had a 64% accuracy while the KNN model had a 62% accuracy. The model could solve over 60% of the busines problem because it depicts on the lab levels of patients when the placebo is taken or when D-pencillamine was taken. My reccomendations for the stakeholders is to use the Random Forest Classifier to ensure they would have the highest accuracy they can get. Additionally, having the unknown variable in the target unit should not be present and to ensure a more accurate result. 
