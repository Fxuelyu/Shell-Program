﻿# Shell Program
> This is BUAA OS Experiment 1. 

> OS实验1 - Shell程序

## Introduction 介绍
基本要求：

* 支持`fg`, `bg`, `cd`, `history`, `exit`指令
* 能够执行外部程序命令，命令可以带参数
* 使用I/O重定向和管道
* 支持前后台作业，提供作业控制功能，包括打印作业的清单，改变当前运行作业的前台/后台状态，以及控制作业的挂起、中止和继续运行。

提高要求：

1. 对YACC语法分析的文法进行进一步修改和完善。
1221312. 尝试在Linux下将Lex和YACC结合起来使用进行词法和语法分析。
1. 对其他常用的内部命令进行实现，并可以尝试考虑对通配符的支持和实现。
1. 实现对管道的支持。
1. 参照组合键Ctrl+Z的实现方法，考虑并实现组合键Ctrl+C命令。
1. 其他自行提出的改进。

## How to use 使用方法
在Unix/Linux终端中，通过`cd`命令修改至源文件目录，执行`make`即可编译。
执行`make clean`可以删除生成的中间文件。   