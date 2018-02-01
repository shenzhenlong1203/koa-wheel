# Teng-koa

![alt](./img/screenshot.png)
> 项目已经通过生产测试。 目前附带的 Demo
* Demo: 网易云 API (基于 `simple-netease-cloud-music`)
* Demo: 请求数统计 (过去一分钟，过去一小时，过去一天)

本项目是基于 Koa v2 的 RESTful API 框架实现，目前已经实现的功能:
* 自动化加载的路由
* 自动化加载的控制器
* 易用的日记系统
* 简单的访问统计
* 更方便的中间件，插件管理
* 更方便的 Cron 管理
* 邮件发送模块 （提供 API服务错误时发送邮件给管理员 的功能）
* 简单的 SQL ORM 实现
* 简单的 Redis Cache 系统


## 开始
```
$ rm -rf .git
$ rm -rf img
$ cp config.json.example config.json
$ yarn init && git init
``` 

由于项目的设计初衷是 RESTful API 的易用轮子，所以并未考虑视图，有需要的可自行集成。
如果在使用中碰到问题或者您有更好的实现，想法，欢迎联系我。

-----------------------------
* Demo: Netease Cloud Music API (based on `simple-netease-cloud-music`)
* Demo: Count Requests number (pastMinute, pastHour, pastDay)

This Project is based on `koa v2`. This is a RESTful API framework.
The features list:
* auto-load routes
* auto-load controllers
* handy log system
* handy request count
* handy cron manager
* handy Middlewares/plugins manager
* simple & fast SQL ORM
* simple & handy Redis Cache System
* Mail Support (Can Send Mail While Crash)

## How to Start ?
```
$ rm -rf .git
$ rm -rf img
$ cp config.json.example config.json
$ yarn init && git init
``` 

If you occur a error in use or have a better idea about it , contact me please. 
