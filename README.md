# 1st-TASK 
#Fibonacci series 
n=int(input("Enter the n value:"))
i=0
a=0
b=1
fib=0
while(i<=n):
if (i <= 1):
   fib=i
   else:
   fib=a+b
a=b
b=fib
print(fib)
i+=1
