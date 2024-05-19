# 项目名称

2024年天津大学编译原理与技术大作业

## 项目简介

该项目是一个基于 C++语言实现的 C 语言子集(C--)的编译器. 它包括词法分析器和语法分析器, 用于对 C--语言源代码进行词法分析和语法分析.

## 团队成员及分工

- 李锦文：负责缓冲区，超前搜索算法，自动机使用，符号表以及报错功能代码的编写和不同类型的样例测试。
- 何昊宇：负责映射表和映射转换规则，构建 ε 闭包，NFA 确定化，DFA 最小化部分的代码编写和状态转换图的绘制。
- 邱成浩：负责 LL(1)文法初始化算法，消除左递归，消除回溯、预测分析过程算法
- 褚济铨：负责构造 LL(1)文法预测分析表。
- 郭法：负责构造文法非终结符的FIRST集和FOLLOW集。

## 开发环境

- 词法分析使用 c++ 作为开发语言。
- 语法分析使用 python 作为开发语言。