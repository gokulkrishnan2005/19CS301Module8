# 19CS301Module8
EXPTNO.8a Program to find Find the simple interest

### Aim:
To Write a python program to read the marks of three subjects from the users and calculate the total and percentage for that particular student.

###Algorithm

STEP 1: Start.

STEP 2: Define a function.

STEP 3: Create variable 'm1','m2','m3' for marks. 
STEP 4: Get the input of m1,m2 and m3 from user.

STEP 5 : Using the formula (m1+m2+m3)/3 calculate the result. 

STEP 6: Print the result.

STEP 7: Stop.

### Program:
```
m1,m2,m3=int(input()),int(input()),int(input())
total=m1+m2+m3;
percentage=(total/300)*100
print("Total marks obtained is {} and the percentage obtained is {}".format(total,percentage))
```
### Output:
![image](https://github.com/gokulkrishnan2005/19CS301Module8/blob/main/26.png)


### Result: 
Thus, the given program is implemented and executed successfully .

EXPTNo.8b program to display elements from a list, present at odd index positions

### Aim:
To Write a python program to display elements from a list, present at odd index positions
### Algorithm:

STEP 1: Start.

STEP 2: Define a function.

STEP 3: Create a list and a variable a.

STEP 4: Get the input of a from user.

STEP 5 : Using loop get the inputs and append in list.

STEP 6: Using another loop print the elements in the odd index position of the list. 

STEP 7: Stop.

### Program:
```
def odd(a):
         l=[]
          for i in range(a):
x = int(input())
l.append(x)
for i in range(a):
           if i%2!=0:
                print(l[i], end=" ")
 a = int(input())
odd(a)
```
### Output:
![image](https://github.com/user-attachments/assets/a13fba7c-36b5-4227-98c1-82ab22a7804a)

### Result:
Thus, the given program is implemented and executed successfully .
 

EXPT NO>8C To Write a python program to Given the participants'	score sheet for your University Sports Day, you are required to find the runner-up score
### Aim: 
To Write a python program to Given the participants' score sheet for your University Sports Day, you are required to find the runner-up score. You are given scores. Store them 
         in a list and find the score of the runner-up.


### Algorithm:
STEP 1: Start.

STEP 2: Create a variable n.

STEP 3: Get the value of n from user.

STEP 4: Get the number of inputs from user and split the input and append in a list. STEP 5: Using set function remove duplicates from the list.

STEP 6: Using sort function reorder the list in ascending order. STEP 7: Print the result.

STEP 8: Stop.


### Program:
```if  name	== '   main    ':
          n = int(input())
          arr = map(int, input().split())
          arr2 = list(set(arr))
          arr2.sort()
print(arr2[-2])
```

### Output:
 
![image](https://github.com/user-attachments/assets/032939c0-f500-4bbb-9b19-87b3c54d8454)

 

### Result:
Thus, the given program is implemented and executed successfully .
 


EX: 8.d program to square all the even numbers and cube all odd numbers from a list of integers
### Aim: 
To Develop a python program to square all the even numbers and cube all odd numbers from a list of integers. Get the starting and ending range to create a list.


### Algorithm:

STEP 1: Start.

STEP 2: Create a variable f and l for upper and lower limit of list. STEP 3: Get the value of f and l from user.

STEP 4: Create a list.

STEP 5 : Get the input from user and append in the list. STEP 6: Create a lambda function to calculate the result. STEP 7: Print the result.

STEP 8 : Stop.

### Program:
```
cube = lambda x: x**2 if x%2==0 else x**3
def fun(f,l):
     l1=[]
     for i in range(f,l+1):
           l1.append(i)
      return l1
f,l = int(input()),int(input())

```
### Output:
![image](https://github.com/user-attachments/assets/4a9076d8-a2cf-44e1-b7d1-e638b7edf12f)



### Result: Thus, the given program is implemented and executed successfully .

EXPTNO.8e Program to find out whether given is a valid regex or not.
### Aim:
To Write a python program to  find out whether given is a valid regex or not.

###Algorithm

Takes an integer input n — number of regex patterns to check.

For each input line, it checks whether the string is a valid regular expression.

If it can be compiled using re.compile(), it prints "True".

If it's invalid, it raises a re.error, and prints "False".


### Program:
```
import re
n=int(input())
for i in range(n):
    s=input()
    try:
        p=re.compile(s)
        if p:
            print("True")
    except re.error:
        print("False")
```
### Output:
![image](https://github.com/gokulkrishnan2005/19CS301Module8/blob/main/module8%20ka%20image.png)


### Result:
Thus, the given program is implemented and executed successfully .
 


