# 概述

autotools本质上是根据一系列配置，生成Makefile，而后，可以使用make对项目进行编译。

# 流程

## 工具链关系

![](/assets/autotools-work-stream.png)

如上图（摘自网络），autotools工具链包含：autoscan、aclocal、autoheader、autoconf、automake

最终autotools生成configure（shell脚本），执行configure并加以添加定制化参数，即可生成对应的Makefile。

工具链基本工作原理：展开宏定义，或者根据模板输入文件，产生输出文件。

开发者必须编写的文件是：configure.ac、Makefile.am

开发者可选编写的文件是：config.h.in、aclocal.m4

## 工具链详细介绍

### autoscan

### aclocal

### autoconf

### autoheader

### automake

## 编译



