# FYP Project
## The Forensic Analysis of Wearables
### Paul Murphy - 17198046
### Supervisor - Thomas Welsh

# Introduction
The forensic Analysis of wearables is the use of tools and methodologies to make data from a wearable more usable to forensic analysts. This code was developed after data from the wearable had been extracted. The main aim of this code was to develop a script to read in a database and display user's activity while wearing the watch which fell under the following categories:
- Sleep
- HeartRate
- Location

Also, in this paper there was a requirement to add a datetime column to csv files for data visualization using a third party software. To summarise, the code developed in this project serves two purposes:
- FYPScript.ipynb is a tool to visualize a user's data in a useful manner to forensic analysts
- ConversionScript.ipynb is a simple script to convert a csv input to be usable for the Visualization Software Tableau

## How to Run-FYPScript
To run this script you require two files from this repo, FYPScript.ipynb and the database file fitbit.7ZWTNH.db. 
- You must download these files and place them in the same directory as each other
- If you wish to use a different databse simply replace this databse file with your own
- Simply open the notebook file in Jupyter notebook and run the cells until the date picker cell
- The first option you'll be prompted at is the dataPicker widgets
- Choose the start date and end date as the ranges in which you want to visualise
- After this, you can continue to run the cells
- The location visualization will be ran first and produces a html file with the output
- Then the sleep and heart rate logs will produce a similar output
- These outputs will be saved in the same directory with appropriate name such as location html


## How to Run-ConversionScript
To run this script you require two files from this repo, ConversionScript.ipynb and the CSV file ExerciseTrackPointDbEntity.csv
- You must download these files and place them in the same directory as each other
- If you wish to use a CSV simply replace this CSV file with your own
- Simply open the notebook file in Jupyter notebook and run the cells
- This will add a datetime column to the CSV and save as a new CSV under the name PreparedExerciseTrackPointDbEntity.csv
