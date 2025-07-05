# DSND-blog-post-project

The goal for this project is to study the following questions for the Stack overflow developer survey data:

Questions:

    What are the most important features of the data set, what do they mean, and how do they drive the predicted outcome? 
    What unusual, or creative, insights are you able to gather from the data set?
    How accurate is the model that you have trained to predict the data in the data set?
    What will happen in a creative, predictive, scenario using the model that you have trained?


The goal of this project would be to see if it is possible to predict how many years the developers have been coding, based on various data inputs that will be decided based on whether or not there is a correlation between certain data 

The data source for this project is the "Stack Overflow Annual Developer Survey". Specifically, I'll be using the 2022 data to train the model, and then test the resulted trained model on the 23 data.

To acheive this, I'll check what coloumns are common between the '22' and the '23' survey results. Then, the model, once selected based on data understanding, will be trained on the '22' data and then tested on the '23' data.

initial comparison between the two years was done to see which columns were common, there are 63 common coloumns. Of coures, any coloumns that are dropped here for the '22' data in the coures of the data cleaning and preperation would also be dropped in the '23' data to ensure correct measure of the model accuracy that would be based on factors other than the data (i.e., hyber parameters adjustments).

The following libraries were used in this project:
pandas 
numpy 
matplotlib.pyplot 
seaborn
sklearn.preprocessing
sklearn.tree
sklearn.model_selection
sklearn.metrics


Check the following link for more details about my work on this project:
https://medium.com/@unamedpersonemail/analysis-and-work-on-the-stack-overflow-annual-developer-survey-a1d8b12143da

In this project, the all the data sets that were used are in the following link:
https://survey.stackoverflow.co/

Files in this project: 
"Main.ipynp" file has the main python code for the project. 
"22 survey data.zip" has the main data set used in this project
"readme.md" the normal readme file. 
