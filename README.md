# IPL_WIN_PREDICROR
**Description**
In this Machine Learnig project, I will make an IPL Win Predictor and implement an end to end machine learning project. The Win Predictor will take the inputs about the situation of match a will predict the percentage of winning of both teams playing as per situation of match at that time.

**DataSet**
I took the dataset for the project from kaggle. I use two datasets named deliveries and matches. merged them and exrtacted the required that dataset. The final dataset consists of 9 fearues and output variable. The feature are batting_team, bowling_team, city(where the match is being played), target, wickets in hand, runs_left, balls_left, crr(current_run_rate and rrr(required_run_rate) and the output variable named as result of that particular match.

##GitHub Files:

**main**
In main file, data extraction, data cleaning, preprocessing, feature engineering and model deployment and saving the model is performed. 
To run this file, open the file in google colab or jupyter notebook and execute the code cell by cell.

**IPL_Win_Predictor.pkl**
Model Saved. To Use this model upload this file in google colab. use joblib library to load the model

**Gradio**
Code to make the gradio interface for the Model. To run this code, **IPL_Win_Predictor.pkl** is required to be loaded in the colab/jupyter notebook is required.


**Share_UI**
Code to share the UI with the Cleint/Colleages to test the working of the model

**FAST_API**
Code to make the fastapi endpoint

**gradio_fastapi**
code to make the gradio interface that interacts with fastapi

**Instruction to deploy **Gradio** Interface on **Hugging Face**
* Login to hugging face
* make new repsitory
* upload the **IPL_Win_Predictor.pkl** file on hugging face by clicking to add file menu
* make requirements.txt file
* install the necessary libraries mentioned in **Gradio** file in requirements.txt file
* pull the **Gradio** file as app.py file on hugging face
* commit changes
* following the steps mentioned above you can deploy the gradio interface on hugging face
