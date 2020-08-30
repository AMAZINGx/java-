

# basic structure



public class hello {

​		public static void main(String[]args)

​				//向屏幕输出文本：

​		System.out.println{"Hello world!"};

/*

进行多行的内容注释

*/

} // class 定义结束

java的基本单位是class，*class是keyword 这里class的名字是hello 



public 是访问修饰符 表示这个class是公开访问的

这里的方法名是main 返回void 值

这个public除了修饰class也可以修饰方法 但是关键字static是另外一个修饰符号他表示静态方法。java的入口程序规定的方法必须是静态方法

##方法名的规则 首字母必须小写



在方法内部语句才是真正执行的代码 每一个语句必须用分号结束



## 变量

java中有两种变量 ： 基本类型的变量和引用类型的变量 

#### 基本类型的变量

1. 必须先定义 后使用 

2. 在定义变量的时候可以给他一个初始值 

   不写初始值就会有一个默认值：0 。

变量的一个重要特点是可以对其进行重新赋值



	- 整数类型： byte，short， int，long
	- 浮点数类型： float， double 
	- 字符类型：char 
	- 布尔类型  

#### 引用类型 

最常见的就是 string 

##### 常量 

定义变量的时候 加上final修饰符 这个变量就变成了常量 ( 习惯为大写)

``` java
final double pi = 3.14; 
double r = 5.0;
double area = PI * r * r;
```

变量的作用范围 都在 花括号里面 



## 整数运算

Java中整数运算遵循四则运算规则 

整数运算求余数运算用（” % “）

#### 自增/自减

```` java
public class Main {
  public static void main(String[]args)
    int n = 1;
  	n++;// n = n +1;
  	n--;// n = n -1;
  	++n; // 先加一再引用 n 
  	--n;// 同上
  System.out.println(n);
}
````



### 运算优先级

在Java的计算表达式中，运算优先级从高到低依次是：

- `()`
- `!` `~` `++` `--`
- `*` `/` `%`
- `+` `-`
- `<<` `>>` `>>>`
- `&`
- `|`
- `+=` `-=` `*=` `/=`

 #### 类型自动提升和强制转型

如果在运算的时候两数字的类型不一致 计算结果为较大类型的数据 

short 和 int 计算 结果为int 

也可以把结果强制转型 把大范围的整数数据转型为小范围的整数 int 强制转换为short 

## Object

dog mydog = new dog 













