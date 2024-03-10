# pattern
a=[]
k=8
for  i in range(2):
  x=[]
  for  j in  range(2):
    x.append(k)
    k=k-2
  a.append(x)
for i in a:
  print(*i,sep=" ")
