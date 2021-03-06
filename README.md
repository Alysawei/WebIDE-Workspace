# Coding WebIDE Workspace

## 项目说明

本项目是为了能够一键启动 `WebIDE` 开源版而创建的，以 git 子模块的形式引用了另外的三个项目，分别是 WebIDE-Frontend、WebIDE-Frontend-Webjars、WebIDE-Backend。

## 模块说明

> **WebIDE-Frontend:** WebIDE 前端项目  
> **WebIDE-Frontend-Webjars:** webjar 项目，用于将 WebIDE 前端打包成 webjar  
> **WebIDE-Backend:** WebIDE 后端项目  

## Clone 项目

首先 clone 本项目到本地，然后拉取子项目:

> git submodule init  
> git submodule update

即可拉取子项目到本地。

## 运行环境

**WebIDE-Frontend 依赖 bower、nodejs**  
**WebIDE-Frontend-Webjars & WebIDE-Backend 项目依赖 maven**

在编译、运行项目前，请保证环境依赖已被正确配置。

## 编译、打包、运行

本项目提供了一个脚本 `ide.sh`，用于编译、打包、运行项目：

> **./ide.sh build:** 编译并打包前端项目  
> **./ide.sh run:** 启动项目

启动完成后，默认端口为 8080，访问 localhost:8080 即可。

