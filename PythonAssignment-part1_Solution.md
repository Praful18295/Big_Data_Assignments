## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

Python is called general purpose as this can be used to create different programs & as its easy to understand byy humans its called high-level programming lanuage

Q2. Why is Python called a dynamically typed language?

Python is called dynamically typed language because the type of the variable is determined only during runtime

Q3. List some pros and cons of Python programming language?

Pros - Easy to lean , lots of libereries are present to use , easy to interpreat , & its open source 

Cons - Slow , its can have run time error , not strong for mobile computing

Q4. In what all domains can we use Python?

Data science , Machine Learning, Deep Learning , AI

Q5. What are variable and how can we declare them?

Variables are the basic unit of storage in a programming language. These variables consist of a data type, the variable name, and the value to be assigned to the variable. Unless and until the variables are declared and initialized, they cannot be used in the program

Q6. How can we take an input from the user in Python?

By using input() Function 

Q7. What is the default datatype of the value that has been taken as an input using input() function?

string

Q8. What is type casting?

To convert one type of data to another i.e - input() function's by default data type is str this can be converted to int as int(input()).

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Yes, this can be done by spliting inputs with .split() function with input() function , we can also  use map with split the inpts into a list.


Q10. What are keywords?

Python keywords are special reserved words that have specific meanings and purposes and can't be used for anything but those specific purposes.


Q11. Can we use keywords as a variable? Support your answer with reason.

NO, 

Q12. What is indentation? What's the use of indentaion in Python?

Indentation is python is givin by 4 space ot a tab - this shows  block of code.

Q13. How can we throw some output in Python?

We can use print() command to give output or return function

Q14. What are operators in Python?

operators are special symbols that designate that some sort of computation should be performed.

Q15. What is difference between / and // operators?

/ provides divison value in float & // provides division value in integer.

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
string = iNeuron
print(string*4)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

a = int(input("Enter a num "))

if a%2==0:
    print("No is even")
else:
    print("No is odd")

Q18. What are boolean operator?

Boolean Operators are simple words (AND, OR, NOT or AND NOT) used as conjunctions to combine or exclude keywords in a search, resulting in more focused and productive results. This should save time and effort by eliminating inappropriate hits that must be scanned before discarding.


Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```

1
0
False
1


Q20. What are conditional statements in Python?

Conditional statements are used to handle conditions in your program. These statements guide the program while making decisions based on the conditions encountered by the program - if, else-if , nested-if.

Q21. What is use of 'if', 'elif' and 'else' keywords?

if - The if condition is considered the simplest of the three and makes a decision based on whether the condition is true or not. If the condition is true, it prints out the indented expression. If the condition is false, it skips printing the indented expression.

elif- The if-else condition adds an additional step in the decision-making process compared to the simple if statement. The beginning of an if-else statement operates similar to a simple if statement; however, if the condition is false, instead of printing nothing, the indented expression under else will be printed.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

Age = int(input("Enter your age"))

if Age>18:
    print("I can vote")
else:
    print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```


l = []

for x in numbers:
    if x%2==0:
        l.append(x)
s = l.sum()
print("sum of num is ",s)


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

num1 = int(input(Enter 1st  number: "))
num2 = int(input(Enter 2nd  number: "))
num3 = int(input(Enter 3rd  number: "))

numbers = [num1 , num 2, num 3]

print(max(numbers)

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

numbers = [12, 75, 150, 180, 145, 525, 50]


n = []

for i in numbers:
    if i > 150:
        if i > 500:
            break
        continue
    if i % 5 == 0:
        b.append(i)
        
print(b)