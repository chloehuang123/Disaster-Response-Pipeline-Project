# Disaster Response Pipeline Project

### Motivation
This project is a component of the Data Science Nanodegree Program offered by Udacity in partnership with Figure Eight. The dataset for this project comprises pre-labelled tweets and messages related to real-life disasters. The primary objective of the project is to develop a Natural Language Processing tool capable of categorizing messages.

The project is structured into the following sections:

- Data Processing: An ETL Pipeline is used to extract data from the source, clean the data, and save it in an appropriate database format.
- Machine Learning Pipeline: A model is trained using this pipeline to classify text messages into specific categories.
- Web Application: This component displays the results of the model in real-time.

The purpose of this project is to make a web app using a both an ETL and Machine Learning Pipelines to create a model that will send messages to a specific disaster relief organization. 

### Instructions:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.
    `python run.py`

3. Go to http://0.0.0.0:3001/

### Screenshot results
Model result:

<img src='https://github.com/chloehuang123/Disaster-Response-Pipeline-Project/blob/main/Screenshot%202023-04-06%20at%201.27.50%20PM.png'/>

The website:

<img src='https://github.com/chloehuang123/Disaster-Response-Pipeline-Project/blob/main/Screenshot%202023-04-06%20at%201.36.51%20PM.png'/>
