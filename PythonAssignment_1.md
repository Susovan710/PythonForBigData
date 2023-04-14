<<<<<<< HEAD
## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

As python is not specialized for any specific problems , it is broadly applicable across application domains and lacks specialized features for particular domain, we call python as general purpose language.
Python is easily readable by humans , so it is high-level programming language.


Q2. Why is Python called a dynamically typed language?

In python we don't need to declare the type of variable . In dynamically typed language, type checking takes place at runtime or execution. This is why python called a dynamically typed language.

Q3. List some pros and cons of Python programming language?

Pros:
	i. It is free, open-source and vibrant communities
	ii. Easy to understand
	iii. Portable programming language
	iv. Vast collection of libraries
	

Cons:
	i. Python is slow as it executes code line by line and compared to other programming language such as C, C++.
	ii. Consumes lot of memory space to carry out all the features that made you chose it.
    iii. Not strong for mobile computing due to the low rate of processing programs.

Q4. In what all domains can we use Python?

    i.  Data Science
    ii. Automation
    iii. Application Developmnet
    iv. AI & ML

Q5. What are variable and how can we declare them?

Python variabl is a name given to a memory location. It is "dynamically typed", means we don't need to declare variables before using them or declare their type.
A variable is created at the moment when we first assign a value to it. There are few rules for variable names as below:
    i. It must start with a letter or the underscore character.
    ii. cannot start with a number.
    iii. can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ ).
    iv. case-sensitive
    v. The reserved words(keywords) in Python cannot be used to name the variable in Python.
Example of variable assignment:
geeks = 1

Q6. How can we take an input from the user in Python?

This can be done using input() method as below:
username = input("Enter username:")
 
Q7. What is the default datatype of the value that has been taken as an input using input() function?

The default datatype of the value is string that has been taken as an input using input() function.

Q8. What is type casting?

The conversion of one data type into the other data type is known as type casting in python or type conversion in python.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Yes.
    i. using split():-
#We need to take different inputs by giving a space
a,b,c = input().split(" ")
print("input 1:",a,"\ninput 2:",b,"\ninput 3",c)

    ii. there are other ways to take multiple inputs such as: using list comprehension, loop

Q10. What are keywords?

Python keywords are special reserved words that have specific meanings and purposes and can't be used for anything (variable name, function name, or any other identifier) but those specific purposes. These keywords are always available,it doesn't require to import them into your code. Example: break, False, elif, del etc.

Q11. Can we use keywords as a variable? Support your answer with reason.

Keywords define the language's syntax rules and structure, hence it has a specific purpose. So, they cannot be used as variable names which are used for their own purpose. 

Q12. What is indentation? What's the use of indentaion in Python?

Indentation refers to adding white space before a statement to a particular block of code. Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important. 
Python uses indentation to indicate a block of code.

Q13. How can we throw some output in Python?

Using print()

Q14. What are operators in Python?

In Python, operators are special symbols that designate that some sort of computation should be performed. The values that an operator acts on are called operands.
    i. Arithmetic operators
    ii.Comparison Operators
    iii. Logical Operators
    iv. Bitwise Operators
    v. Assignment Operators

Q15. What is difference between / and // operators?

/ returns float data type
// retrutns integer data type

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
print("iNeuron"*3)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

num = int(input("Enter the number"))
if num%2==0:
  print("Even")
else:
  print("Odd")

Q18. What are boolean operator?

True , False , not , and , or

Q19. What will the output of the following?
```
1 or 0
1

0 and 0
0

True and False and True
False

1 or 0 or 0
1
```

Q20. What are conditional statements in Python?

Python has 3 key Conditional Statements : if statement. if-else statement. if-elif-else ladder

Q21. What is use of 'if', 'elif' and 'else' keywords?

The if statement is a conditional statement in python. If the program finds the condition defined in the if statement to be true, it will go ahead and execute the code block inside the if statement.
Similarly, the else statement works in conjuncture with the if statement to execute a code block when the defined if condition is false.
The elif statement is used to check for multiple conditions and execute the code block within if any of the conditions evaluate to be true.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

age = int(input())
if age>=18:
  print("I can vote")
else:
  print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
from functools import reduce

numbers = [12, 75, 150, 180, 145, 525, 50]
even_list = list(filter(lambda x: (x % 2== 0), numbers))
result = reduce(lambda x,y: x + y, final_list)
print(result)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

from functools import reduce

n = [float(num) for num in input().split()]
result = reduce(lambda x,y: x if x>y else y, n)
print(result)

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
numbers = [12, 75, 150, 180, 145, 525, 50]

for i in numbers:
  if i>500:
    break
  elif i%5==0 and i<=150:
    print(i)


Q26. What is a string? How can we declare string in Python?

A string is a data structure in Python that stores a sequence of elements, typically characters, using some character encoding.Strings in python are surrounded by either single quotation marks, or double quotation marks.

a = "Hello"
print(a)

Q27. How can we access the string using its index?

a = "Hello"
print(a[0])

Q28. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "iNeuron"
```
string = "Big Data iNeuron"
print(string[9:])

Q29. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "norueNi"
```
string = "Big Data iNeuron"
print(string[:8:-1])

Q30. Resverse the string given in the above question.

string = "Big Data iNeuron"
print(string[::-1])

Q31. How can you delete entire string at once?

del string

Q32. What is escape sequence?

An escape sequence is a sequence of characters that, when used inside a character or string, does not represent itself but is converted into another character or series of characters. 
Example: \n	will convert to newline

Q33. How can you print the below string?
```
'iNeuron's Big Data Course'
```
print('iNeuron\'s Big Data Course')

Q34. What is a list in Python?

A list is an ordered data structure with elements separated by a comma and enclosed within square brackets.
Example: list1 = [1,2,4]

Q35. How can you create a list in Python?

list1 = [1,2,4]

Q36. How can we access the elements in a list?

using the index as below:
list1[0]

Q37. Write a code to access the word "iNeuron" from the given list.
```
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
``` 
lst[4][2]

Q38. Take a list as an input from the user and find the length of the list.

n = input().split()
print(len(n))

Q39. Add the word "Big" in the 3rd index of the given list.
```
lst = ["Welcome", "to", "Data", "course"]
```
lst.insert(2, "Big")

Q40. What is a tuple? How is it different from list?

Python Tuple is a collection of objects separated by commas. In some ways, a tuple is similar to a list in terms of indexing, nested objects, and repetition but a tuple is immutable, unlike lists which are mutable.

Q41. How can you create a tuple in Python?

tuple1 = (0, 1, 2, 3)

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.

As tuples are immutable , we can not add element into the same instance. However, in a new instance we can add the new element (name).

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?

No. Because tuple is immutable.

Q44. Take a tuple as an input and print the count of elements in it.

n = tuple(input().split())
print(len(n))

Q45. What are sets in Python?

A Set in Python programming is an unordered collection data type that is iterable, mutable and has no duplicate elements. 

Q46. How can you create a set?

my_set = {1,3,5,6}

Q47. Create a set and add "iNeuron" in your set.

my_set = {1,3,5,6}
my_set.add("iNeuron")

Q48. Try to add multiple values using add() function.

my_set = {1,3,5,6}
my_set.add("iNeuron")
my_set.add(10)

Q49. How is update() different from add()?

We can add more than one element in a single go using update(), but using add() it's not possible.

Q50. What is clear() in sets?

To remove all the elements from the set, clear() function is used.

Q51. What is frozen set?

Frozen sets in Python are immutable objects that only support methods and operators that produce a result without affecting the frozen set or sets to which they are applied. It can be done with frozenset() method in Python.

Q52. How is frozen set different from set?

In normat set , we can add elements whereas in frozen set we can not.

Q53. What is union() in sets? Explain via code.

Return a set that contains all items from both sets, duplicates are excluded:

code:
x = {"apple", "banana", "cherry"}
y = {"google", "microsoft", "apple"}

z = x.union(y)

print(z)

output:
{'banana', 'apple', 'microsoft', 'google', 'cherry'}

Q54. What is intersection() in sets? Explain via code.

Return a set that contains the items that exist in both set x, and set y:
code:
x = {"apple", "banana", "cherry"}
y = {"google", "microsoft", "apple"}

z = x.intersection(y)

print(z)

output:
{'apple'}

Q55. What is dictionary in Python?

Dictionaries are used to store data values in key:value pairs.

A dictionary is a collection which is ordered (from python 3.7), changeable and do not allow duplicates.

Q56. How is dictionary different from all other data structures.

Dictionary items are presented in key:value pairs, and can be referred to by using the key name.

Q57. How can we delare a dictionary in Python?

thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
print(thisdict)

Q58. What will the output of the following?
```
var = {}
print(type(var))
```

dict

Q59. How can we add an element in a dictionary?

d_obj.add(key, value)

Q60. Create a dictionary and access all the values in that dictionary.

thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
x = thisdict["model"]

Q61. Create a nested dictionary and access all the element in the inner dictionary.

myfamily = {
  "child1" : {
    "name" : "Emil",
    "year" : 2004
  },
  "child2" : {
    "name" : "Tobias",
    "year" : 2007
  },
  "child3" : {
    "name" : "Linus",
    "year" : 2011
  }
}
myfamily["child1"]

Q62. What is the use of get() function?

The get() method in Python is used to fetch the value of a key from a dictionary. 
ex: dict.get("key")

Q63. What is the use of items() function?

The items () method in the dictionary is used to return each item in a dictionary as tuples in a list.
ex: dict.items()

Q64. What is the use of pop() function?

The pop() method removes the element at the specified position.
Ex:
fruits = ['apple', 'banana', 'cherry']
fruits.pop(1)

Q65. What is the use of popitems() function?

The popitem() method removes the item that was last inserted into the dictionary. In versions before 3.7, the popitem() method removes a random item.
The removed item is the return value of the popitem() method, as a tuple.
Ex:
car = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
car.popitem()
print(car)

Q66. What is the use of keys() function?

The keys() method returns a view object. The view object contains the keys of the dictionary, as a list.
Syntax: dictionary.keys()

Q67. What is the use of values() function?

values() is an inbuilt method in Python programming language that returns a view object. The view object contains the values of the dictionary, as a list.
Syntax: dictionary_name.values()

Q68. What are loops in Python?

A loop statement allows us to execute a statement or group of statements multiple times. 

Q69. How many type of loop are there in Python?

2 types of loop.
  i. for loop
  ii. while loop

Q70. What is the difference between for and while loops?

	1. For loop  --------- When number of iteration is known
	2. While loop ---------- when number of iteration is unknown

Q71. What is the use of continue statement?

It used to ignore the current execution and gives control to the next iteration

Q72. What is the use of break statement?

used to break the statement or the loop to avoid further execution.

Q73. What is the use of pass statement?

The pass statement is used as a placeholder for future code. When the pass statement is executed, nothing happens, but you avoid getting an error when empty code is not allowed.

Q74. What is the use of range() function?

The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and stops before a specified number.
Syntax: range(start, stop, step)

Q75. How can you loop over a dictionary?

statesAndCapitals = {
	'Gujarat': 'Gandhinagar',
	'Maharashtra': 'Mumbai',
	'Rajasthan': 'Jaipur',
	'Bihar': 'Patna'
}

for state,city in statesAndCapitals.items():
	print("state--", state,"\ncity--", city)

### Coding problems
Q76. Write a Python program to find the factorial of a given number.

x = lambda num : 1 if num <= 1 else num*x(num-1)
number = int(input('Enter number: '))
print(x(number))

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (P*R*T)/100

 si = lambda p, r, t : (p * r * t) / 100
 print(si(8,8,6))

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.

def CI(p, r, t):
  amount = p*((1+r/100)**t)
  ci = amount - p
  print(f"Compound intrest is {ci}")
  return ci

CI(10000, 10.25, 5)

Q79. Write a Python program to check if a number is prime or not.

num = int(input("Enter a number: "))

flag = False

if num == 1:
    print(num, "is not a prime number")
elif num > 1:
    for i in range(2, num):
        if (num % i) == 0:
            # if factor is found, set flag to True
            flag = True
            break

    if flag:
        print(num, "is not a prime number")
    else:
        print(num, "is a prime number")

Q80. Write a Python program to check Armstrong Number.

num = int(input("Enter a number: "))
sum = 0
temp = num
while temp > 0:
   digit = temp % 10
   sum += digit ** 3
   temp //= 10

if num == sum:
   print(num,"is an Armstrong number")
else:
   print(num,"is not an Armstrong number")

Q81. Write a Python program to find the n-th Fibonacci Number.

num = int(input("Enter a number: "))
lis = [0,1]
for i in range(2,num):
  temp = lis[i-1] + lis[i-2]
  lis.append(temp)

fib = lambda x: lis[num-1] if num>2 else (1 if num==2 else 0)
print(fib(num))

Q82. Write a Python program to interchange the first and last element in a list.

def swap_list(newList):
     
    newList[0], newList[-1] = newList[-1], newList[0]
 
    return newList
     
newList = [15, 12, 35, 17, 9, 56, 29]
print(swap_list(newList))

Q83. Write a Python program to swap two elements in a list.

def swap_list(li, pos1, pos2):
     
    li[pos1], li[pos2] = li[pos2], li[pos1]
 
    return li
     
newList = [15, 12, 35, 17, 9, 56, 29]
print(swap_list(newList, 0 , 1))

Q84. Write a Python program to find N largest element from a list.

newList = [15, 12, 35, 17, 9, 56, 29]
newList.sort(reverse=True)
N =3
for i in range(N):
  print(newList[i])

Q85. Write a Python program to find cumulative sum of a list.

import functools
list_x = [1,2,3,4,5]
add_two_nums = lambda x , y : x + y
result = functools.reduce(add_two_nums , list_x)
print(result)

Q86. Write a Python program to check if a string is palindrome or not.

s = input("Enter string value")
s = s.lower()
pal = lambda x: "Palindrome" if s == s[::-1] else "Not Palindrome"
print(pal(s))

Q87. Write a Python program to remove i'th element from a string.

test_str = "imNeuron"
pos = 2 
new_str = lambda x: test_str[:(x-1)] + test_str[x:] 
print ("The string after removal of i'th character : " + new_str(pos))

Q88. Write a Python program to check if a substring is present in a given string.

s = "Welcome to iNeuron Big Data Bootcamp"
ch = lambda s1, s2 : f'"{s1}" is a substring of "{s2}"' if s2.count(s1) > 0 else f'"{s1}" is a substring of "{s2}"'
print(ch("iNeuron", s))

Q89. Write a Python program to find words which are greater than given length k.

s = "Identify the word"
st = s.split(" ")
k =3
for i in st:
  if len(i)>k:
    print(i)

Q90. Write a Python program to extract unqique dictionary values.

test_dict = {'iNeuron': [5, 6, 7, 8],
			'is': [10, 11, 7, 5],
			'best': [6, 12, 10, 8],
			'for': [1, 2, 5],
      'big data': [2, 7, 12, 9]
      }
res = list(sorted({ele for val in test_dict.values() for ele in val}))

print("The unique values list from the dictionary is : " , res)

Q91. Write a Python program to merge two dictionary.

def Merge(dict1, dict2):
    dict2.update(dict1)
    return dict2
dict1 = {'a': 10, 'b': 8}
dict2 = {'d': 6, 'c': 4}
merged_dic = Merge(dict1, dict2)   
print(merged_dic)

Q92. Write a Python program to convert a list of tuples into dictionary.
```
Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
```
ml = [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
d = {}
for i in ml:
  d[i[0]] = i[1]
print(d)

Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.
```
Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
```
list1 =  [9, 5, 6]
tup = lambda x : (x, x**3)
res = list(map(tup, list1))
print(res)

Q94. Write a Python program to get all combinations of 2 tuples.
```
Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
```

test_tuple1 = (7, 2)
test_tuple2 = (7, 8)

res = [(a, b) for a in test_tuple1 for b in test_tuple2] + [(a, b) for a in test_tuple2 for b in test_tuple1]
print(res)

Q95. Write a Python program to sort a list of tuples by second item.
```
Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
```
def m_sort(l):
  l[0],l[1] = l[1],l[0]
  return l
s =  [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
print(m_sort(s))

Q96. Write a python program to print below pattern.
```
* 
* * 
* * * 
* * * * 
* * * * * 
```

for i in range(1,6):
  print(i*'*')

Q97. Write a python program to print below pattern.
```
    *
   **
  ***
 ****
*****
```

m = 4
for i in range(1,6):
  print((' '*m)+(i*'*'))
  m = m -1

Q98. Write a python program to print below pattern.
```
    * 
   * * 
  * * * 
 * * * * 
* * * * * 
```

m = 5
k = m-1
for i in range(1,6):
  print((' '*k)+(i*'* '))
  k = k -1


Q99. Write a python program to print below pattern.
```
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
```

m = 5
for i in range(1,m+1):
  k=1
  while k<=i:
    print(k,'',end="")
    k = k+1
  print("\r")

Q100. Write a python program to print below pattern.
```
A 
B B 
C C C 
D D D D 
E E E E E 
```

m =5
a_num = 65

for i in range(1, m+1):
  print((chr(a_num)+' ')*i)
  a_num = a_num+1
=======
## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

As python is not specialized for any specific problems , it is broadly applicable across application domains and lacks specialized features for particular domain, we call python as general purpose language.
Python is easily readable by humans , so it is high-level programming language.


Q2. Why is Python called a dynamically typed language?

In python we don't need to declare the type of variable . In dynamically typed language, type checking takes place at runtime or execution. This is why python called a dynamically typed language.

Q3. List some pros and cons of Python programming language?

Pros:
	i. It is free, open-source and vibrant communities
	ii. Easy to understand
	iii. Portable programming language
	iv. Vast collection of libraries
	

Cons:
	i. Python is slow as it executes code line by line and compared to other programming language such as C, C++.
	ii. Consumes lot of memory space to carry out all the features that made you chose it.
    iii. Not strong for mobile computing due to the low rate of processing programs.

Q4. In what all domains can we use Python?

    i.  Data Science
    ii. Automation
    iii. Application Developmnet
    iv. AI & ML

Q5. What are variable and how can we declare them?

Python variabl is a name given to a memory location. It is "dynamically typed", means we don't need to declare variables before using them or declare their type.
A variable is created at the moment when we first assign a value to it. There are few rules for variable names as below:
    i. It must start with a letter or the underscore character.
    ii. cannot start with a number.
    iii. can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ ).
    iv. case-sensitive
    v. The reserved words(keywords) in Python cannot be used to name the variable in Python.
Example of variable assignment:
geeks = 1

Q6. How can we take an input from the user in Python?

This can be done using input() method as below:
username = input("Enter username:")
 
Q7. What is the default datatype of the value that has been taken as an input using input() function?

The default datatype of the value is string that has been taken as an input using input() function.

Q8. What is type casting?

The conversion of one data type into the other data type is known as type casting in python or type conversion in python.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Yes.
    i. using split():-
#We need to take different inputs by giving a space
a,b,c = input().split(" ")
print("input 1:",a,"\ninput 2:",b,"\ninput 3",c)

    ii. there are other ways to take multiple inputs such as: using list comprehension, loop

Q10. What are keywords?

Python keywords are special reserved words that have specific meanings and purposes and can't be used for anything (variable name, function name, or any other identifier) but those specific purposes. These keywords are always available,it doesn't require to import them into your code. Example: break, False, elif, del etc.

Q11. Can we use keywords as a variable? Support your answer with reason.

Keywords define the language's syntax rules and structure, hence it has a specific purpose. So, they cannot be used as variable names which are used for their own purpose. 

Q12. What is indentation? What's the use of indentaion in Python?

Indentation refers to adding white space before a statement to a particular block of code. Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important. 
Python uses indentation to indicate a block of code.

Q13. How can we throw some output in Python?

Using print()

Q14. What are operators in Python?

In Python, operators are special symbols that designate that some sort of computation should be performed. The values that an operator acts on are called operands.
    i. Arithmetic operators
    ii.Comparison Operators
    iii. Logical Operators
    iv. Bitwise Operators
    v. Assignment Operators

Q15. What is difference between / and // operators?

/ returns float data type
// retrutns integer data type

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
print("iNeuron"*3)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

num = int(input("Enter the number"))
if num%2==0:
  print("Even")
else:
  print("Odd")

Q18. What are boolean operator?

True , False , not , and , or

Q19. What will the output of the following?
```
1 or 0
1

0 and 0
0

True and False and True
False

1 or 0 or 0
1
```

Q20. What are conditional statements in Python?

Python has 3 key Conditional Statements : if statement. if-else statement. if-elif-else ladder

Q21. What is use of 'if', 'elif' and 'else' keywords?

The if statement is a conditional statement in python. If the program finds the condition defined in the if statement to be true, it will go ahead and execute the code block inside the if statement.
Similarly, the else statement works in conjuncture with the if statement to execute a code block when the defined if condition is false.
The elif statement is used to check for multiple conditions and execute the code block within if any of the conditions evaluate to be true.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

age = int(input())
if age>=18:
  print("I can vote")
else:
  print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
from functools import reduce

numbers = [12, 75, 150, 180, 145, 525, 50]
even_list = list(filter(lambda x: (x % 2== 0), numbers))
result = reduce(lambda x,y: x + y, final_list)
print(result)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

from functools import reduce

n = [float(num) for num in input().split()]
result = reduce(lambda x,y: x if x>y else y, n)
print(result)

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
numbers = [12, 75, 150, 180, 145, 525, 50]

for i in numbers:
  if i>500:
    break
  elif i%5==0 and i<=150:
    print(i)


Q26. What is a string? How can we declare string in Python?

A string is a data structure in Python that stores a sequence of elements, typically characters, using some character encoding.Strings in python are surrounded by either single quotation marks, or double quotation marks.

a = "Hello"
print(a)

Q27. How can we access the string using its index?

a = "Hello"
print(a[0])

Q28. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "iNeuron"
```
string = "Big Data iNeuron"
print(string[9:])

Q29. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "norueNi"
```
string = "Big Data iNeuron"
print(string[:8:-1])

Q30. Resverse the string given in the above question.

string = "Big Data iNeuron"
print(string[::-1])

Q31. How can you delete entire string at once?

del string

Q32. What is escape sequence?

An escape sequence is a sequence of characters that, when used inside a character or string, does not represent itself but is converted into another character or series of characters. 
Example: \n	will convert to newline

Q33. How can you print the below string?
```
'iNeuron's Big Data Course'
```
print('iNeuron\'s Big Data Course')

Q34. What is a list in Python?

A list is an ordered data structure with elements separated by a comma and enclosed within square brackets.
Example: list1 = [1,2,4]

Q35. How can you create a list in Python?

list1 = [1,2,4]

Q36. How can we access the elements in a list?

using the index as below:
list1[0]

Q37. Write a code to access the word "iNeuron" from the given list.
```
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
``` 
lst[4][2]

Q38. Take a list as an input from the user and find the length of the list.

n = input().split()
print(len(n))

Q39. Add the word "Big" in the 3rd index of the given list.
```
lst = ["Welcome", "to", "Data", "course"]
```
lst.insert(2, "Big")

Q40. What is a tuple? How is it different from list?

Python Tuple is a collection of objects separated by commas. In some ways, a tuple is similar to a list in terms of indexing, nested objects, and repetition but a tuple is immutable, unlike lists which are mutable.

Q41. How can you create a tuple in Python?

tuple1 = (0, 1, 2, 3)

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.

As tuples are immutable , we can not add element into the same instance. However, in a new instance we can add the new element (name).

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?

No. Because tuple is immutable.

Q44. Take a tuple as an input and print the count of elements in it.

n = tuple(input().split())
print(len(n))

Q45. What are sets in Python?

A Set in Python programming is an unordered collection data type that is iterable, mutable and has no duplicate elements. 

Q46. How can you create a set?

my_set = {1,3,5,6}

Q47. Create a set and add "iNeuron" in your set.

my_set = {1,3,5,6}
my_set.add("iNeuron")

Q48. Try to add multiple values using add() function.

my_set = {1,3,5,6}
my_set.add("iNeuron")
my_set.add(10)

Q49. How is update() different from add()?

We can add more than one element in a single go using update(), but using add() it's not possible.

Q50. What is clear() in sets?

To remove all the elements from the set, clear() function is used.

Q51. What is frozen set?

Frozen sets in Python are immutable objects that only support methods and operators that produce a result without affecting the frozen set or sets to which they are applied. It can be done with frozenset() method in Python.

Q52. How is frozen set different from set?

In normat set , we can add elements whereas in frozen set we can not.

Q53. What is union() in sets? Explain via code.

Return a set that contains all items from both sets, duplicates are excluded:

code:
x = {"apple", "banana", "cherry"}
y = {"google", "microsoft", "apple"}

z = x.union(y)

print(z)

output:
{'banana', 'apple', 'microsoft', 'google', 'cherry'}

Q54. What is intersection() in sets? Explain via code.

Return a set that contains the items that exist in both set x, and set y:
code:
x = {"apple", "banana", "cherry"}
y = {"google", "microsoft", "apple"}

z = x.intersection(y)

print(z)

output:
{'apple'}

Q55. What is dictionary in Python?

Dictionaries are used to store data values in key:value pairs.

A dictionary is a collection which is ordered (from python 3.7), changeable and do not allow duplicates.

Q56. How is dictionary different from all other data structures.

Dictionary items are presented in key:value pairs, and can be referred to by using the key name.

Q57. How can we delare a dictionary in Python?

thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
print(thisdict)

Q58. What will the output of the following?
```
var = {}
print(type(var))
```

dict

Q59. How can we add an element in a dictionary?

d_obj.add(key, value)

Q60. Create a dictionary and access all the values in that dictionary.

thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
x = thisdict["model"]

Q61. Create a nested dictionary and access all the element in the inner dictionary.

myfamily = {
  "child1" : {
    "name" : "Emil",
    "year" : 2004
  },
  "child2" : {
    "name" : "Tobias",
    "year" : 2007
  },
  "child3" : {
    "name" : "Linus",
    "year" : 2011
  }
}
myfamily["child1"]

Q62. What is the use of get() function?

The get() method in Python is used to fetch the value of a key from a dictionary. 
ex: dict.get("key")

Q63. What is the use of items() function?

The items () method in the dictionary is used to return each item in a dictionary as tuples in a list.
ex: dict.items()

Q64. What is the use of pop() function?

The pop() method removes the element at the specified position.
Ex:
fruits = ['apple', 'banana', 'cherry']
fruits.pop(1)

Q65. What is the use of popitems() function?

The popitem() method removes the item that was last inserted into the dictionary. In versions before 3.7, the popitem() method removes a random item.
The removed item is the return value of the popitem() method, as a tuple.
Ex:
car = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
car.popitem()
print(car)

Q66. What is the use of keys() function?

The keys() method returns a view object. The view object contains the keys of the dictionary, as a list.
Syntax: dictionary.keys()

Q67. What is the use of values() function?

values() is an inbuilt method in Python programming language that returns a view object. The view object contains the values of the dictionary, as a list.
Syntax: dictionary_name.values()

Q68. What are loops in Python?

A loop statement allows us to execute a statement or group of statements multiple times. 

Q69. How many type of loop are there in Python?

2 types of loop.
  i. for loop
  ii. while loop

Q70. What is the difference between for and while loops?

	1. For loop  --------- When number of iteration is known
	2. While loop ---------- when number of iteration is unknown

Q71. What is the use of continue statement?

It used to ignore the current execution and gives control to the next iteration

Q72. What is the use of break statement?

used to break the statement or the loop to avoid further execution.

Q73. What is the use of pass statement?

The pass statement is used as a placeholder for future code. When the pass statement is executed, nothing happens, but you avoid getting an error when empty code is not allowed.

Q74. What is the use of range() function?

The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and stops before a specified number.
Syntax: range(start, stop, step)

Q75. How can you loop over a dictionary?

statesAndCapitals = {
	'Gujarat': 'Gandhinagar',
	'Maharashtra': 'Mumbai',
	'Rajasthan': 'Jaipur',
	'Bihar': 'Patna'
}

for state,city in statesAndCapitals.items():
	print("state--", state,"\ncity--", city)

### Coding problems
Q76. Write a Python program to find the factorial of a given number.

x = lambda num : 1 if num <= 1 else num*x(num-1)
number = int(input('Enter number: '))
print(x(number))

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (P*R*T)/100

 si = lambda p, r, t : (p * r * t) / 100
 print(si(8,8,6))

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.

def CI(p, r, t):
  amount = p*((1+r/100)**t)
  ci = amount - p
  print(f"Compound intrest is {ci}")
  return ci

CI(10000, 10.25, 5)

Q79. Write a Python program to check if a number is prime or not.

num = int(input("Enter a number: "))

flag = False

if num == 1:
    print(num, "is not a prime number")
elif num > 1:
    for i in range(2, num):
        if (num % i) == 0:
            # if factor is found, set flag to True
            flag = True
            break

    if flag:
        print(num, "is not a prime number")
    else:
        print(num, "is a prime number")

Q80. Write a Python program to check Armstrong Number.

num = int(input("Enter a number: "))
sum = 0
temp = num
while temp > 0:
   digit = temp % 10
   sum += digit ** 3
   temp //= 10

if num == sum:
   print(num,"is an Armstrong number")
else:
   print(num,"is not an Armstrong number")

Q81. Write a Python program to find the n-th Fibonacci Number.

num = int(input("Enter a number: "))
lis = [0,1]
for i in range(2,num):
  temp = lis[i-1] + lis[i-2]
  lis.append(temp)

fib = lambda x: lis[num-1] if num>2 else (1 if num==2 else 0)
print(fib(num))

Q82. Write a Python program to interchange the first and last element in a list.

def swap_list(newList):
     
    newList[0], newList[-1] = newList[-1], newList[0]
 
    return newList
     
newList = [15, 12, 35, 17, 9, 56, 29]
print(swap_list(newList))

Q83. Write a Python program to swap two elements in a list.

def swap_list(li, pos1, pos2):
     
    li[pos1], li[pos2] = li[pos2], li[pos1]
 
    return li
     
newList = [15, 12, 35, 17, 9, 56, 29]
print(swap_list(newList, 0 , 1))

Q84. Write a Python program to find N largest element from a list.

newList = [15, 12, 35, 17, 9, 56, 29]
newList.sort(reverse=True)
N =3
for i in range(N):
  print(newList[i])

Q85. Write a Python program to find cumulative sum of a list.

import functools
list_x = [1,2,3,4,5]
add_two_nums = lambda x , y : x + y
result = functools.reduce(add_two_nums , list_x)
print(result)

Q86. Write a Python program to check if a string is palindrome or not.

s = input("Enter string value")
s = s.lower()
pal = lambda x: "Palindrome" if s == s[::-1] else "Not Palindrome"
print(pal(s))

Q87. Write a Python program to remove i'th element from a string.

test_str = "imNeuron"
pos = 2 
new_str = lambda x: test_str[:(x-1)] + test_str[x:] 
print ("The string after removal of i'th character : " + new_str(pos))

Q88. Write a Python program to check if a substring is present in a given string.

s = "Welcome to iNeuron Big Data Bootcamp"
ch = lambda s1, s2 : f'"{s1}" is a substring of "{s2}"' if s2.count(s1) > 0 else f'"{s1}" is a substring of "{s2}"'
print(ch("iNeuron", s))

Q89. Write a Python program to find words which are greater than given length k.

s = "Identify the word"
st = s.split(" ")
k =3
for i in st:
  if len(i)>k:
    print(i)

Q90. Write a Python program to extract unqique dictionary values.

test_dict = {'iNeuron': [5, 6, 7, 8],
			'is': [10, 11, 7, 5],
			'best': [6, 12, 10, 8],
			'for': [1, 2, 5],
      'big data': [2, 7, 12, 9]
      }
res = list(sorted({ele for val in test_dict.values() for ele in val}))

print("The unique values list from the dictionary is : " , res)

Q91. Write a Python program to merge two dictionary.

def Merge(dict1, dict2):
    dict2.update(dict1)
    return dict2
dict1 = {'a': 10, 'b': 8}
dict2 = {'d': 6, 'c': 4}
merged_dic = Merge(dict1, dict2)   
print(merged_dic)

Q92. Write a Python program to convert a list of tuples into dictionary.
```
Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
```
ml = [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
d = {}
for i in ml:
  d[i[0]] = i[1]
print(d)

Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.
```
Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
```
list1 =  [9, 5, 6]
tup = lambda x : (x, x**3)
res = list(map(tup, list1))
print(res)

Q94. Write a Python program to get all combinations of 2 tuples.
```
Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
```

test_tuple1 = (7, 2)
test_tuple2 = (7, 8)

res = [(a, b) for a in test_tuple1 for b in test_tuple2] + [(a, b) for a in test_tuple2 for b in test_tuple1]
print(res)

Q95. Write a Python program to sort a list of tuples by second item.
```
Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
```
def m_sort(l):
  l[0],l[1] = l[1],l[0]
  return l
s =  [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
print(m_sort(s))

Q96. Write a python program to print below pattern.
```
* 
* * 
* * * 
* * * * 
* * * * * 
```

for i in range(1,6):
  print(i*'*')

Q97. Write a python program to print below pattern.
```
    *
   **
  ***
 ****
*****
```

m = 4
for i in range(1,6):
  print((' '*m)+(i*'*'))
  m = m -1

Q98. Write a python program to print below pattern.
```
    * 
   * * 
  * * * 
 * * * * 
* * * * * 
```

m = 5
k = m-1
for i in range(1,6):
  print((' '*k)+(i*'* '))
  k = k -1


Q99. Write a python program to print below pattern.
```
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
```

m = 5
for i in range(1,m+1):
  k=1
  while k<=i:
    print(k,'',end="")
    k = k+1
  print("\r")

Q100. Write a python program to print below pattern.
```
A 
B B 
C C C 
D D D D 
E E E E E 
```

m =5
a_num = 65

for i in range(1, m+1):
  print((chr(a_num)+' ')*i)
  a_num = a_num+1
>>>>>>> cb66a86598bded77cc1764395517f8318369841b
