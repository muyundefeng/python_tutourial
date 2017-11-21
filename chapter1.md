# python中基本的数据类型

## 数值类型

python支持四种基本的数值类型，分别是整数，长整数，浮点数以及复数，类型分别是int，long，float，complex

其中长整数没有上限与下限，复数是区别与其他与语言类型的。复数的表示方法存在**两种:a+bj或者complex\(a,b\)**

表示长整数的时候，需要在数字的末尾加上大写或者小写的l。

上面四种类型可以进行相互的转化，其中int\(x\)，long\(x\)，float\(x\)分别表示将x转化为整数，长整数以及浮点数三种类型。比较常见的几种表达式：repr\(x\)将字符串x转化为表达式；**eval\(x\)执行x中有效的python表达式，并返回结果；**chr\(x\)将x转化为字符；ord\(x\)将一个字符转化为它的整数。

## python中的数学函数

| 函数名称 | 含义 |
| :--- | :--- |
| abs\(x\) | x的绝对值 |
| ceil\(x\) | 返回数字上整数,ceil\(4.1\)=5 |
| floor\(x\) | 返回数字的下舍证书，ceil\(4.9\)=4 |
| max\(x1,x2,.....\) | 返回列表中的最大值 |
| min\(x1,x2,....\) | 返回列表中的最小值 |
| round\(x,\[n\]\) | 返回x的四舍五入值，并保留n位小数 |

## python中的随机函数

| 函数名称 | 含义 |
| :--- | :--- |
| choice\(seq\) | 返回seq随机一个数值，例如choice\(rang\(1,10\)\)可能返回9 |

## python中的字符串操作

| 函数 | 含义 |
| :--- | :--- |
| a\[1:5\] | 返回字符串a的第二个字符到第五个字符，不包括第五个 |
| a\[\] | 通过索引获取所在位置的字符 |
| a** in** A | A中是否包含a字符串 |
| a not in A | A中不包含a返回True，否则False |
| r/R | 所有的字符串按照字面意思来用，例如r'\n'返回\n |

### 字符串的格式化

主要的操作符为**%**

其中%s与%d分别表示格式化字符串与整数。例子如下:

print 'my name is** %s,d%** years old' _**%**_ \('tom',21\)

输出为my name is tom,21 years old

### 三引号

python中的三引号，通常引用html或者sql，可以避免很多转移字符的出现。

## python中的列表

python中的里列表类似于java中的list。

| 方法 | 含义 |
| :--- | :--- |
| min\(list\) | 返回list中的最小值 |
| max\(list\) | 返回list中的最大值 |
| list.append\(q\) | list中追加元素 |
| list.extend\(list1\) | list中扩充序列,list1放在list尾部 |
| list.index\(obj\) | 返回匹配到第一个obj的索引 |
| list.pop\(\) | 移除最后一个元素，并返回该元素的值 |
| list.reverse\(\) | 反转列表 |
| list.sort\(func\) | 对list进行排序 |





