# MLEnd
A machine learning project exploring a dataset of spoken numerals.

## The dataset
The dataset contains 20,000 spoken numerals. The entries were gathered as part of Machine Learning module at Queen Mary University of London in 2021.
Each participants has been asked to record a set of spoken numerals (0-20, 30, 40, 50, 60, 70, 80, 90, 100, thousand, million, billion) in 4 different intonations (neutral, bored, excited, question).

## The models
This project contains two models:
### Prediction of intonation of the speaker
### Prediction of the digit spoken

# Setup
The project requires a download of the dataset. This can be done locally or in Google Drive. Instructions for Google Drive setup.

## Google Drive set up
1. Go to https://drive.google.com/
2. Create a folder named 'Data' in 'MyDrive'
3. Open the 'Data' folder and create a folder named 'MLEnd'
4. Move the file 'trainingMLEnd.csv' to the newly created folder 'MyDrive/Data/MLEnd'
5. Instructions for downloading the database can be found in `database_download.ipnyb`

# Project contents
This repository contains the following files
- `trainingMLEnd.csv` a file containing information about the dataset
- **`database_download.ipnyb`** notebook with instruction on how to download the dataset
- `features.csv` a file containing all features extracted from the dataset
- `intonations.csv` a file containing the intonations associated with features extracted
- `numerals.csv` a file containing the numerals associated with the features extracted
- `telephone_numbers` a folder containing 15 .wav files of sequences of 11 numbers spoken
