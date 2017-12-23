# YGOPro-AI

## 介绍
这是致力于ygopro本地ai的项目开发。

## 说明
[说明](https://github.com/Fluorohydride/ygopro/wiki/%E4%B8%AD%E6%96%87%E8%AF%B4%E6%98%8E)

## 编译
### 1.) 下载 YGOPro-AI
下载 YGOPro-AI

然后下载[ocgcore](https://github.com/SunnyEric/ygopro-core)，将解压出来的所有文件放入YGOPro-AI的ocgcore文件夹下

### 2.) 安装 Premake4 和 Visual Studio 2010 (或更高的版本).
下载[Premake4](https://premake.github.io/download.html#v4)

将premake4.exe放入`c:\windows`

下载安装vs2010(或更高的版本)

### 3.) 生成工程文件
在ygopro-ai目录打开cmd命令窗口，运行下面的命令

`premake4 vs2010`

### 4.) 编译生成
打开项目ygopro-ai\build\ygo.sln，选择Release

ygopro右键点生成

### 5.) 复制文件
将文件lflist.conf、strings.conf、system.conf、目录textures复制到Release目录

将ygopro最新版的pics目录、script复制、cards.cdb文件复制到Release目录

另外需要创建deck、replay文件夹

游戏即可运行
