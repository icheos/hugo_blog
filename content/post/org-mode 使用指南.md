+++
title = "org-mode 使用指南"
lastmod = 2022-12-24T14:30:24+08:00
draft = true
author = "icheos"
+++

## 快捷键操作 {#快捷键操作}

主要摘录几个我认为有用的操作,详细请看[官方文档](https://orgmode.org/org.html#Document-Structure)


## 基本符号 {#基本符号}


### checklist {#checklist}


### 列表操作 {#列表操作}

My favorite scenes are (in this order)

1.  The attack of the Rohirrim
2.  Eowyn's fight with the witch king
    -   this was already my favorite scene in the book
    -   I really like Miranda Otto.

Important actors in this film are:

Elijah Wood
: He plays Frodo

Sean Austin
: He plays Sam, Frodo's friend.


## 表格 {#表格}

表格功能比 markdown 强大，可以像 excel 一样使用一些数学功能

1.  使用 C-c '进入数学运算模式,输入运算完毕后，C-c C-c 回到原来界面，此
    时就会产生公式 #+TBLFM: $3=$2\*$1
2.  在公式上按 `C-c C-c` 就能进行计算了

| f | g | fdkd |
|---|---|------|
| 1 | 2 | 3    |


## todo 基本操作 {#todo-基本操作}


### checklist 使用 todo {#checklist-使用-todo}


#### lists<code>[33%]</code> {#lists}

-   [ ] list1
-   [ ] list2
-   [X] list3


## agenda 管理规划 {#agenda-管理规划}
