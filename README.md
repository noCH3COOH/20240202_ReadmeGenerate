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
    |----config.json   (97B)
    |----emojiLog.py   (5.1650390625KB)
    |----fileAnalysis.py   (1.5830078125KB)
    |----info.json   (1.0322265625KB)
    |----LICENSE   (11.287109375KB)
    |----log.txt   (0B)
    |----main.py   (4.521484375KB)
    |----README.md   (0B)
    |----requirements.txt   (0B)
    |----test.md   (1.30078125KB)
    |----__pycache__
    |    |----emojiLog.cpython-312.pyc   (4.2197265625KB)
    |    |----fileAnalysis.cpython-312.pyc   (2.3671875KB)
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

***
