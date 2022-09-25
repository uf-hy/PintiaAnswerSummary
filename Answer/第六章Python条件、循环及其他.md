### 填空题
4-1 `40`
4-2 `1` `3` `5`

### 程序填空题
`(int(b)*int(b)==x+268)&(int(a)*int(a)==x+100)`
### 编程题
> 7-1
```py
tivs,ufgc = input().split(',',1)
tivs = float(tivs)
ufgc = float(ufgc)
BMI = tivs/(ufgc*ufgc)
if BMI < 18:
    print("超轻")
elif BMI < 25:
    print("标准")
elif BMI < 27:
    print("超重")
else:
    print("肥胖")
```
> 7-2
```py
a = float(input())
if((a%3==0)&(a%5==0)&(a%7==0)):
    print("Yes")
else:
    print("No")
```
> 7-3
```py
lst = eval(input())
counts = [0] * 26
for i in lst:
    for j in i:
        counts[ord(j)-ord('a')]+=1
for i in range(26):
    if counts[i]>0:
        print(chr(ord('a')+i),counts[i],sep=',')
```
> 7-4
```py
lst = list(map(int,str(input())))
for i in range(len(lst)):
    lst[i] = (lst[i]+8)%7
lst[0],lst[4],lst[2],lst[1] = lst[4],lst[0],lst[1],lst[2]
for i in range(len(lst)):
    print(lst[i],end="")
```
