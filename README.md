# max_value-with-index
approach-1
#max_value with index
n=int(input())
a=list(map(int,input().split()))
m=0
for i in range(n):
  if a[i]>m:
    m=a[i]
res=a.index(m)
print(m,res)
#approach-2
n=int(input())
a=list(map(int,input().split()))
m=0
for i in a:
  if i>m:
    m=i
res=a.index(m)
print(m,res)
