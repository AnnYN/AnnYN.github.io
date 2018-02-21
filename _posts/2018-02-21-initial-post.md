---
title: vim与bash笔记
abstract: 记录vim和bash的相关使用方法。
---

## {{ page.title }}

mv filename1 filename2   # 给文件改名字

<Tab> #命令补齐，可以多按几次

#CTRL组合

ctrl+a  #光标跳到行首
Ctrl+b  #光标左移一个字母
ctrl+c  #中断进程，开启新的一行
ctrl+d  #删除提示符后一个字符，或者exit或者layout
ctrl+e  #光标移到行尾
ctrl+f  #光标后移一个字符
ctrl+h  #删除前一个字符
ctrl+l  #清除屏幕
ctrl+k  #清楚光标后至行尾的内容
ctrl+u  #清楚光标至行首的内容
ctrl+p  #重复上一次命令
ctrl+w  #删除光标前一个单词
ctrl+y  #将删除的字符粘贴出来

#esc组合
esc+f #向右跳一个词语
esc+b #向左跳一个词语
esc+d #删除光标后的一个词

ctrl+r #搜索历史命令

ctrl+n #搜索下一个命令
ctrl+p #搜索前一个命令


df -h  #查看主机内存
git reset --hard #恢复代码

#VIM#

vim  filename   #打开vim编辑器，命令模式
#进入编辑模式
i   #进入编辑模式，按“i”进入插入模式后是从光标当前位置开始输入文件
a  #是从目前光标所在位置的下一个位置开始输入文字
o   #行首开始输入文字

ESC   #返回命令模式

#删除命令
x  #向后删除一个字符
X  #向前删除一个字符
dd  #两下d删除整行
2dd #从光标开始所在行删除第2行

u   #撤回上一步骤的操作

#移动光标
0   #回到所在行的开始
e   #移到所在行末位

#保存
：w  #存盘

#离开
：q  #退出
:wq  #存盘并退出
q! #强行退出不保存

