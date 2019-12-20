# 2-group-Fibonacci-number
为了解决第2小组的论文，斐波那契数列而创建。

x = 0
y = 1
n=1
while n!=0:
  x=x+y
  y=x+y
  if x>300 or y>300:
    break
  print(x) 
  print(y) 

def fib(n):
  x = 0
  y = 1
  for i in range(int(n/2)):
    x = x+y
    y = x+y
  if n%2 is 0:
    return x
  return y
number = int(input("番号を入力してください:"))
for i in range(number):
  print(fib(i))
