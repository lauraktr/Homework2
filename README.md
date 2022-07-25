# Homework 2: Regression and Classification

### Due 1 August 2022

For this homework assignment, you will be working with a dataset about possums in Australia.

You will need to use **pandas** to manage data, **matplotlib** and **seaborn** to visualize data, and **sklearn** to fit various models.

[Here](https://www.markdownguide.org/basic-syntax/) is a guide to formatting text in markdown. Please make sure to provide adequate comments throughout your notebook.

# Main Steps
1.  Fork this repository. Feel free to make commits and push along the way.
    
2.  Make the first cell a markdown cell and input a title and your name.
    
3.  Now you can import the possum dataset from possum.csv and start exploring.

4. You will need to answer the questions below.

5. Make sure to include markdown cells throughout your notebook describing what you are doing and anything interesting you find along the way. 

6. At the end include a paragraph summarizing what you have found.

7.  When you are done make a final commit and push it to your GitHub repo.



# Questions

### *Possums* (Possums.csv)
Use a method of curve fitting discussed in class to predict a possum's total length based on its head length. Make sure to visualize the data.

1. How well does the method describe the data?
3.   If you perform regression for male and female possums separately, does this increase our accuracy?

  

Use lasso regression to determine if there is a better classifier to use than head length.

3.   What are the three best classifiers?

  

Use logistic regression to determine whether a possum is male or female, then use a different classification method. Make sure to visualize the data.

4.   Which appears to be more accurate?
5.   How do the confusion matrices compare?

  

Pick 2 classification methods discussed in class and use them to classify possums by either collection site # or population. Make sure to visualize each of your classification attempts.

6.   Which classification method is more accurate?
7.   What properties are most important for an accurate prediction?
8.   Can this data be classified into these categories well?

