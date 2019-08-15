## 介绍
该项目是一个关于node.js（Express）的用户注册、登陆、和授权的小demo

## 准备

1.安装mongoDB
参考教程
https://www.jianshu.com/p/7241f7c83f4a
```
//启动mongoDB
mongo
//停止
use admin;
db.shutdownServer();
```
2.依赖
```
//安装express
npm i express@next
//操作mongdb工具
npm i mongoose
//无需重新启动node，实时刷新修改工具
npm i -g nodemen
```
3.工具插件

vscode插件安装REST Client

## 启动
```
nodemon server.js
```