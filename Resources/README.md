# Resources

This folder contains files required for the file handling tasks in chapter 4 as well as some useful code snippets for common tasks. 

&nbsp;
&nbsp;

## Invalid number input

```python
#Check if user enters valid input
x = input("Enter a number: " )
while (not x.isnumeric()):
    print("Invalid input")
    x = input("Enter a number: " ) #get number again
print("Input number: ", x )
```

&nbsp;
&nbsp;

## Random Number generation

```python
# Program to generate 5 random numbers between 0 and 100

# importing the random module
import random
for i in range(0,5):
    print(random.randint(0,100))
    #randint() generates random values
```

&nbsp;
&nbsp;

## Check for number in String

```python
# Check if string contains any number
# Using isdigit() + any()
 
# initializing string
text = 'CodeLab 2 Module'
 
# printing original string
print("The original string is : " + str(text))
 
# using any() to check for any occurrence
res = any(chr.isdigit() for chr in text)
     
if res == True:
    # printing result
    print("string contains digit ")
else:
    print("String has no digit")

```

&nbsp;
&nbsp;

## Convert to upper / lower case

```python
# Convert to lowercase/uppercase

# initializing string
text = input("Enter the text")
if text.isupper():
    print(text.lower()) 
    #Converts to lowercase
else:
    print(text.upper())
     #Converts to uppercase
```



