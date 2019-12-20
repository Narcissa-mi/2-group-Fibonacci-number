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
