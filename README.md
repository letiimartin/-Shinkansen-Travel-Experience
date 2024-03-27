# Shinkansen-Travel-Experience

## Project Description

This project aims to analyze the passenger experience on the Shinkansen Bullet Train in Japan using machine learning techniques. The main objective is to determine the relative importance of various parameters that contribute to the passengers’ overall travel experience. By analyzing a dataset of individual passengers who have traveled on the Shinkansen train, this study seeks to predict passenger satisfaction based on their feedback on different travel-related parameters.

## Goal

The goal of this machine learning project is to predict whether a passenger was satisfied with their overall experience of traveling on the Shinkansen Bullet Train.

## Dataset

The project utilizes two separate datasets:

- **Travel Data**: Contains information related to passengers and attributes related to the Shinkansen train.
- **Survey Data**: Consists of aggregated data from surveys indicating the post-service experience.

Both datasets are provided as raw data and require necessary data cleaning and validation steps.

### Data Files

The data has been divided into training and testing sets, located in the `Data` folder:

- **Train_Data**: To be used for building the machine learning model. This set includes labels for the target variable - `Overall_Experience`.
- **Test_Data**: To evaluate the model's performance on unseen data. The task is to predict the `Overall_Experience` level for each participant.

### Target Variable

- **Overall_Experience**: Indicates whether a passenger was satisfied (1) or not satisfied (0) with their travel experience.

### Data Dictionary

The survey levels and more detailed explanations of the data can be found in the Data Dictionary file.

## Submission File Format

Your submission should be a CSV file containing exactly 35,602 entries plus a header row. The file must have the following two columns:

- **ID**
- **Overall_Experience**: Contains values 0 & 1, where 1 represents ‘Satisfied’, and 0 represents ‘Not Satisfied’.

## Evaluation Criteria

The model will be evaluated based on the Accuracy Score, which is the percentage of correct predictions made by the model. The accuracy is calculated as the total number of correct predictions divided by the total number of observations in the dataset. The best possible accuracy is 100%, and the worst is 0%.
