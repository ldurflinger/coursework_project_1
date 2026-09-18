# Coursework Project #1 (NHL Data Wrangling and Analysis)

## Table of Contents  
- [Project Title](#Project-Title)  
- [Description](#Description)  
- [Tools and Technologies Used](#Tools-and-Technologies-Used)  
- [Files Used](#Files-Used)  
- [How to Run Program](#How-to-Run-Program)  
- [Additional Information](#Additional-Information)

## Project Title  
**NHL Data Project -- Wrangling and Analysis to See what Statistics Win Hockey Games**

## Description  
*We wanted to find out what statistics heavily related to wins in NHL games. One of the requirements for this project was to scrape a website for external data or find an API for data to combine with our original dataset found on Kaggle. 
We wanted to answer multiple questions:* 
- Question 1: Which team statistics are most strongly correlated with winning a game?
- Question 2: Do offensive statistics (such as goals and shots) have a greater impact on winning than defensive statistics (such as blocks and takeaways)?
- Question 3: Is there a relationship between possession-related statistics (like faceoff win percentage) and winning?
- Question 4: Do team statistics increase or decrease between regular season and post season games?

To answer these questions, we needed to merge the two DataFrames. After, we spent time cleaning the data and removing unnecessary data that we did not plan to use in our analysis. Lastly, we would use our data to create an analysis to answer each question previously mentioned.  

## Tools and Technologies Used  
#### Data Sourcing
- Kaggle: Used to source original data
#### Environment and Language
- Jupyter Notebook: Interactive computing environment used to create and run code
- Python: Core programming language of Jupyter Notebook 
#### Libraries and Data Manipulation
- Pandas: Used for data cleaning, manipulation, and structured analysis.
- NumPy: Used for high-performance mathematical functions and array operations
#### Data Visualization
- Matplotlib: Core library used to create static, interactive visual graphs
- Seaborn: Built on top of Matplotlib, used to generate clean and informative statistical graphics.
#### Machine Learning & Modeling
Scikit-learn (sklearn): Used to split data into training/testing sets (train_test_split) and build the predictive Logistic Regression model. 

## Files Used  
*To run the analysis, you will need to have Jupyter Notebook and the underlying files provided here. It is important to run the Jupyter files (denoted by the file extension ".ipynb") in the specific order listed here: Merge, Cleaning, then Analysis.*
#### Files
* **Jupyter Notebooks**
  - [NHL_Project_Merge.ipynb](data/NHL_Project_Merge.ipynb)  
  - [NHL_Project_Cleaning.ipynb](data/NHL_Project_Cleaning.ipynb)  
  - [NHL_Project_Analysis.ipynb](data/NHL_Project_Analysis.ipynb)  

* **Data Files**
  - [game.csv](data/game.csv)  
  - [game_teams_stats.csv](data/game_teams_stats.csv)  
  - [team_info.csv](data/team_info.csv)  

## How to Run Program  
*To run the files, you will need to have access to Jupyter Notebook and have all files within the same folder and folder level. After that, it is as easy as clicking 'Run all cells' through each notebook as long as you run them in order. Then you will be able to see the analysis.*  

##  Additional Information  
*I do not consent to other students using my group's property to cheat on assignments. This assignment was made for analysis of NHL games to complete a final project at my university. It is okay to evaluate and use techniques shown within the files, but please do not try to use the files for your own benefits. ***I do not want any university breathing down my back since I am only putting this on GitHub to showcase my skills for future employment.****  
