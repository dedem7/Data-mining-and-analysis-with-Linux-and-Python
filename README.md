# Data-mining-and-analysis-with-Linux-and-Python
More than 20k .csv files given. 
The structure of each file doesn't have a "data frame" structure, however the structure of each file is similar to another. 
The task is to join all .csv files in one and to keep such form of file that will allow to make further analysis. 
For this purpose Linux(bash) was used. For further analysis, Python (pandas) was used.

#Data description
The data contains indication of temperature from machine in manufacture. Machine each day, every certain hour, sends a signal to monitoring systems,as a degrees of celcius.
Machine has two sides: Delta1 and Delta2, each side sends the state of temperature. 
Two machines have two different numbers, the first has 001 and second has 002, respectively.
Date and time are given. The "File" column displays the list of filename to which the rows are related.
old.csv is one of original files, used for demonstrating how the files were looked like before "fixing" them 

#files
The mining.rar folder consists of scripts and the .csv files that were achieved by implementing these scripts.
s001.csv and s002.csv files are the parts of all.csv file. The "s001.csv" was implemented from one folder that has data for machine number 001 and "s001.csv"
has information from 002 machine.

"bashscript.sh" is a script, which was used for creation all.csv(final file) 
"python.ipynb" is a script for getting answers for questions, listed in "questions.txt"
