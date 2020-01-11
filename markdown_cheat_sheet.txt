---
title: Markdown Cheat Sheet
date: 1994-10-10 11:07:29
tags:
---

# Markdown Cheat Sheet

我展示的是一级标题
=================

我展示的是二级标题
-----------------

# 一级标题

## 二级标题

### 三级标题

#### 四级标题

##### 五级标题

###### 六级标题

换行的方式  
可以两个空格加回车

或者连续两个回车

*斜体文本*

_斜体文本_

**粗体文本**

__粗体文本__

***粗斜体文本***

___粗斜体文本___

## 分隔线

***

* * *

*****

- - -

----------

~~删除线~~

<u>带下划线文本</u>


## Markdown 列表

* 第一项
* 第二项
* 第三项

+ 第一项
+ 第二项
+ 第三项


- 第一项
- 第二项
- 第三项

## Markdown区块

> 区块的第一项
> 区块的第二项
> 区块的第三项
--------------
> 最外层
> > 第一层嵌套
> > > 第二层嵌套
----------------
> 区块中使用列表
> 1. 第一项
> 2. 第二项
> + 第一项
> + 第二项
> + 第三项
---------------------
* 第一项
    > 菜鸟教程
    > 学的不仅是技术更是梦想
* 第二项

## Markdown代码

`printf("Hello world");`可以写在同一行内

四个空格或一个tab键加小于号开启代码区块

	>```{r}
	cat("This is the code part")
	```

一段代码可以注明也可以不注明

```
$(document).ready(function () {
    alert('RUNOOB');
});
```

```{r}
cat("Hello world")
```

被添加[链接](www.link_address.com)的文字

也可以直接写出链接
www.link_address.com

链接也可以用变量来代替，文档末尾附带变量地址：
这个链接用 1 作为网址变量 [Google][1]

这个链接用 runoob 作为网址变量 [Runoob][runoob]

然后在文档的结尾为变量赋值（网址）

  [1]: http://www.google.com/
  [runoob]: http://www.runoob.com/

## Markdown 图片
开头一个感叹号 !

接着一个方括号，里面放上图片的替代文字

接着一个普通括号，里面放上图片的网址，最后还可以用引号包住并加上选择性的 'title' 属性的文字。

![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png)

![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png "RUNOOB")

## Markdown 表格

Markdown 制作表格使用 | 来分隔不同的单元格，使用 - 来分隔表头和其他行。

语法格式如下：

|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |

-------------------------

| 左对齐 | 右对齐 | 居中对齐 |
| :-----| ----: | :----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |

## 转义

**文本加粗** 

\*\* 正常显示星号 \*\*

---------------------------

<kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑

$$\textrm{Soma Size}_i = \beta_0 +\beta_1\*\textrm{Fatty Acid treatment}_i +\xi_i$$

$$a+b$$
