# CONDITIONAL STATEMENTS:divisible by both 11 and 3 or not

## Aim:
To write a Python program that reads a number from the user and checks whether the number is divisible by both 11 and 3, without using conditional statements such as if or else.

## Algorithm:
1.Start

2.Input a number from the user and store it in variable n

3.Check if n is divisible by both 11 and 3:

4.Compute n % 11

5.Compute n % 3

6.Use Boolean logic to determine the message:

7.If both remainders are 0, print: "n is divisible by both 11 and 3"

8.Otherwise, print: "n is NOT divisible by both 11 and 3"

9.Achieve this using string multiplication by Boolean expressions, not conditional statements

10.End

## Program:
```
n=int(input())
if n%11==0 and n%4==0:
    print(n,"is divisible by both 11 and 4")
else:
    print(n,"is NOT divisible by both 11 and 4")
```
## Output:

![image](https://github.com/user-attachments/assets/4c2cd309-8a60-494e-aed1-688c5bd8be60)

## Result:

Thus, the python program was executed successfully
