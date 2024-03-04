# Readme生成
***
## 目录
- [Readme生成](#readme生成)
  - [目录](#目录)
  - [项目简介](#项目简介)
    - [项目介绍](#项目介绍)
    - [项目结构](#项目结构)
  - [功能列表](#功能列表)
  - [依赖](#依赖)
  - [安装过程](#安装过程)
  - [使用方法](#使用方法)
  - [更新日志](#更新日志)

***
## 项目简介

### 项目介绍
本工程只是一个用于生成 README.md 文件的脚本，只会生成一些框架内容，方便自己完善 README。
README 结构是参考了网络很多文章随便弄的，包括
[standard-readme](https://github.com/RichardLitt/standard-readme/blob/main/spec.zh-CN.md)

### 项目结构
``` shell
----20240202_ReadmeGenerate
    |----config.json   (97.000B)
    |----emojiLog.py   (5.165KB)
    |----fileAnalysis.py   (1.614KB)
    |----info.json   (1.194KB)
    |----LICENSE   (11.287KB)
    |----log.txt   (0.000B)
    |----main.py   (4.523KB)
    |----README.md   (0.000B)
    |----requirements.txt   (0.000B)
    |----test.md   (1.301KB)
    |----__pycache__
    |    |----emojiLog.cpython-312.pyc   (4.220KB)
    |    |----fileAnalysis.cpython-312.pyc   (2.392KB)
```
包含以下类型的文件：['.json', '.py', '无后缀', '.txt', '.md', '.pyc']

***
## 功能列表
|brief|file|how|
|:-:|:-:|:-:|
|文件结构分析|fileAnalysis.py|analysis_file()|
|emoji日志生成|emojiLog.py|emojiLog(update_type, update_log)|

***
## 依赖
json

tkinter

os


***
## 安装过程
直接 clone 即可

***
## 使用方法
在工程目录下打开 cmd 或者其它命令行，输入
``` shell
python main.py
```

在弹出窗口选择需要生成的工程文件夹即可。

***
## 更新日志
20240202 🎉submit_first: 首次提交

20240203 📝add_doc: 更新 readme

20240304 🚀add_function: 将文件大小保留至三位小数


***
