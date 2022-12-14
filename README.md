Motive:
The goal is to predict the statements that would either support vaccination, lockdown, masking, and distancing or not.  The whole project was divided into two segments. The first segment comprises of 
Calculating Kapa for 4 different users and then counting the one with maximum occurrences of true and false values. The second segment comprises predicting the unseen data.  

Data Collection:

Data was collected through a survey done by the students. So we had three topics: vaccination, lockdown, masking, and distancing of each three datasets. Four users’ data was collected. The kappa score was calculated with respect to each user and whose scores were less than 0.2 were dropped. The final csv files for each topic were calculated by taking the maximum occurrences of true and false values. So now we had a single final output for each topic. Later all three datasets' final values were merged to obtain one full big dataset. 
Data was stored in excel sheets.


Procedure:

•	Collected labeled datasets from Annotators as either to be pro lockdowns, pro-mask-wearing, or pro-vaccination.
•	Calculated Cohen’s Kappa Score and multiple classification modeling was used. (11% increase in accuracy) Implemented Regular Expression, Stop Words, Stemming, Tokenization, N-gram, and Word Frequency for FE. 




<img width="726" alt="Screen Shot 2022-12-14 at 1 27 09 PM" src="https://user-images.githubusercontent.com/97769635/207695611-9e679f21-7592-46b6-b561-14389cd3a381.png">
