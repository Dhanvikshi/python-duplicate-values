# python-duplicate-values
#duplicate elements in array
#approch--1
'''n=int(input())
a=list(map(int,input().split()))
for i in range(n-1):
  if a[i] in a[i+1:]:
    print(a[i])
    break'''
    

#apprOCH--2
'''n=int(input())
a=list(map(int,input().split()))
for i in range(n-1):
  if a.count(a[i])>1:
    print(a[i])
    break'''
#aprooch--2.1without range
'''n=int(input())
a=list(map(int,input().split()))
for i in a:
  if a.count(i)>1:
    print(i)
    break'''
#aprroch--3 by using slicing windows
'''n=int(input())
a=list(map(int,input().split()))
a.sort()
for i in range(n-1):
  if a[i] == a[i+1]:
    print(a[i])
    break'''
