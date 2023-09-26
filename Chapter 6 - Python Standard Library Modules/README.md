# Chapter 6 - Exercises
Exercises with a tick mark ☑️ represent exercises that must be submitted for the Programming Skills Portfolio as a minimum expectation. Completing more exercises provides the opportunity to attain higher marks. For each exercise you should create a new project with the name of the exercise and save it to this folder in your local repository.

Once you have completed your solution you should make sure you commit and push your solutions to your remote repository on GitHub. You can commit and push as many changes to your solutions as you wish, only those pushed before the deadline will be marked for the Programming Skills Portfolio.

---
&nbsp;
# Assessment Exercises
## Exercise 1: Basic Math ☑️
Using math module compute the following
- For a =2.3 find the ceil of a
- For a =2.3 find the floor of a 
- For a = 5 find the factorial of a
- Find the value of 2<sup>3</sup>
- For a=16 find the square root of a

&nbsp;
&nbsp;
## Exercise 2: Numpy Array ☑️
For the array a = [20,23,82,40,32,15,67,52] print the output of following
- find the indices of even numbers
- Sort the array
- Slice elements from index 3 to the end of the array
- Slice elements from index 0 to index 4
- print [32 15 67] using negative slicing

&nbsp;
&nbsp;
## Exercise 3: Calculator☑️
Write a program that will display the following calculator menu 
```
1. Add
2. Subtract
3. Multiply
4. Divide
5. Modulus
6. Check greater number
```
The program will prompt the user to choose the operation choice (from 1 to 6). Then it asks the user to input values for the calculation. The program outputs the results of the calculation.Use operator module functions

### Extension Problem (Bonus):
- Allow the user to keep entering values until they enter Q to quit.
- Handle incorrect input
 
&nbsp;
&nbsp;
## Exercise 3: Line graph ☑️
-  Draw a line in a diagram from position (1, 2) to position (6, 8)
-  Draw a dotted line in a diagram from position (1, 3) to (2, 8) then to (6, 1) and finally to position (8, 10)
 
&nbsp;
&nbsp;
## Exercise 4: Working with JSON File ☑️
Create a JSON file named 'StudentJson.json' with the following details
1. Ask the user to enter the student name, ID, and course and write these contents to the JSON file.
2.Read the contents from the JSON file and display the individual values.  
  Expected Output :
  ```
  Details of the Student are
 		Name: Alpha
 		ID: 1
 		course: BSc CC
```
3. Append another dictionary as follows as key value pair for student 1 in StudentDetails dictionary to form a nested dictionay. Later update the JSON file.
```
 "CourseDetails":{ 
             		 "Group": "A",
             		 "Year": 2
		}
```
4. Print the individual vlaues of the Student details reading from JSON file.

  Expected Output :
```
Details of the Student are
		  Name: Alpha
		  ID: 1
 		 course: BSc CC
 		 Group: A
 		 Year: 2
```
 
&nbsp;
&nbsp;
## Bonus Assessment Exercise A: Bar graph
Draw a bar graph with the following information
- Title: Most valuable brands worldwide in 2023 (in billion U.S. dollars)
- brands = [ "Amazon", "Apple", "Google", "Microsoft", "Walmart", "Samsung Group", "ICBC", "Verizon", "Tesla", "TikTok/Douyin"]
- values = [299.28, 297.51, 281.38, 191.57, 113.78, 99.66, 69.55, 67.44, 66.21, 65.67 ]
- Source - https://www.statista.com/statistics/264875/brand-value-of-the-25-most-valuable-brands/
 
&nbsp;
&nbsp;
# Further Exercises
## Exercise I: Stack bar graph
In January 2007, a Gallup poll asked 1008 Americans aged 18 and over whether they planned to watch the upcoming Super Bowl. The pollster also asked who planned to watch whether they were looking forward more to watch football games or commercials. The results were summarized in the table
```
                Male	 Female	  Total
Game		279	  200	    479
Commercials	81	  156	    237
won’t watch	132	  160	    292
Total		492	  516	    1008
```
 
&nbsp;
&nbsp;
## Exercise II: Working with JSON file (Extension)
In the above Exercise 4: Working with JSON File add details of another student and display the contents of JSON File.
