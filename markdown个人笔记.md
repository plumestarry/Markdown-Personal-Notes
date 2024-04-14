# Markdown个人笔记

## 目录

- [Markdown个人笔记](#markdown个人笔记)
  - [目录](#目录)
  - [1. 基本文字块语法](#1-基本文字块语法)
    - [1.1 标题语法](#11-标题语法)
    - [1.2 段落语法](#12-段落语法)
    - [1.3 强调语法](#13-强调语法)
    - [1.4 引用语法](#14-引用语法)
    - [1.5 缩进块语法](#15-缩进块语法)
    - [1.6 分隔线语法](#16-分隔线语法)
  - [2. 文字内容语法](#2-文字内容语法)
    - [2.1 代码语法](#21-代码语法)
    - [2.2  字体语法](#22--字体语法)
    - [2.3 转义字符语法](#23-转义字符语法)
    - [2.4 脚注语法](#24-脚注语法)
    - [2.5 数学公式语法](#25-数学公式语法)
  - [3. 功能语法](#3-功能语法)
    - [3.1 列表语法](#31-列表语法)
    - [3.2 链接语法](#32-链接语法)
    - [3.3 图片语法](#33-图片语法)
    - [3.4 任务列表语法](#34-任务列表语法)
    - [3.5 表格语法](#35-表格语法)
    - [3.6 代码块语法](#36-代码块语法)
    - [3.7 标题编号语法](#37-标题编号语法)
    - [3.8 内嵌 HTML 标签](#38-内嵌-html-标签)
  - [4. 更多内容](#4-更多内容)

---

## 1. 基本文字块语法

### 1.1 标题语法

`# 一级标题`

`## 二级标题`

......

`###### 六级标题`

### 1.2 段落语法

这是一个段落

### 1.3 强调语法

这是强调语法 -> **这是强调语法**

强调语句应该包含在段落中，不然容易被认为是标题

### 1.4 引用语法

> 这是引用语法
>  
> **引用语法**可以嵌套其它语法

### 1.5 缩进块语法

    这是一个缩进块，Tab敲出

### 1.6 分隔线语法

以下是一条分隔线

---

## 2. 文字内容语法

### 2.1 代码语法

这是一段代码片段 `import os`

### 2.2  字体语法

~~我是删除线~~ `~~删除线~~`

**粗体** `**粗体**`

*斜体* `*斜体*`

注：如果想换颜色、字体或者居中显示，需要使用内嵌HTML来实现。

### 2.3 转义字符语法

可做转义的字符如下

\\ , \` , \* , \_ , \{\} , \[\] , \(\), \# , \+ , \- , \. , \! , \|

特殊字符自动转义

&copy; , &amp;

### 2.4 脚注语法

[这是一个脚注]("" "这是一个脚注")

`脚注：[文字](脚注解释 "脚注名字")`

### 2.5 数学公式语法

行内公式 `$公式$`

行间公式 `$$公式$$`

上标 $x^y$，下标 $x_y$，分式 $\frac{1}{2}$，开根号 $\sqrt{2}$

箭头 $a \leftarrow b \rightarrow c \leftrightarrow d \Leftrightarrow e \rightleftharpoons f$

矩阵：

$$
\begin{pmatrix}
1 & a_1 & a_1^2 & \cdots & a_1^n \\
1 & a_2 & a_2^2 & \cdots & a_2^n \\
\vdots & \vdots & \vdots & \ddots & \vdots \\
1 & a_m & a_m^2 & \cdots & a_m^n \\
\end{pmatrix}
$$

[更多详细公式](https://blog.csdn.net/m0_37769093/article/details/107732606)

---

## 3. 功能语法

### 3.1 列表语法

有序列表

1. 第一章
2. 第二章
   1. 第二章第一节
   2. 第二章第二节
      1. 第二章第二节第一段
3. 第二章
4. 第四章

无序列表

- 无序列表
- 无序列表
  - 无序列表
  - 无序列表
- 无序列表

### 3.2 链接语法

这是一个链接 [Markdown语法](https://markdown.com.cn "最好的markdown教程")

### 3.3 图片语法

![这是图片](https://i0.hdslb.com/bfs/bangumi/image/f50a08cc1562f2c1e933b656c00db3fcafd110e9.png@394w_525h.webp "间谍过家家")

### 3.4 任务列表语法

- [x] 吃饭
- [x] 睡觉
- [ ] 学习

### 3.5 表格语法

| 左对齐 | 居中 | 右对齐 |
| :--- | :----: | ---: |
| ---------------- | ---------------- | ---------------- |

### 3.6 代码块语法

```csharp
using System; 
class Hello 
{ 
static void Main() 
    { 
        Console.WriteLine("Hello, World"); 
    } 
}
```

```diff
+ 新增项
- 删除项
```

### 3.7 标题编号语法

`[标题名称](#heading-ids)`

### 3.8 内嵌 HTML 标签

<span style="display:block;text-align:center;color:red;">红色居中</span>

---

## 4. 更多内容

[Markdown相关编写软件](https://markdown.com.cn/tools.html#%E7%BC%96%E8%BE%91%E5%99%A8)

[使用Visual Studio Code编写Markdown](https://code.visualstudio.com/)

Visual Studio Code相关插件

- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf)
- [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)
- [Markdown Preview Github Styles](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles)
- [Markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)

---

Made by [Plumestarry](https://github.com/plumestarry)
