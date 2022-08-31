# 3-1
>难以察觉的语法错误（高教社，《Python编程基础及应用》习题3-1）  
找出下述程序中的三处错误。
```python
iScore = 70

if Score >= 60:

  print("You passed.")

else:

    print("You failed.')
```

- A. Score变量应为iScore
- B. 第3行print语句缩进错误(应为4个空格）
- C. 第5行的字符串双引号与单引号不匹配

# 4-1
>与或非及比较运算（高教社，《Python编程基础及应用》习题3-2）  
写出下述程序的执行结果。
```python
a = 70
b = 55.3
c = 9
print(a>=60 and b>=60)
print(a%9+c)
print((not a<90) or b<60)
print(not (a<90 and b<60))
```

执行结果第1行应为：`False`


执行结果第2行应为：`16`


执行结果第3行应为：`True`


执行结果第4行应为：`False`

# 4-2
`Dora    899.0   10      89.90`

# 4-3
`784`
`122`


# 4-4
`0b10001111`

# 7-1
```python
a = int(input())
b = int(input())
c = int(input())
print("{},{:.2f}".format(a+b+c,(a+b+c)/3))
```

# 7-2
```python
jo = int(input())
to = int(input())
tu = (jo-to*2)/2
ji = to-tu
print("{:.0f}\n{:.0f}".format(ji,tu))
```
# 7-3
```python
import math
a = int(input())
b = int(input())
c = int(input())
p = (a+b+c) / 2
if((a+b>c)and(b+c>a)and(a+c>b)):
    S = math.sqrt(p*(p-a)*(p-b)*(p-c))
    print("{:.2f}".format(S))
else:
    print("数据错误")
```

# 7-4
```python
f = int(input())
c = 5/9*(f-32)
print("{:.1f}".format(c))
```

# 7-5
```py
import math
r = float(input())
print("{:.3f}\n{:.3f}\n{:.3f}".format(2*math.pi*r,math.pi*r*r,4*math.pi*r*r))
```

# 7-6
```py
a = float(input()) 
print("千米:{:.2f}".format(a*1.609))
```

# 7-7
```py
v = float(input())
a = float(input())
print("最短跑道长度为:{:.2F}".format(v*v/(2*a)))
```

# 7-8
```py
import math
x1,y1 = input().split(",", 1)
x2,y2 = input().split(",", 1)
x1 = float(x1)
y1 = float(y1)
x2 = float(x2)
y2 = float(y2)
l = math.sqrt((x2-x1)*(x2-x1)+(y2-y1)*(y2-y1))
print("{:.2f}".format(l))
```
