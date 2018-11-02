---
layout: post
title: 'MacOS Python2.7升级Python3.7'
date: 2018-11-02
categories: Python
tags: Python
---

### 1. 下载Python3.7
```
https://www.python.org/downloads/
```

### 2. 安装python 3.7
点击下载好的pkg文件进行安装，安装完成之后，python 3.7的默认安装路径如下：
```
/Library/Frameworks/Python.framework/Versions/3.7
```

### 3. 修改profile文件
```
vim ~/.bash_profile
```
添加：
```
alias python="/Library/Frameworks/Python.framework/Versions/3.7/bin/python3.7"
```

### 4. 重启一下Terminal
