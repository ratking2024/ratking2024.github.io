---
title: 置顶markdown高阶格式验证
date: 2014-04-15
categories: single
id: blog001
mathjax: true
---

本文作为存档备份，每次切换转义框架或主题时，以此文档验证该环境下markdown各语法是否支持以及样式是否美观。

## Quick Start

## 化学公式


### 化学方程式表示



## 数学公式

### 基本字符

### 多行多项式
```

```
有些符号会产生不合适的间隔，需要手动添加间隔符 

$$
\begin{array}{cc}
\mathrm{Bad} & \mathrm{Better} \\
\hline \\
\{x|x^2\in\Bbb Z\} & \{x\mid x^2\in\Bbb Z\} \\
\end{array}
$$

```
$$
\begin{array}{cc}
\mathrm{Bad} & \mathrm{Better} \\
\hline \\
\{x|x^2\in\Bbb Z\} & \{x\mid x^2\in\Bbb Z\} \\
\end{array}
$$
```

箭头指向
$$
\begin{CD}
    A @>>> B @>{\text{very long label}}>> C \\
    @. @AAA @| \\
    D @= E @<<< F
\end{CD}
$$
$$
\begin{CD}
    A @>a>> B\\
    @V b V V\# @VV c V\\
    C @>>d> D
\end{CD}
$$

```
$$
\begin{CD}
    A @>>> B @>{\text{very long label}}>> C \\
    @. @AAA @| \\
    D @= E @<<< F
\end{CD}
$$
$$
\begin{CD}
    A @>a>> B\\
    @V b V V\# @VV c V\\
    C @>>d> D
\end{CD}
$$
```

啊啊

底部分割


<details>
	<summary>折叠文本</summary>
	`hexo`是什么？
	#### 啊啊啊啊啊eeee鹅鹅鹅饿
</details>

## 问答

<details>
  <summary>什么是tinper</summary>
    
`tinper`是开源前端技术平台。<br>
 鹅鹅鹅饿
 ##### 啊啊啊啊啊eeee鹅鹅鹅饿
    
 ```
    int a = 0;
    
 ```
</details>