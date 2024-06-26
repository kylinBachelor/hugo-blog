---
title: "Vim常用快捷键操作"
aliases: 
tags: ["vim"]
description: "Vim常用快捷键操作"
date: 2024-05-09T13:07:18+08:00
draft: false
---


### 移动光标

1. `h`：左移
2. `j`：下移
3. `k`：上移
4. `l`：右移
5. `w`：移动到下一个单词的开头
6. `e`：移动到下一个单词的结尾
7. `b`：移动到上一个单词的开头
8. `0`：移动到行首
9. `$`：移动到行尾
10. `gg`：移动到文件开头
11. `G`：移动到文件末尾
12. `H`：移动到屏幕的上半部分
13. `M`：移动到屏幕的中间部分
14. `L`：移动到屏幕的下半部分
15. `nG`：移动到第n行
16. `fx`：移动到下一个字符处
17. `tx`：移动到前一个x字符处
18. `Fx`：移动到下一个x字符处，相当于fx的反向操作
19. `Tx`：移动到前一个x字符处，相当于tx的反向操作
20. `;`：重复上一次f、t、F、T命令
21. `,`：反向重复上一次f、t、F、T命令
22. `*`：移动到下一个相同单词
23. `#`：移动到上一个相同单词
24. `%`：移动到括号匹配处
28. `Ctrl + o`：回到上一个跳转位置
29. `Ctrl + i`：回到下一个跳转位置
30. `Ctrl + u`：向上滚动半屏
31. `Ctrl + d`：向下滚动半屏
32. `Ctrl + b`：向上翻页
33. `Ctrl + f`：向下翻页
34. `Ctrl + e`：向下滚动一行
35. `Ctrl + y`：向上滚动一行


### 编辑操作
+ `J` ：合并当前行与下一行
+ `K` ：合并当前行与上一行
+ `u` ：撤销
+ `Ctrl + r` ：重做
+ `x` ：删除当前字符
+ `X` ：删除前一个字符
+ `dd` ：删除当前行
+ `D` ：删除当前字符到行尾
+ `dw` ：删除当前单词
+ `cw` ：修改当前单词
+ `yy` ：复制当前行
+ `p` ：粘贴
+ `P` ：粘贴到上一行
+ `cc` ：删除当前行并进入编辑模式
+ `~` ：切换大小写
+ `>>` ：向右缩进
+ `<<` ：向左缩进
+ `==` ：自动缩进

### 查找替换
+ `/pattern` ：向下查找pattern
+ `?pattern` ：向上查找pattern
+ `n` ：重复上一次查找
+ `N` ：反向重复上一次查找
+ `:s/old/new` ：替换当前行第一个old为new
+ `:s/old/new/g` ：替换当前行所有old为new
+ `:n1,n2s/old/new/g` ：替换第n1到n2行所有old为new
+ `:%s/old/new/g` ：替换所有行所有old为new
+ `:%s/^/new/` ：每行行首插入new
+ `:%s/$/new/` ：每行行尾插入new
+ `:%s/old/new/gc` ：替换所有行所有old为new，并显示替换过程
