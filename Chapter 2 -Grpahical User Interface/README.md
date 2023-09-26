# Chapter 2 - Exercises
Exercises under the heading **Assessment Exercises** with a ☑️ must be attempted as a minimum expectation of the programming skills portfolio assessment. The assessment exercises also include some bonus exercises, solving these bonus exercises offers the potential to attain marks in the higher grade boundaries.

Further exercises are provided for you to practice and develop your programming skills. Completing these exercises is encouraged, although they have **no impact** on the programming skills portfolio mark.
For each exercise you should create a _**new project**_ with the name of the exercise and save it to this exercises folder in your local repository. Once you have completed your solution you should make sure you commit and push the code to your remote repository on GitHub. You can commit and push as many changes to your solutions as you wish, only those pushed before the chapter deadlines will be marked for the Programming Skills Portfolio.

---

&nbsp;
## Assessment Exercises
### Exercise 1: Welcome ☑️ 
Develop a GUI program to do the following using the tkinter module
- create a label to display the welcome message and change the label font style (font name, bold, size)
- Set the default window size
- Disable resizing the window
- Add background color to the Window.

&nbsp;
&nbsp;

### Exercise 2: Managing	Layout ☑️ 
#### Exercise 2 a: Using pack ☑️ 
Create a GUI with 4 labels using the pack() geometry as shown in the below images. The	first image on the left shows	the	original display and the	second image on right shows	what	happens	when	the	window	is	resized.

![image](https://github.com/a-subhani/CodeLab-II-Python-2023/assets/70882239/961eccd9-0750-4fd5-b553-421e4d0b8d7e)   &nbsp;&nbsp;&nbsp;    ![image](https://github.com/a-subhani/CodeLab-II-Python-2023/assets/70882239/53b0d1f2-b58d-4709-8d5b-ad8b0c908ba8)

#### Additional information
Arguments values for many widgets, including Frames for Borders and Background 
- bd is used for border width. For example bd=5
- Relief is used for border-style values are FLAT, RAISED, GROOVE, SUNKEN, and RIDGE. For example relief=RAISED
- bg is used for background color.For example bg="white" or bg="#FFFFFF".

Pack arguments
- Fill: Fill the space with the widget, Values are  Y, X, BOTH. For example fill=Y
- Expand: The size of the button is expanded if the window is maximized. Values are 0,1, any number, YES, NO. For example  expand=0 (default) no expansion

&nbsp;
&nbsp;
### Exercise 2 b: Square Grid ☑️ 	
- With	the	pack	layout	manager, Create the following labels inside the frames. A and B inside the left frame. C and D inside the right frame
- Using Pack() align  A and C at the top and B and D at the bottom of the frames that contain them
- Support	resizing. Use	the	‘expand’ and	‘fill’ attributes	of	the	pack	method	to	make	the	labels	grow	and	expand	into	the	available	space.
- Assign border value as 5 to the frames
  
### EXPECTED OUTPUT
![image](https://github.com/a-subhani/CodeLab-II-Python-2023/assets/70882239/a494c28e-8e84-45d6-8f2f-ce5a90793f28)
&nbsp;
&nbsp;

## Exercise 3: Login page ☑️ 

Create a login page using the Grid geometry. 

&nbsp;
&nbsp;
## Exercise 4: Registration page ☑️
Using widgets create a GUI as shown in below image  

![Student Management System](https://github.com/a-subhani/CodeLab-II-Python-2023/assets/70882239/1115b29d-5491-4967-b164-80ba26355a56)
&nbsp;
&nbsp;
## Exercise 5: Calculator☑️ 
Develop a GUI to perform basic arithmetic operations like addition, subtraction, multiplication, Division, and modulo division using buttons. You can ask the user to enter the values in entry widget and select the operation to be performed.

&nbsp;
&nbsp;
## Bonus Assessment Exercises
### Exercise A: Temperature Converter
Develop a GUI that implements a temperature converter application using Tkinter, allowing users to convert between Celsius and Fahrenheit.
&nbsp;
&nbsp;
### Exercise B:  Age Calculator 
Create a program to take input of the user's date of birth and output the age.
Expected input: 8/5/2018
Expected output: Your age is 5 years
Hint: you can use the date from datetime package to get today's date
&nbsp;
&nbsp;
## Further Exercises
### Exercise I:  Count characters
Develop a GUI to count the number of vowels and consonants in the given string. Ask the user to enter the string
For example
Enter a word: hello world
Total number of letters: 11
Number of vowels:  3
Number of consonants:  7
Number of special characters:  1
&nbsp;
&nbsp;
## Exercise II: Capitalize letters 
Create a GUI that takes input and changes all letters to upper case.
hint : Use upper() function
