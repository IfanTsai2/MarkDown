# Demo2

## 链接

### 内嵌式链接

- 外部链接: [百度](http://www.baidu.com)
- 内部链接: 
	- 链接其他文件: [demo1](demo1.md)
	- 链接本文其他部分: [代码块](demo2.md#代码块)

### 引用式链接

- 外部链接: [百度][百度]
- 内部链接: 
	- 链接其他文件: [demo1][demo1]
	- 链接本文其他部分: [代码块][代码块]

## 图片

- 外部图片
![百度logo](https://www.baidu.com/img/bd_logo1.png?where=super "百度logo")
- 本仓库内图片
![百度logo](./images/bd_logo.png "百度logo")



## 引用

> 这是一个引文。

															—— 出自《出处》

## 代码块

- 行内代码
`printf("hello world\n");`

- 块式代码
```c
#include <stdio.h>

int main(void) 
{
	printf("hello world\n");
    return 0;
}
```



<!--- 下面是本文中用到的链接 -->

[百度]: http://www.baidu.com
[demo1]: demo1.md
[代码块]: demo2.md#代码块
