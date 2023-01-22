# Predicting-Patent-Citations
## CSSM 502 Final Project: Fighting with the Nature of Patent Data: Predicting Patent Citations

Link for big USPTO Datasets: https://drive.google.com/drive/folders/1ztH3Bt-WHVLAhO8nL8tJ65lImEN4vUZT


**Final_Data_clean.ipynb**: In this notebook, I created model_input_clean.csv file from the USPTO Datasets. Please use model_input_clean.csv in the Final_Project_Models.ipynb notebook to create the model_input_final.csv.

**Final_Project_Models.ipynb**: In this notebook, I modified model_input_clean.csv to create model_input_final.csv, then model_input_final.csv is used as the input for the machine learning models. All models were trained and tested in this notebook.

If you want to run the code in which the model_input_clean.csv was created, use Final_Data_clean.ipynb with datasets g_application.tsv, g_assignee_disambiguated.tsv, g_ipc_at_issue.tsv, g_patent.tsv, and g_us_patent_citation.tsv that are available in the Google Drive link. **However, these datasets are too big, and running these codes takes time. Thus, I suggest you to run Final_Project_Models.ipynb code directly using model_input_clean.csv dataset without using these big datasets.**


Note: RMSE values in my presentation are different from the ones in my final report because after the presentation because I added some new features to the models. Also after the presentation, I used some classification models which are not available in the presentation slides.
