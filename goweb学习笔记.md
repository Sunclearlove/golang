### 快速入门Go







##### 一、变量的声明方式与多变量声明方式

###### 	1. PrintIn、Printf的使用

2. ###### 打死

```go
Println：打印字符串、变量；

Printf：打印需要格式化的字符串，可以输出字符串类型的变量；不可以输出整型变量和整型

  %v：默认方式打印变量的值
  %T：打印变量的类型
  \n: 表示换行符

  实例:  fmt.Printf(" type of a = %T\n", a) // type of a = int
```

###### 	2.  声明一个变量 默认的值是 0

```go
var a int
fmt.Println("a = ", a) // a = 0
fmt.Printf(" type of a = %T\n", a) // type of a = int
```

###### 3. 初始化的时候,可以省略数据类型,通过自动匹配当前的变量的数据类型

```go
var c = 100
fmt.PrintIn( "c = ", c)
```

###### 4. ( 常用方法 )	省去var关键字,	直接自动匹配

```go
e := 100
fmt.PrintIn( "e = ", e)
```

































