# cpp内存泄漏检查工具vld

## 一、结构

include:	vld.h	vld_def.h

lib:	Win32/vld.lib	Win64/vld.lib

bin:		Win32/vld_x86.dll, Win32/vld_x86.pbd, Win32/dbghelp.dll		Win64/vld_x64.dll, Win64/vld_x64.pbd, Win64/dbghelp.dll

## 二、使用

添加链接库：#pragma comment(lib, "vld.lib")

bin/Win32 or bin/Win64添加至环境路径

在包含预编译头文件前添加 #include "vld.h"

