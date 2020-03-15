# Alzheimer prediction
This project aims at predicting the alzheimers disease based on the dataset taken from the kaggle.<br>
Data was taken from here : https://www.kaggle.com/jboysen/mri-and-alzheimers

## Description about the data
| Feature    	| Description                                                                                                                              	|
|------------	|------------------------------------------------------------------------------------------------------------------------------------------	|
| Subject_id 	| The uniquie id given to a person.                                                                                                        	|
| MRI id     	| The unique id given to a sinlge MRI scan.                                                                                                	|
| Group      	| Whether the patient is Demented/Non Demented or Converted                                                                                	|
| Visit      	| Contains the number of visits. (This feature contains the visit in order.)                                                               	|
| MR Delay   	| The MR delauy time.                                                                                                                      	|
| M.F        	| Denoted the gender of the patient. (M/F)                                                                                                 	|
| Hand       	| Contains whether the patient is right handed or left handed. (In this dataset all the patients are right handed.)                        	|
| Age        	| Contains the age of the patient.                                                                                                         	|
| EDUC       	| Contains the years of education the patient went through.                                                                                	|
| SES        	| Contains the socio-economic status of the patient.                                                                                       	|
| MMSE       	| Stands for "Mini mental state examination score". Ranges from 0(worst) to 30 (best).                                                     	|
| CDR        	| Stands for clinical dementia rating. It`s a 5 point scale score. (0 = No dementia, 0.5 = Very Mild, 1 = Mild, 2 = Moderate, 3 = Severe ) 	|
| eTIV       	| Stands for"estimated intracranial volume" measured in mm3.                                                                               	|
| nWBV       	| Stands for "Normalized Whole brain volume".                                                                                              	|
| ASF        	| Stands for "Atlas scaling factor"                                                                                                        	|

## Organization of notebook
<i><ul type="none">
    <li>1.  Introduction</li>
    <li>2.  Objective</li>
    <li>3.  Understanding the data</li>
    <li>4.  Importing the necessary libraries</li>
    <li>5.  Importing the data</li>
    <li>6.  Understanding the high level details about the data</li>
    <li>7.  Exploring the data through visualizations</li>
    <li>8.  Analyzing the imbalance in the data</li>
    <li>9.  Making the necessary assumptions and changes</li>
    <li>10. Dividing the data into train and test</li>
    <li>11. Feature encoding</li>
    <li>12. Making the necessary assumptions and changes</li>
    <li>13. Training a random model and assuming it as baseline</li>
    <li>14. Training a random forest with best hyper parameters</li>
    <li>15. Training a Logistic regression model</li>
    <li>16. Training a Naive bayes model</li>
</ul></i>

## Conclusion

| Model                	| Train Accuracy 	| Test Accuracy 	|                     	|
|----------------------	|----------------	|---------------	|---------------------	|
| Random forests model 	| 0.87           	| 0.28          	| Clearly overfitting 	|
| Logistic regression  	| 0.90           	| 0.65          	| Not perfoming well  	|
| Naive bayes          	| 0.86           	| 0.71          	| Best till now       	|
