Everything is object
This project contains some tasks for learning about object behaviours in Python.

Tasks To Complete
 0. Who am I?
0-answer.txt contains the function I would use to print the type of an object.
 1. Where are you?
1-answer.txt contains the function I would use to get the variable identifier (which is the memory address in the CPython implementation).
 2. Right count
2-answer.txt contains the answer to if a and b point to the same object in the following code (Yes / No).
>>> a = 89
>>> b = 100
 3. Right count =
3-answer.txt contains the answer to if a and b point to the same object in the following code (Yes / No).
>>> a = 89
>>> b = 89
 4. Right count =
4-answer.txt contains the answer to if a and b point to the same object in the following code (Yes / No).
>>> a = 89
>>> b = a
 5. Right count =+
5-answer.txt contains the answer to if a and b point to the same object in the following code (Yes / No).
>>> a = 89
>>> b = a + 1
 6. Is equal
6-answer.txt contains the output of the following code.
>>> s1 = "Best School"
>>> s2 = s1
>>> print(s1 == s2)
 7. Is the same
7-answer.txt contains the output of the following code.
>>> s1 = "Best"
>>> s2 = s1
>>> print(s1 is s2)
 8. Is really equal
8-answer.txt contains the output of the following code.
>>> s1 = "Best School"
>>> s2 = "Best School"
>>> print(s1 == s2)
 9. Is really the same
9-answer.txt contains the output of the following code.
>>> s1 = "Best School"
>>> s2 = "Best School"
>>> print(s1 is s2)
 10. And with a list, is it equal
10-answer.txt contains the output of the following code.
>>> l1 = [1, 2, 3]
>>> l2 = [1, 2, 3]
>>> print(l1 == l2)
 11. And with a list, is it the same
11-answer.txt contains the output of the following code.
>>> l1 = [1, 2, 3]
>>> l2 = [1, 2, 3]
>>> print(l1 is l2)
 12. And with a list, is it really equal
12-answer.txt contains the output of the following code.
>>> l1 = [1, 2, 3]
>>> l2 = l1
>>> print(l1 == l2)
 13. And with a list, is it really the same
13-answer.txt contains the output of the following code.
>>> l1 = [1, 2, 3]
>>> l2 = l1
>>> print(l1 is l2)
 14. List append
14-answer.txt contains the output of the following code.
l1 = [1, 2, 3]
l2 = l1
l1.append(4)
print(l2)
 15. List add
15-answer.txt contains the output of the following code.
l1 = [1, 2, 3]
l2 = l1
l1 = l1 + [4]
print(l2)
 16. Integer incrementation
16-answer.txt contains the output of the following code.
def increment(n):
    n += 1

a = 1
increment(a)
print(a)
 17. List incrementation
17-answer.txt contains the output of the following code.
def increment(n):
    n.append(4)

l = [1, 2, 3]
increment(l)
print(l)
 18. List assignation
18-answer.txt contains the output of the following code.
def assign_value(n, v):
    n = v

l1 = [1, 2, 3]
l2 = [4, 5, 6]
assign_value(l1, l2)
print(l1)
 19. Copy a list object
19-copy_list.py contains a function that returns a copy of a list.
 20. Tuple or not?
20-answer.txt contains the answer to if a is a tuple or not (Yes / No).
a = ()
 21. Tuple or not?
21-answer.txt contains the answer to if a is a tuple or not (Yes / No).
a = (1, 2)
 22. Tuple or not?
22-answer.txt contains the answer to if a is a tuple or not (Yes / No).
a = (1)
 23. Tuple or not?
23-answer.txt contains the answer to if a is a tuple or not (Yes / No).
a = (1, )
 24. Who I am?
24-answer.txt contains the output of the following code.
a = (1)
b = (1)
a is b
 25. Tuple or not
25-answer.txt contains the output of the following code.
a = (1, 2)
b = (1, 2)
a is b
 26. Empty is not empty
26-answer.txt contains the output of the following code.
a = ()
b = ()
a is b
 27. Still the same?
27-answer.txt contains the answer to if the last line of the following script will print 139926795932424 (Yes / No).
>>> id(a)
139926795932424
>>> a
[1, 2, 3, 4]
>>> a = a + [5]
>>> id(a)
 28. Same or not?
28-answer.txt contains the answer to if the last line of the following script will print 139926795932424 (Yes / No).
>>> a
[1, 2, 3]
>>> id (a)
139926795932424
>>> a += [4]
>>> id(a)
 29. #pythonic
100-magic_string.py contains a function that returns a string “BestSchool” n times the number of the iteration.
 30. Low memory cost
101-locked_class.py contains a class LockedClass with no class or object attribute, that prevents the user from dynamically creating new instance attributes, except if the new instance attribute is called first_name.
 31. int 1/3
Considering the script below and assuming we are using a CPython implementation of Python3 with default options/configuration:
a = 1
b = 1
103-line1.txt Contains the answer to how many int objects are created by the execution of the first line of the script.
103-line2.txt Contains the answer to how many int objects are created by the execution of the second line of the script.
 32. int 2/3
Considering the script below and assuming we are using a CPython implementation of Python3 with default options/configuration:
a = 1024
b = 1024
del a
del b
c = 1024
104-line1.txt Contains the answer to how many int objects are created by the execution of the first line of the script.
104-line2.txt Contains the answer to how many int objects are created by the execution of the second line of the script.
104-line3.txt Contains the answer to if the int object pointed by a is deleted after the execution of line 3 in the script (Yes / No).
104-line4.txt Contains the answer to if the int object pointed by b is deleted after the execution of line 4 in the script (Yes / No).
104-line5.txt Contains the answer to how many int objects are created by the execution of the last line of the script.
 33. int 3/3
Considering the script below and assuming we are using a CPython implementation of Python3 with default options/configuration:
print("I")
print("Love")
print("Python")
105-line1.txt Contains the answer to how many int objects have been created and are still in memory before the execution of line in the script (print("Love")).
105-blog_post.md Contains the blog post of an explanation of the answer.
 34. Clear strings
Considering the script below and assuming we are using a CPython implementation of Python3 with default options/configuration:
a = "SCHL"
b = "SCHL"
del a
del b
c = "SCHL"
106-line1.txt Contains the answer to how many string objects are created by the execution of the first line of the script.
106-line2.txt Contains the answer to how many string objects are created by the execution of the second line of the script.
106-line3.txt Contains the answer to if the string object pointed by a is deleted after the execution of line 3 in the script (Yes / No).
106-line4.txt Contains the answer to if the string object pointed by b is deleted after the execution of line 4 in the script (Yes / No).
106-line5.txt Contains the answer to how many string objects are created by the execution of the last line of the script.