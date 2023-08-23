# Chapter 5 - Exercises
Exercises with a tick mark ☑️ represent exercises that must be submitted for the Programming Skills Portfolio as a minimum expectation. Completing more exercises provides the opportunity to attain higher marks. For each exercise you should create a new project with the name of the exercise and save it to this folder in your local repository.

Once you have completed your solution you should make sure you commit and push your solutions to your remote repository on GitHub. You can commit and push as many changes to your solutions as you wish, only those pushed before the deadline will be marked for the Programming Skills Portfolio.

---
&nbsp;
&nbsp;
## Exercise 1: Woof Woof ☑️
 
Write a program that declares a class which defines the characteristics of a dog. The program should instantiate two objects from this class and assign data to its members.
The program should then output the data from each object and the oldest dog should woof via a class method.
&nbsp;
&nbsp;
## Exercise 2: Student Class ☑️
Create a class called students.
- The class should have the following members.```Name (string), Mark1 (int), Mark2 (int), Mark3 (int) ``` 
- The class should have the following methods
```calcGrade()``` - should return an average from the three marks.```display()```- should output the student name and calculated grade average
- Create one object using a constructor that contains parameters to initialise all of the variables
- Ask user to input the variable values using input() and pass the values to the second object
&nbsp;
&nbsp;
## Exercise 3 :Employee Class ☑️
Create an employee class with the following members:
 ```name, age, id, salary```
- Add the following methods:
```setData()``` - should allow employee data to be set via user input,```getData()```- should output employee data to the console
- Now create a list of 5 employees. You can create a list of objects in the following way, appending the objects to the lists.
``` python
  emp_object = []
  for i in range(5):
    emp_ object.append(ClassName())
```
Expected output:
```
Name             id      Age     Salary
AAA              20      1       2000
BBB              22      2       2500
CCC              20      3       1500
DDD              22      4       3500
EEE              22      5       4000
```
&nbsp;
&nbsp;
## Exercise 4: Shapes ☑️
Create a parent class called shape. This should have following methods
```inputSides()``` – Ask user to enter the sides of the shape. Now create subclasses for a circle, rectangle and triangle. These should include an appropriate ```area()``` method that will use the side values from the shape class.
&nbsp;
&nbsp;
## Optional Exercise 5: Playing around in class
Use this exercise to play around with creating and accessing class members and methods. Create a class called Animal
- Give the class at least the following members  ```Type, Name, Colour, Age, Weight, Noise```
- The class should have the following methods
```sayHello()``` - says its name via print,```makeNoise()``` -make an appropriate noise via print, ```animalDetails()``` -output all the details of the animal object
- Instantiate at least two objects from your animal class (e.g. Dog, Cow)
- Set values for each of the variables
- Invoke each of the class functions
