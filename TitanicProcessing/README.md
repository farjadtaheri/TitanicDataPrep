# Titanic Data Processing Project

This project cleans and processes the Titanic dataset to make it ready for analysis. It fills missing data and adds a helpful column for survival status.

## What It Does
The code in this project does these steps:
1. Loads the `titanic.csv` file (included here).
2. Replaces missing `Age` values with the average age.
3. Adds a `Survived_Status` column: "no" for 0 (didn't survive) and "yes" for 1 (survived).
4. Saves the result as `titanic_processed.csv` (also included).

## Tools You Need
- Python 3 (any recent version works)
- Libraries: `pandas` and `numpy`

Install them with this command:
```bash
pip install pandas numpy



How to Run It
Everything you need (titanic.csv, TitanicProcessing.ipynb) is in this folder.
Open and run TitanicProcessing.ipynb in Jupyter Notebook.
Check the new titanic_processed.csv file that gets created (a sample is already here).



Files in This Project
TitanicProcessing.ipynb: The code that processes the data.
titanic.csv: The original dataset.
titanic_processed.csv: The processed dataset.


Sample of the Output
Here’s what the first few rows of titanic_processed.csv look like:
PassengerId,Survived,Pclass,Name,Sex,Age,SibSp,Parch,Ticket,Fare,Cabin,Embarked,Survived_Status
1,0,3,"Braund, Mr. Owen Harris",male,22.0,1,0,A/5 21171,7.25,,S,no
2,1,1,"Cumings, Mrs. John Bradley (Florence Briggs Thayer)",female,38.0,1,0,PC 17599,71.2833,C85,C,yes
3,1,3,"Heikkinen, Miss. Laina",female,26.0,0,0,STON/O2. 3101282,7.925,,S,yes


Notes
All files are included, so you don’t need to download anything extra.
Running the code will overwrite titanic_processed.csv with a fresh version.


Who Made This
Farjad Taheri
GitHub: https://github.com/farjadtaheri
LinkedIn: https://www.linkedin.com/in/farjadtaheri


License
This is free to use under the MIT License.