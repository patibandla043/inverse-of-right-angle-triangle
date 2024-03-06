a=[]
n=int(input())
for i in range(n):
  x=[]
  for j in range(n):
    if i<=j:
      x.append("*")
    else:
      x.append(" ")
  a.append(x)
for i in a:
  print(*i,sep=" ")
