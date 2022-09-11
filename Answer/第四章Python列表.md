### 4-1
执行结果第1行：`s1= [1, 3, '5', '7', 'False']`  
执行结果第2行：`s2= ['a', 'b', ['c', 'd']]`
### 4-2
执行结果:`[900, 66, 30, 24, 23, 22]`
### 4-3
第1行：`2`


第2行：`1`


第3行：`5`


第4行：`900`


第5行：`1011`


第6行：`8`

### 4-4
第1行：`900`


第2行：`[56, 8, 900]`


第3行：`[23, 8, 24]`


第4行：`[24, 900, 8, 56, 23]`
### 4-5
执行结果第1行：`mary`

执行结果第2行：`['henry', 'mary']`

执行结果第3行：`4`

### 4-6
执行结果第1行：`[2, 5, 8]`

执行结果第2行：`[0, 1, 2, 3, 4]`

执行结果第3行：`[10, 5, 0, -5]`



## 函数题

### 6-1
```py
def generateMatrix (m,n):
    a, temp = [], []
    for i in range(m):
        for j in range(n):
            temp.append(i + j + 2)
        a.append(list(temp))
        temp.clear()
    return a
```
### 6-2
```py
def generateMatrix (m,n):
    a, temp = [], []
    for i in range(m):
        for j in range(n):
            temp.append(random.randint(1,5))#1!5!
        a.append(list(temp))
        temp.clear()
    return a

```
## 编程题

### 7-4
```py
a=eval(input())
b=a.copy()
for x in b:
    ge=a.count(x)
    if ge>=2:
        for i in range(ge-1):
            a.remove(x)
print(a)
```