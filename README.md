# Music-Popularity-Prediction
This project focus on predicting popularity of songs based on musical features using R and Data Mining Techniques. 
Spotify records musical features and popularity based on listeners’ streams for all their songs. The data for 10,000 songs released in 2018 is acquired from Spotify’s music library using Python and Spotify for Developers. Data processing steps (using R) include cleaning based on domain knowledge, zooming to limit scope of project to songs only, and standardizing and factorizing variables. Dimension reduction to pick relevant variables is done by multicollinearity, domain knowledge, and correlation analysis. The numerical popularity is categorized using median as cutoff into categorical popular or not popular. Data mining prediction techniques used for numerical popularity are linear regression, KNN, SVM, neural network and random forest. Data mining classification techniques used for categorical popularity are KNN and Discriminant Analysis.

# Project Objective
Spotify music features for 10,000 songs was collected using Spotify for Developers with Python API. The data contains unique identifiers, 0-1 ratings, and numerical variables.

  • Ratings: popularity, acoustic, danceable, energy, speech, happiness, instrumental, live
  
  • Numerical: decibels, key, bpm, length, mode, timestamp
  
  • Unique identifiers: song id, artist name, song name
  
The objective is to use data mining to classify popularity category and predict numerical popularity rating based on the other variables.

Steps successfully completed include data cleaning, data exploration, dimension reduction, data preprocessing, and a plan for solution design.
