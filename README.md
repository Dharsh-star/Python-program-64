# Python-program-64
Python program to find the sum of the digits of an integer using while loop
sum = 0
number = int(input("Enter an integer: "))
while(number!=0):
    digit = number%10
    sum = sum+digit
    number = number//10
print("Sum of digits is: ", sum)

Enter an integer: 1234
Sum of digits is:  10
