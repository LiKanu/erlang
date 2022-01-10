## erlang 学习笔记01

### 1、 erlang基础

#### 1、数值类型

Erlang并不关心输入的是浮点数还是整数。算数运算对两种类型都支持。

##### 1、多进制数值表示

对于非10进制的数值，采用Base#Value的形式输入数值即可，2 =< Base <= 36。

- 二进制，例如`2#10010`表示二进制的18
  
  ![](/Users/likanug/Library/Application%20Support/marktext/images/2022-01-10-15-07-42-image.png)

- 八进制，例如`8#1010`表示八进制的520
  
  ![](/Users/likanug/Library/Application%20Support/marktext/images/2022-01-10-15-13-42-image.png)

- 十六进制，例如`16#101`表示十六进制257
  
  ![](/Users/likanug/Library/Application%20Support/marktext/images/2022-01-10-15-18-29-image.png)

#### 2、变量不可变

变量只能赋值一次，在第二次赋值之后就会报错。

#### 3、布尔类型
