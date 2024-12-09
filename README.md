# Techup-Audio-Classification
TechCabal Ewè Audio Translation Challenge solution from Zindi that obtain position 42.

#Introduction
TechCabal Ewè Audio Translation Challenge (Zindi)
Task to build a model to recognise Ewè commands from audio samples (more than 5000 train dataset and less than 3000 test dataset).

The dataset was built 100% by Umbaji community members with the support of Google Cloud For Startups in 2023, as well as Microsoft Entrepreneurship For Positive Impact.
consist of EWE language ,speaking when:
Crossing road background noise
Rain and thunder background noise
Rural and forest background noise
Firefighters alarm background noise

#Objective
The objective of this hackathon is to create machine learning models that can accurately classify audio recordings of basic directional commands in Ewè: "up," "down," "stop," "go," "left," "right," "yes," and "no."
 

#ETL process
Data extraction:
Datasets (variable information,training and testing)  in CSV format were collected from the Zindi website. To facilitate efficient data handling and avoid daily upload limits, these datasets were uploaded to Google Drive and then connected to Google Colab. The Pandas library was imported into the Colab environment to enable the loading and manipulation of the CSV files.

#Load:
Datasets and audioes was stored in memory (Google drive) and were read in librosa for immediate access during the modeling process.

#Run time:
Run time for the entire notebook 15 minutes.

#Performance Metrics:



