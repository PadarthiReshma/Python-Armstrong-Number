# Python-Armstrong-Number
# Apporach-1
# to check whether the given number is armstrong or not
# without using power function
n = 153 
s = n 
b = len(str(n))
sum1 = 0
while n != 0:
	r = n % 10
	sum1 = sum1+(r**b)
	n = n//10
if s == sum1:
	print("The given number", s, "is armstrong number")
else:
	print("The given number", s, "is not armstrong number")

# Apporach-2 

# Python program to check if the number is an Armstrong number or not
# take input from the user
num = int(input("Enter a number: "))
# initialize sum
sum = 0
# find the sum of the cube of each digit
temp = num
while temp > 0:
   digit = temp % 10
   sum += digit ** 3
   temp //= 10
# display the result
if num == sum:
   print(num,"is an Armstrong number")
else:
   print(num,"is not an Armstrong number")

 # Apporach-3
 
 # input is taken from the user
number = int(input("Please input a number "))
# Variable result is initialized
result = 0
# cube of each digit is added to find the sum
temporary = number
while temporary > 0:
	  digit = temporary % 10
	  result += digit ** 3
	  temporary //= 10
# result is displayed
if number == result:
	  print(number," - an Armstrong number")
else:
	  print(number," - not an Armstrong number")


