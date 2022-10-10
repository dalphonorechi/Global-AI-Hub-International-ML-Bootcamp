I participate in the month long Global AI Hub ML Bootcamp.

This Repo contains Notebooks for:

* Competion : Predict Career Longevity for NBA Rookies.
* Project : Medical Cost Analysis.


# Competion.
This is a week long competion that was for the Global AI Hub ML Bootcamp and Dphi.
It was part of the Python for Machine Learning International Bootcamp by Global AI Hub.

**About the data**

* [Train](/longevity_train.csv).
* [Test](/longevity_test.csv).

The dataset contains player statistics for NRB Rookies. There are 1100+ observations in the train dataset with 19 variables excluding the target variable (i.e. Target).

**Data Description**

GP: Games Played (here you might find some values in decimal, consider them to be the floor integer, for example, if the value is 12.789, the number of games played by the player is 12)


The values for given attributes are averaged over all the games played by players

* MIN:  Minutes Played

* PTS: Number of points per game

* FGM: Field goals made

* FGA: Field goals attempt

* FG%: field goals percent

* 3P Made: 3 point made

* 3PA: 3 points attempt

* 3P%: 3 point percent

* FTM: Free throw made

* FTA: Free throw attempts

* FT%: Free throw percent

* OREB: Offensive rebounds

* DREB: Defensive rebounds

* REB: Rebounds

* AST: Assists

* STL: Steals

* BLK: Blocks

* TOV: Turnovers

**What we are predicting.**

* Target: 0 if career years played < 5, 1 if career years played >= 5

# Project

This is a week long project that was for the Global AI Hub ML Bootcamp.

It entails developing an end-to-end data science application using this [dataset](/insurance.csv). The aim of the project is to estimate the approximate cost of a person's health insurance based on the given variables.

* age: age of primary beneficiary 
* sex: insurance contractor gender, female, male 
* bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9 
* children: Number of children covered by health insurance / Number of dependents
* smoker: Smoking
* region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.

What we are trying to predict.

* charges: Individual medical costs billed by health insurance.

The instructions for the Project are in the Medical Cost Analysis Pdf.
