---
title: windows 命令行中进入指定的目录
published: 2025-12-20
updated: 2025-12-20
discribe: 如何在windows的cmd＆prompt中进入指定的目录下
image: ''
tags: [windows,命令行]
category: '命令行'
draft: false
---
## 进入指定目录
在windows的命令行中，使用 `cd` 命令可以进入指定的目录。
例如，假设你想进入 `C:\Users\YourName\Documents` 目录，可以使用以下命令：

```cmd
cd C:\Users\YourName\Documents
```
如果目录路径中包含空格，需要使用引号将路径括起来，例如：

```cmd
cd "C:\Users\Your Name\Documents"
```
## 返回上一级目录
要返回上一级目录，可以使用以下命令：

```cmd
cd ..
```
## 返回根目录
要返回当前驱动器的根目录，可以使用以下命令：

```cmd
cd \
```
## 切换驱动器
:::important  
注意不能跨驱动器进行目录跳转
:::  
>比如  
如果你当前在C盘，想进入D盘的某个目录，直接使用 `cd D:\SomeFolder` 是不行的。你需要先切换到D盘，然后再进入指定目录。  

**要切换到另一个驱动器（例如从C盘切换到D盘），只需输入驱动器字母后跟冒号：**

```cmd
D:
```
这样你就可以在Windows命令行中轻松地导航到所需的目录了。  
接下来你就可以进入D盘下的目录了  
```cmd
cd D:\SomeFolder
```