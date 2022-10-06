### 4-1
```
Jack Ma
10000
```
### 4-2
```
1111-2222
1111-2222
```

### 4-3
```
4
Eric Zhang
['name', 'english', 'python', 'math']
True
110
100
('english', 80)
90
```
### 4-4
```
C出现4次
B出现3次
A出现1次
```
### 7-1
```py
d = {}
while True:
    s = input()
    if s == 'q':
        break
    d[s] = d.get(s, 0) + 1

m = max(d.values())
for x, y in d.items():
    if y == m:
        print(x, y)
        break
```
### 7-2
```py
s = str(input())
b=len(s.split(" "))
c=len(s)
d=(c-b+1)/b
print("{},{:.2f}".format(b,d))
```