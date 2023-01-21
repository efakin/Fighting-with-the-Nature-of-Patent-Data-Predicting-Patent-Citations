# Predicting-Patent-Citations
CSSM 502 Final Project

Link for big USPTO Datasets: https://drive.google.com/drive/folders/1ztH3Bt-WHVLAhO8nL8tJ65lImEN4vUZT

In Final_Data_clean.ipynb, I created the model_input_clean.csv file from the USPTO Datasets. Please use model_input_clean.csv in the Final_Project_Models.ipynb notebook. I modified model_input_clean.csv in the Final_Project_Models.ipynb notebook to create model_input_final.csv, then model_input_final.csv is used as the input for the machine learning models. 

If you want to run the code in which the model_input_clean.csv was created, use Final_Data_clean.ipynb with datasets g_application.tsv, g_assignee_disambiguated.tsv, g_ipc_at_issue.tsv, g_patent.tsv, and g_us_patent_citation.tsv. However, these datasets are too big, and running these codes takes time. Thus, I suggest you to run Final_Project_Models.ipynb code directly using model_input_clean.csv dataset without using these datasets.

Note: RMSE values in my presentation are different from the ones in my final report because after the presentation, I added some new features to the models. Also after the presentation, I used some classification models which are not available in the presentation slides.
