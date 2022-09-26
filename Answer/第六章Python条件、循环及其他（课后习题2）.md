## 7-3
```py
n=input()
n=float(n)
r=0
a=[1000000,600000,400000,200000,100000,0]
rat=[0.01,0.015,0.03,0.05,0.075,0.1]
for i in range(6):
    if n>a[i] :
        r=r+(n-a[i])*rat[i]
        n=a[i]
r=('%.2f'%r)
print(r)
```
## 7-4
```py
a = 1
sum = 1
n=int(input())
for i in range(1, n+1):
    a*= i;
    item=1 / a;
    sum += item;
print("%.10f"%sum)
```