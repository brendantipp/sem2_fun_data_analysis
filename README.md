
## This repository contains the files for the Fundamentals in Data Analysis Tasks 2020

### Four tasks are contained in on Jupyter Notebook named tasks

## Task 1

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
https://medium.com/swlh/create-a-dictionary-from-a-list-65742246ab4b

https://www.geeksforgeeks.org/python-ways-to-create-a-dictionary-of-lists/

https://www.w3schools.com/python/python_dictionaries.asp

https://realpython.com/courses/lists-tuples-python/


#### counts function code 

        # create the required list
         list = ['A', 'A','B', 'C','A']
         
         # create an empty dictionary
        dict = {}

    # create a for loop to count result and return as a dict
    # range and len for loop per research link ttps://medium.com/swlh/create-a-dictionary-from-a-list-65742246ab4b
    # reference https://www.geeksforgeeks.org/python-ways-to-create-a-dictionary-of-lists/
    # dictionary key being the item found and the value the count of same 
    # wrap code in function counts()

    def counts(list):

        for l in range(len(list)):
            dict[list[l]] = list.count(list[l])
        print (dict)
    
    #output is created passing list to our new function counts
     counts(list)

Using the input list the following output is created - {'A': 3, 'B': 1, 'C': 1}


#### How to run and test/view out new function

The created function counts() can be viewed and tested interactivley using the jupyter notebook tasks.ipynb

