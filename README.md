# Hackerrank-python-
This repository all the questions i solved on Hackerrank in my python practice
Question 1- 
Task
Given an integer, , perform the following conditional actions:
If  is odd, print Weird
If  is even and in the inclusive range of  to , print Not Weird
If  is even and in the inclusive range of  to , print Weird
If  is even and greater than , print Not Weird

Solution -
n = int(input().strip())
if n % 2 == 1:
    print("Weird")
elif n % 2 == 0 and 2 <= n <= 5:
    print("Not Weird")
elif n % 2 == 0 and 6 <= n <= 20:
    print("Weird")
elif n % 2 == 0 and n > 20:
    print("Not Weird")


Question 2-
Task
The provided code stub reads two integers from STDIN,  and . Add code to print three lines where:
The first line contains the sum of the two numbers.
The second line contains the difference of the two numbers (first - second).
The third line contains the product of the two numbers.
Solution-
a = int(input().strip())
b = int(input().strip())
print(a+b) #sum of two numberes
print(a-b) #difference of two numbers
print(a*b) #product of two numbers


Question 3-
Task
The provided code stub reads two integers,  and , from STDIN.
Add logic to print two lines. The first line should contain the result of integer division,  // . The second line should contain the result of float division,  / .
No rounding or formatting is necessary.
Solution-
a = int(input().strip())
b = int(input().strip())
print(a//b)
print(a/b)


Question 4-
Task
The provided code stub reads and integer, , from STDIN. For all non-negative integers i<n , print i^2
Solution - 
n = int(input().strip())
for i in range (n) :
    print( i**2)


Question 5- 
Given a year, determine whether it is a leap year. If it is a leap year, return the Boolean True, otherwise return False.
Note that the code stub provided reads from STDIN and passes arguments to the is_leap function. It is only necessary to complete the is_leap function.
Input Format
Read year,  the year to test.
Solution-
def is_leap(year):
    if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
        return True
    else:
        return False
  year = int(input())
print(is_leap(year))


Question 6-The included code stub will read an integer, , from STDIN.
Without using any string methods, try to print the following: 123...n
Note that "" represents the consecutive values in between.
Solution- if __name__ == '__main__':
    n = int(input())
    for i in range(1, n + 1):
        print(i, end="")


Question 7-  
