---
permalink: /
title: "Academic Pages"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
INTRODUCTIONS
======
重庆大学计算机科学与技术(卓越)2021级学生，我是一个积极进取的人，热衷于学习更多关于计算机的知识，动手搭建项目，研究兴趣方向是软件工程、自然语言处理、电子信息、计算机视觉。

SKILLS AND LEARNINGS
======
#  2024.05
- **项目概述**：课设 《编译器设计与实现》，实现了一个将类C语言翻译至汇编的编译器，最终生成的汇编代码通过GCC的汇编器转化为二进制可执行文件，并在物理机或模拟器上运行。
  
- **主要功能**：
  - **词法分析和语法分析**：读取源文件中的代码并进行分析，输出一颗语法树。
  - **语义分析和中间代码生成**：接受语法树，进行语义分析，生成中间表示（IR）。
  - **汇编代码生成**：将IR翻译为汇编代码，并在模拟器 qemu-riscv 上运行。
- **项目代码**：[编译器设计与实现](https://github.com/guoluguodong/Junior-year/tree/main/s2/%E7%BC%96%E8%AF%91%E5%8E%9F%E7%90%86/%E5%AE%9E%E9%AA%8C/lab3)


#  2024.4
- **项目概述**：课设 《基于Web的单点登录系统》，本设计涉及Web编程技术，包括Servlet，JSP，Filter，Listener等Web设计元素的使用；部署在Tomcat服务器上。
- **主要功能**：
  - **单点登录（SSO）**：SSO是一种机制，允许用户只需登录一次即可访问所有相关系统，无需单独登录到每个系统。这样做的好处是简化了登录流程，同时提供了额外的安全层。
- **源代码链接**：[基于Web的单点登录系统](https://github.com/guoluguodong/SSOLoginInSystem)

#  2023.12
- **项目概述**：课设 《MIPS SOC 设计与性能优化》，本设计实现了简单的MIPS CPU, 是一个实现52 条基本指令和5 条特权指令的五级流水线CPU，实现精确异常处理，实现了2 路组相联LRU 替换策略的写回cache（也实现了4路组相联PLRU 替换策略的写回cache）优化。小组合作完成。
- **主要功能**：
  - **指令操作**：实现的简易五级流水线 CPU，52条基础指令，和5条特权指令实现精确异常处理
  - **性能测试**：
  类 SRAM 接口，添加 cache，采用龙芯杯提供的转接桥连接 AXI 总线，；
- **源代码链接**：[MIPS SOC 设计与性能优化](https://github.com/guoluguodong/Junior-year/tree/main/s1/%E7%A1%AC%E4%BB%B6%E7%BB%BC%E5%90%88%E8%AE%BE%E8%AE%A1/CO-lab-material-CQU-2022)

#  2023.4
- **项目概述**：课设 《数据库SQL执行器设计与模拟实现》，本设计针对关系型数据库SQL语句执行，进行需求分析，并设计一个简单的数据库系统SQL执行器模块，根据设计模拟实现SQL基本操作，小组合作完成。
- **主要功能**：
  - **SQL基本操作**：数据库创建、表格创建、数据添加、删除、更新、查询等操作。使用test.sql中的语句进行测试。
  - **项目模块**：
  (1). SQL解析器：将用户输入的SQL指令解析为内部的数据结构，以便进一步处理和执行
  (2). SQL 执行器：将解析后的SQL命令传递给对应的执行模块，并执行相应的操作。
- **项目特点**：实现了B+树索引。

- **源代码链接**：[数据库SQL执行器设计与模拟实现](https://github.com/guoluguodong/SQL-Parser-and-Runner-with_B_Plus_Tree)

