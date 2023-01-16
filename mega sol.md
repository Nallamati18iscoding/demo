
Q1. Why do we call Python as a general purpose and high-level programming language?
ans ) 
 Python is called general purpose because it can used to design and develop a wide variety of applications, across multiple domain. High-level programming language means it's more user-friendly


Q2. Why is Python called a dynamically typed language?
ans)
    Dynamically typed language means that variables are checked against types only when the program is executing. We don't need to declare the variable type, the interpreter automatically interprets it.

Q3. List some pros and cons of Python programming language?
ans)
Pros:

Easy to use
Easy to integrate
Multi-paradigm approach
High library support
Cons:

Slow speed of execution compared to C,C++
Absence from mobile computing and browsers

Q4. In what all domains can we use Python?
ans)--Graphic design, image processing applications, Games, and Scientific/ computational Applications
-Web frameworks and applications
-Database Access
-Language Development
-Prototyping
-Software Development
-Data Science and Machine Learning
-Scripting
Q5. What are variable and how can we declare them?
ans)

 A variable is a symbolic name that is a reference or pointer to an object. Once an object is assigned to a variable, you can refer to the object by that name.

var = 17

Q6. How can we take an input from the user in Python?
ans)
 By using input() function.



Q7. What is the default datatype of the value that has been taken as an input using input() function?
ans  it will taek as string

Q8. What is type casting?
Ans. Type casting means changing the datatype of the variable. We can only type casting the datatype having higher bit value to the lower bit value.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Yes.

x, y, z = input("Enter three values: ").split(",")
print("Total number of students: ", x)
print("Number of boys is : ", y)
print("Number of girls is : ", z)
print()

x = [int(x) for x in input("Enter multiple value: ").split(",")]
print("Number of list is: ", x) 

Q10. What are keywords?
ans)
 Keywords in Python are reserved words that can not be used as a variable name, function name, or any other identifier.


Q11. Can we use keywords as a variable? Support your answer with reason.

Ans. Yes we can but we shoudn't as it will override the properties of the keyword.
Q12. What is indentation? What's the use of indentaion in Python?
Ans12. Indentation is the whitespace used in Python. Indentation is used to create block of statement.
Q13. How can we throw some output in Python?
ans) Using print() function.

Q14. What are operators in Python?
ans)
Ans14. Symbols or keywords used to perform certain operations on values or variable are known as operators. There are different types of operators like

-Arithmetic operators
-Comparison Operators
-Logical Operators
-Bitwise Operators
-Assignment Operators

Q15. What is difference between / and // operators?
Ans15. / is used for float division and // is used of floor (integer) division.

Q16. Write a code that gives following as an output.
iNeuroniNeuroniNeuroniNeuron
ans) "iNeuron"*3
Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
ans)
num = float(input("Enter a number: "))
if num%2 == 0:
  print(f"{num} is even")
else:
  print(f"{num} is odd")

Q18. What are boolean operator?
ans) True , False , not , and , or are the only built-in Python Boolean operators.

Q19. What will the output of the following?

1 or 0

0 and 0

True and False and True

1 or 0 or 0

ans)
1 or 0 -> 1
0 and 0 -> 0
True and False and True -> False
1 or 0 or 0 -> 1
Q20. What are conditional statements in Python?

ans) In large projects we have to control the flow of execution of our program and we want to execute some set of statements only if the given condition is satisfied, and a different set of statements when it’s not satisfied.

Q21. What is use of 'if', 'elif' and 'else' keywords?
ans) if is the first condition check for the condition.
if "if" is False then elif's condition is checked.

else is checked when all the upper condition fails.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

ans)  age = int(input("Enter you age: "))
if age >= 18:
    print("I can vote")
else:
    print("I can't vote") 

Q23. Write a code that displays the sum of all the even numbers from the given list.

numbers = [12, 75, 150, 180, 145, 525, 50]

ans)  numbers = [12, 75, 150, 180, 145, 525, 50]
add = 0
for num in numbers:
  if num%2 == 0:
    add = add+num
  else:
    continue
print(add) 
Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

ans)x, y, z = input("Enter 3 numbers seprated by comma: ").split(",")
if int(x) > int(y) and int(x) > int(z):
  print(f"{x} is greatest")
elif int(y) > int(z):
  print(f"{y} is greatest")
else:
  print(f"{z} is greatest")

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

The number must be divisible by five

If the number is greater than 150, then skip it and move to the next number

If the number is greater than 500, then stop the loop

numbers = [12, 75, 150, 180, 145, 525, 50]
ans)numbers = [12, 75, 150, 180, 145, 525, 50]
lst = []
for num in numbers:
  if num > 150:
    if num > 500:
      break
  elif num%5==0:
    lst.append(num) 

print(lst)
Q26. What is a string? How can we declare string in Python?
Ans26. In Python, Strings are arrays of bytes representing Unicode characters.

Q27. How can we access the string using its index?
Ans27. Sqaure brackets can used to access the elements of the string.

Q28. Write a code to get the desired output of the following

string = "Big Data iNeuron"
desired_output = "iNeuron"

Ans28.

string[9:16]

Q29. Write a code to get the desired output of the following

string = "Big Data iNeuron"
desired_output = "norueNi"

Ans29.

string[15:8:-1]
Q30. Resverse the string given in the above question.
ans)string[::-1]

Q31. How can you delete entire string at once?
ans)str1 = "Hello"
del(str1)

Q32. What is escape sequence?
ans)
The "backslash ()" character as an escape character. In other words, it has a special meaning when we use it inside the strings. As the name suggests, the escape character escapes the characters in a string for a brief moment to introduce unique inclusion.

Q33. How can you print the below string?

'iNeuron's Big Data Course'

ans)'iNeuron's Big Data Course'
Q34. What is a list in Python?
ans)
Python list are dynamically sized array, declared in languages like C++ and Java. A list is a collection of things, enclosed in [ ] and separated by commas.
Q35. How can you create a list in Python?
ans)You can create a list by opening and closing the square brackets.
Q36. How can we access the elements in a list?
Ans36. We can access the elements in a list by indexing.

Q37. Write a code to access the word "iNeuron" from the given list.
Ans37.

lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
lst[4][2]

lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
Q38. Take a list as an input from the user and find the length of the list.
Ans38.

n = input("Enter number of elements seprated by space: ").split(" ")
print(len(n))
Q39. Add the word "Big" in the 3rd index of the given list.

lst = ["Welcome", "to", "Data", "course"]

Ans39.

lst = ["Welcome", "to", "Data", "course"]
lst.insert(2, "Big")

Q40. What is a tuple? How is it different from list?
Ans40. Tuple is a collection of Python objects much like a list. The sequence of values stored in a tuple can be of any type, and they are indexed by integers. Tuples are immutable where as list are mutable. We can also faster through the tuples than the list.

Q41. How can you create a tuple in Python?
Ans41. We can create tuple using round brackets ().

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.
ans) Ans42. No, I can't as tuples are immutable. The work around is it typecast tuple to list and then append.
tup = ()
tup = list(tup)
tup.append("Venkata")
tup = tuple(tup)
tup

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?
Ans43.Yes, we can.

tup1 = ("Venkata ")
tup2 = ("Sai")
tup1+tup2

Q44. Take a tuple as an input and print the count of elements in it.
Ans44.

x = input("Enter the values separeted by space: ").split(" ")
x = tuple(x)
print(len(x))

Q45. What are sets in Python?
Ans45. A set is an unordered collection of data types that is iterable, mutable and has no duplicate elements. The order of elements in a set is undefined though it may consist of various elements.

Q46. How can you create a set?
Ans46. We can create set using curly brackets {}. Keep in mind empty {} will result in dictionary hence there must be some value in the brackets.

Q47. Create a set and add "iNeuron" in your set.
Ans47.

set1 = {"iNeuron"}
set1

Q48. Try to add multiple values using add() function.
Ans48.

set1.add("Big")
set1.add("Data")
set1

Q49. How is update() different from add()?
Ans49. We can add more than one element in a single go using update(), but using add() it's not possible.

Q50. What is clear() in sets?
Ans50. To remove all the elements from the set, clear() function is used.

Q51. What is frozen set?
Ans51. Frozen sets in Python are immutable objects that only support methods and operators that produce a result without affecting the frozen set or sets to which they are applied. While elements of a set can be modified at any time, elements of the frozen set remain the same after creation.

Q52. How is frozen set different from set?
Ans52.

--Frozen sets are immutable where as sets are mutable.
--Sets can't be used as keys in dictionary where as frozen sets can be used.

Q53. What is union() in sets? Explain via code.
Ans53. Python set Union() Method returns a new set which contains all the items from the original set.

set1 = {2, 4, 5, 6}
set2 = {4, 6, 7, 8}
set3 = {7, 8, 9, 10}

print("set1 U set2 : ", set1 | set2)

print("set1 U set2 U set3 :", set1 |set2 | set3)

Q54. What is intersection() in sets? Explain via code.
Ans54. Python set intersection() method returns a new set with an element that is common to all set

set1 = {2, 4, 5, 6}
set2 = {4, 6, 7, 8}
set3 = {4, 6, 8}

print("set1 intersection set2 : ", set1.intersection(set2))

print("set1 intersection set2 intersection set3 :", set1.intersection(set2, set3))

Q55. What is dictionary ibn Python?
Ans55. Dictionary in Python is a collection of keys values, used to store data values like a map, which, unlike other data types which hold only a single value as an element.

Q56. How is dictionary different from all other data structures.
Ans56. Dictionary is having key and value pair where as all other data structures have only values in them.

Q57. How can we delare a dictionary in Python?
Ans57. We can create dictionary using curly brackets {}.

Q58. What will the output of the following?
var = {}
print(type(var))

ans) dict

Q59. How can we add an element in a dictionary?
Ans59.

Dict = {}
Dict[0] = "Hello"
Dict[1] = "Course: ["Data Science", "Big Data"]"

Q60. Create a dictionary and access all the values in that dictionary.
Ans60.

Dict = {"Name": "Vishal", "Experience": 3, "Organisation":"iNeuron"}
for i, j in Dict.items():
  print(f"Key is {i} and value is {j}")

Q61. Create a nested dictionary and access all the element in the inner dictionary.
Ans61.

Dict = {"Name": {"f_name":"Vishal", "l_name":"Singh"}, "Experience": 3, "Organisation":"iNeuron"}
for i, j in Dict["Name"].items():
  print(f"Key is {i} and value is {j}")

Q62. What is the use of get() function?
Ans62. get() is also to access the elements in dictionary.
Dict = {"Name": "Venkata", "Experience": 0, "Organisation":"iNeuron"}
print(Dict.get("Name"))

Q63. What is the use of items() function?
Ans63. items() method is used to return the list with all dictionary keys with values.

Q64. What is the use of pop() function?
ans ) it deletes the last value in list or dict 

Q65. What is the use of popitems() function?
Ans65. popitem() method removes the last inserted key-value pair from the dictionary and returns it as a tuple.

Q66. What is the use of keys() function?
Ans66. keys() method returns a view object that displays a list of all the keys in the dictionary.

Q67. What is the use of values() function?
Ans67. values() is an inbuilt method in Python programming language that returns a view object. The view object contains the values of the dictionary, as a list.

Q68. What are loops in Python?
Ans68. Loops are used the iterate over a block of statement multiple times

Q69. How many type of loop are there in Python?
ans) for and while loops 

Q70. What is the difference between for and while loops?
Ans70. When we know the exact number of iterations, we can use for loop. When we want the to run till a certain condition is true we can use while loop.

Q71. What is the use of continue statement?
Ans71. Continue Statement skips the execution of the program block from after the continue statement and forces the control to start the next iteration.

Q72. What is the use of break statement?
Ans72. break statement in Python is used to bring the control out of the loop when some external condition is triggered. break statement is put inside the loop body

Q73. What is the use of pass statement?
Ans73. The pass statement is a null statement. But the difference between pass and comment is that comment is ignored by the interpreter whereas pass is not ignored.

Q74. What is the use of range() function?
Ans74. range() function returns a sequence of numbers, in a given range. The most common use of it is to iterate sequence on a sequence of numbers

Q75. How can you loop over a dictionary?
Ans75.

statesAndCapitals = {
	'Gujarat': 'Gandhinagar',
	'Maharashtra': 'Mumbai',
	'Rajasthan': 'Jaipur',
	'Bihar': 'Patna'
}

for state in statesAndCapitals:
	print(state)


Coding problems
Q76. Write a Python program to find the factorial of a given number.

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (PRT)/100

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.

Q79. Write a Python program to check if a number is prime or not.

Q80. Write a Python program to check Armstrong Number.

Q81. Write a Python program to find the n-th Fibonacci Number.

Q82. Write a Python program to interchange the first and last element in a list.

Q83. Write a Python program to swap two elements in a list.

Q84. Write a Python program to find N largest element from a list.

Q85. Write a Python program to find cumulative sum of a list.

Q86. Write a Python program to check if a string is palindrome or not.

Q87. Write a Python program to remove i'th element from a string.

Q88. Write a Python program to check if a substring is present in a given string.

Q89. Write a Python program to find words which are greater than given length k.

Q90. Write a Python program to extract unquire dictionary values.

Q91. Write a Python program to merge two dictionary.

Q92. Write a Python program to convert a list of tuples into dictionary.

Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.

Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
Q94. Write a Python program to get all combinations of 2 tuples.

Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
Q95. Write a Python program to sort a list of tuples by second item.

Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
Q96. Write a python program to print below pattern.

* 
* * 
* * * 
* * * * 
* * * * * 
Q97. Write a python program to print below pattern.

    *
   **
  ***
 ****
*****
Q98. Write a python program to print below pattern.

    * 
   * * 
  * * * 
 * * * * 
* * * * * 
Q99. Write a python program to print below pattern.

1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
Q100. Write a python program to print below pattern.

A 
B B 
C C C 
D D D D 
E E E E E 

