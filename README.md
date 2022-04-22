# This repository is the repository of paper 'Drug Resistance and Interaction Prediction Using Geometric Deep Learning on HIV-1 Virus'

## First clone this repository

## After cloned this repository there are two ways to run the python script and see the output.

## First and recommended way is creating a python virtual environment and installing requirements that specified in requirements.txt.
**Run following commands** 

-pip install virtualenv

-virtualenv venv

-.\venv\Scripts\activate.bat  * *(For windows)* *

-source mypython/bin/activate  * *(For linux)* *

-pip install -r requirements.txt



**And execute main.py in order to see results in visualizations folder.**

* *(It may take longer or shorter depending on the processing capacity of the computer you are using.)* *

**Run this command**

-python main.py

Few examples of results you can see inside the visualization folder

Roc Curve

![roc curve](/visualizations/roc curve.png)

Accurarcy

![roc curve](/visualizations/auc.png)

F1 Score

![roc curve](/visualizations/f1 score.png)

Drug Predictions

![roc curve](/visualizations/drug results.png)

## The second way is to make the project an isolated docker container and run it in a computer that docker installed.
**Run following command**

docker-compose up





