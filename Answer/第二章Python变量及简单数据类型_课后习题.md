## 第二章Python变量及简单数据类型（课后习题）

### 3-1 
>请选出下述Python变量命名中正确的命名。

C. iLength
D. _Width

### 4-1 

>字符串的upper()函数
写出下述程序的执行结果。
```
sName1 = "john miller"
print("1:",sName1.upper())
print("2:",sName1)
```

执行结果第1行：`1: JOHN MILLER`

执行结果第2行：`2: john miller`

### 4-2

>转义符号的应用
写出下述程序的执行结果。
```
s = "\"Programming\" itself is the best way to learn programming.\n\t---Nobody."
print(s.strip())
```

第1行：`"Programming" itself is the best way to learn programming.`

第2行：`        ---Nobody.`

### 4-3

>整数，浮点数及布尔型的相互转换
写出下述程序的执行结果
```
r = int(True) + int(bool(-0.0000001)) + int(3 > 2)
print(r)
```
答案:`3`
