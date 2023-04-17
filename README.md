# Coding
Python
print("Hello World")

def recursion(product):
  if product!=0:
    product1 = product*recursion(product-1)
return product1
num = int(input())
recursion(num)
 
 Fibonacci series
 range=int(input("Enter Range":))
 a=0
 b=1
 c=a+b
 print(a,b)
 while(c<n):
  print(c)
  a=b
  b=c
  c=a+b
  
  Armstrong Number
  num = int(input("Enter a number"))
  sum=0
  temp = num
  while num>0:
    num//=10
    count +=1
  while num>0:
    num1 = temp%10
    sum = sum+num1^count
  if sum==num:
    print(" Armstrong Number")
 
