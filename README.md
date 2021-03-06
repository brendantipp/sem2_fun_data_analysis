
## This repository contains the files for the Fundamentals in Data Analysis Tasks 2020

### Four tasks are contained in on Jupyter Notebook named tasks

#### BRENDAN RYAN - GMIT 



### How to run the jupyter notebook


The Jupyter notebook can be viewed on my My repository is held on GitHub - https://github.com/brendantipp/sem2_fun_data_analysis


You can also download and run the Jupyter notebook from the repository to your local hard drive and open with Jupyter Notebooks - www.jupyter.org

The following is useful step by step guide on how to open and run a jupyter notebook - https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html


### Details of Git Repository
The repository for the assignment and all the files are located here https://github.com/brendantipp/sem2_prog_data_analysis_project

#### Contents of the Repository

Files

- tasks.ipynb (Jupyter notebook for Project)
- REAME.md (Details of the project, how to run the files, details of the repository)
- licence (licence used)

Folders

- Images Folder - contains any images used in the jupyter notebook

The Software used:

- Annacoda distribution package (Python, Git) - www.anaconda.com
- Jupyter Notebook - www.jupyter.org
- cmder - www.cmder.net
- Github www.github.com


## Overview of tasks relating to repository

###  Task 1

##### Task Description
Within the Jupyter notebook write a python function called counts that takes a list as an input and returns a dictionary of unique items in the last as keys and the number of times each item appears as values.





#### Development plan

- Write fucntion counts in Python using Jupyter notebook 
- Function will require an input list and an output dictionary
- Function will require a count of each of input (using inbuilt python fuction .count)
- Create a for loop to loop through each list value/key and create a dictionary (named dict) with a key and value(the value which will be the count of each key)
- Possibly require a sort function TBC
- Wrap loop in function named counts
- Our output will be created by passing our input "lists" into our new function counts()


#### Task Research and references:
- https://medium.com/swlh/create-a-dictionary-from-a-list-65742246ab4b
- https://www.geeksforgeeks.org/python-ways-to-create-a-dictionary-of-lists/
- https://www.w3schools.com/python/python_dictionaries.asp
- https://realpython.com/courses/lists-tuples-python/



#### How to run and test/view out new function

The created function counts() can be viewed and tested interactivley using the jupyter notebook tasks.ipynb



### Task 2

### Task Description

Write a Python function calleddicerollsthat simulatesrolling dice.  Your function should take two parameters:  the number of dicekandthe number of times to roll the dicen.  The function should simulate randomlyrollingkdicentimes, keeping track of each total face value.  It should then returna dictionary with the number of times each possible total face value occurred.  So,calling the function asdiceroll(k=2, n=1000)should return a dictionary like:{2:19,3:50,4:82,5:112,6:135,7:174,8:133,9:114,10:75,11:70,12:36}You can use any module from the Python standard library you wish and you shouldinclude a description with references of your algorithm in the notebook


#### Development plan

- Write function dicerolls in Python using Jupyter notebook
- import random from standard library
- create for loop for the range 0 to number of throws k
- define the max score possible as 6 sides x the number of dice
- pick a random number up to the maximum possible score
- append each throw to a list and use function counts to output the results in a dict 


References:
- https://www.geeksforgeeks.org/python-randint-function/
- https://www.askpython.com/python/dictionary/delete-a-dictionary-in-python


### Task 3

### Task Description 

The numpy.random.binomial function can be used to simulate flipping a coin with a 50/50 chance of heads or tails.  Interestingly, if acoin is flipped many times then the number of heads is well approximated by abell-shaped curve.  For instance, if we flip a coin 100 times in a row the chance ofgetting 50 heads is relatively high, the chances of getting 0 or 100 heads is relatively low, and the chances of getting any other number of heads decreases as you moveaway from 50 in either direction towards 0 or 100.  Write some python code that simulates flipping a coin 100 times.  Then run this code 1,000 times, keeping track of  the  number  of  heads  in  each  of  the  1,000  simulations.   Select  an  appropriate plot to depict the resulting list of 1,000 numbers, showing that it roughly follows a bell-shaped curve.  You should explain your work in a Markdown cell above thecode.




###  Task 4

### Task Description 


Simpson’s paradox is a well-known statistical paradox where a trend evident in a number of groups reverses when the groups are combined nto one big data set.  Use numpy to create four data sets, each with an x array and  a  corresponding y array,  to  demonstrate  Simpson’s  paradox.   You  mightcreate  your xarrays  using numpy.linspace and  create  they array  for  eachxusing notation likey = a * x + bwhere you choose theaandbfor each x,y pair to demonstrate the paradox.  You might see the Wikipedia page for Simpson’s paradox for inspiration


Refenences 

https://en.wikipedia.org/wiki/Simpson%27s_paradox




END
