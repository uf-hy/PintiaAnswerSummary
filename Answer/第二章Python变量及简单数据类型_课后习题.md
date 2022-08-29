## 第二章Python变量及简单数据类型（课后习题）

### 3-1 (选择题)
>请选出下述Python变量命名中正确的命名。

C. iLength
D. _Width

### 4-1 (填空题)

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

### 7-1 (编程题)


  
***注意,PTA输入框左上角的语言(编译器)应改为Python(python3)***
***注意,PTA编辑器左上角的语言(编译器)应改为Python(python3)***
***注意,PTA输入框左上角的语言(编译器)应改为Python(python3)***

>将信息“Life is short, I want to learn python！”赋值给变量m，再将其打印输出  


```
m="Life is short,I want to learn python!"
print(m)
```

***如遇"编译错误"请确保PTA编辑器左上角的语言(编译器)为"Python(python3)"***

### 7-2
>使用print( )函数打印输出下述内容`丘吉尔说："成功就是从失败到失败，也依然不改热情！"。`

```
print("丘吉尔说：\"成功就是从失败到失败，也依然不改热情！\"。")
```

### 7-3

```
print("My favorite sports are as follows:\n\tfootball\n\ttable tennis\n\tbadminton\n\tswimming\n\trunning")
```

或者

```
print("My favorite sports are as follows:")
print("	football")
print("	table tennis")
print("	badminton")
print("	swimming")
print("	running")
```

### 7-4

>从键盘读取一个英文字符串，将其转换为大写，然后输出。

```
StrCache=input()
print(StrCache.upper())
```