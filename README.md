
![Logo](./images/mpercept_technology_thumbnail.png)


# Python Assessment 

Examinee are encouraged to attempt as many questions as possible. The questions marked `[OPTIONAL]` can be skipped but adds extra credit to your assessment if successfully completed. 
Some questions have extra points questions which on successful completion, gives you extra credit on the assessment.

Everyone has total of 120 Minutes to complete the assessment and has to submit the assessment by uploading the scripts to the Google Drive Link. Open the link by clicking :

[HERE](https://drive.google.com/drive/folders/1HdDN7ASNCQpeREHNdF6KXM734Ak13Hyr?usp=share_link)
Please rename the folder of your assessment with your name and college roll number before uploading it to the drive like `RAJU123`



#### Lets start with some basic practice.

1. Illustrate the difference between list and tuple using a sample python program.

2. Given a list of tuples [('a',1),('b',2),('c',3),('d',4)] write a simple python script to convert the above to a dictionary.
- Extra : Conver this list to a dictionary [('a',1),('a',1.1),('b',2),('b',2.1),('c',3),('d',4)]

3. Write a function that takes a list of lists and flattens it into a one-dimensional list.

Name your function flatten. It should take a single parameter and return a list.

For example, calling:`flatten([[1, 2], [3, 4]])` should return `[1, 2, 3, 4]`


# Optional Questions
1. `[OPTIONAL]` Two strings are anagrams if you can make one from the other by rearranging the letters.

Write a function named `is_anagram` that takes two strings as its parameters. Your function should return `True` if the strings are anagrams, and `False` otherwise.

For example, the call `is_anagram("typhoon", "opython")` should return `True` while the call `is_anagram("Alice", "Bob")` should return `False`.

2. `[OPTIONAL]` An extra day is added to the calendar almost every four years as February 29, and the day is called a leap day. It corrects the calendar for the fact that our planet takes approximately 365.25 days to orbit the sun. A leap year contains a leap day.

####  In the Gregorian calendar, three conditions are used to identify leap years:

- The year can be evenly divided by 4, is a leap year, unless:
- The year can be evenly divided by 100, it is NOT a leap year, unless:
- The year is also evenly divisible by 400. Then it is a leap year.
This means that in the Gregorian calendar, the years 2000 and 2400 are leap years, while 1800, 1900, 2100, 2200, 2300 and 2500 are NOT leap years.

#### Task

Given a year, determine whether it is a leap year. If it is a leap year, return the Boolean True, otherwise return False.

#### Input Format

Read , the year as integer to test.

#### Output Format

The function must return a Boolean value `(True/False)`.



### Lets get some action done!!


1. Write a class based python script to mimic a simple calculator that has the functionality of addition, subtraction, multiplication and division.
- `[EXTRA]` Inherit the simple calculator class and add some scientific calculator functionality like finding the value of sine and cosine of provided value.

2. Write a program (function!) that takes a list and returns a new list that contains all the elements of the first list minus all the duplicates.

3. Let’s say I give you a list saved in a variable: `a = [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]`. Write one line of Python that takes this list a and makes a new list that has only the even elements of this list in it.





## Flowchart to CODE !

### Convert the following flowchart to a python script.



![FLOWCHART](./images/class-register-flowchart.png)



# Special Question:
This question has the highest evaluatory points but is totally optional:
`[OPTIONAL]`

The sinking of the Titanic is one of the most infamous shipwrecks in history.
On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

Create a python notebook  and perform an exploratory data analysis (EDA) of the titanic datasets to answers the questions like : “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc), how may passengers were male/female, different class.

The dataset has about 12 columns, which are explained below;

`PassengerId`: unique IDs for each passenger onboard.

`Survived`: 1 indicates those who survived the shipwreck while 0 indicate those who failed.

`Pclass`: Passenger's socio-economic class, i.e 1st, 2nd or 3rd.

`Name`: Name of each passenger

`Sex`: Gender of each passemger

`Age`: Age of each passenger

`SibSp`: number of siblings and spouses of each passenger.

`Parch`: number of parents and children of each passenger.

`Ticket`: Ticket number of each passenger

`Fare`: Amount paid by each passenger

`Cabin`: Cabin seat of each passenger

`Embarked`: location where the passengers embarked from(either S-Southampton, Q-Queenstown or C-Cherbourg)

## The dataset is a CSV file that you can find in the data folder of this assessement.