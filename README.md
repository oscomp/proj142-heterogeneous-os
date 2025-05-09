# proj142-heterogeneous-os
异构操作系统中的多指令集应用执行环境


### 项目描述

在包括一个C906的RISC-V和两个A7的ARM核的异构SoC开发板D1-Super上移植uCore或rCore教学操作系统，以支持在一个操作系统中运行ARM应用程序和RISC-V应用程序。

### 所属赛道

2025全国大学生操作系统比赛的“OS功能设计”赛道

### 参赛要求

* 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生
* 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
* 请遵循“2025全国大学生操作系统比赛”的章程和技术方案要求

### 项目导师

向勇

* github [https://github.com/xyongcn](https://github.com/xyongcn)
* email [xyong@tsinghua.edu.cn](mailto:xyong@tsinghua.edu.cn)

### 难度

高

### 特征

* uCore、rCore等教学操作系统
* ARM A7
* RISC-V64

### License

* GPL3

### 预期目标

选择一个小操作系统（以RISC-V上的rCore为例）实现下面的移植和功能扩展目标。

* 基于已有参考，移植RISC-V上的rCore到D1-Super开发板上；
* 扩展rCore的启动过程，以启动两个ARM A7核；
* 实现ARM与RISC-V间核间中断IPI的MessageBox驱动；
* 扩展进程管理模块和相关系统调用，支持ARM应用程序的加载和执行控制；
