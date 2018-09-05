# lmsite 

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/jonny6015/lmsite/pulls)  [![GitHub stars](https://img.shields.io/github/stars/jonny6015/lmsite.svg?style=social&label=Stars)](https://github.com/jonny6015/lmsite)  [![GitHub forks](https://img.shields.io/github/forks/jonny6015/lmsite.svg?style=social&label=Fork)](https://github.com/jonny6015/lmsite)

> 学忆小站网站文档 ——> 从零开始规划网站。文章以`Markdown`语法书写，结合其他工具进行编辑。

## 1. 前言

### lmsite的诞生：

  该网站是作为一个程序员/开发者个人工具而生，当然也可以用于其它 Web 网站。在工作中，我希望把自己常用的网站工具等聚集在一起，但是很难找到一个根据自己需求打造的全方位系统，因此，我萌发了写一个这样的系统。
  既然是全方位系统，那么就要有高度可定制化功能，经过我认真的思考，决定使用 `Spring Boot` 来写。从名字就知道这是一个 `Spring` 的引导，就是用于启动 `Spring` 的，使得 `Spring` 的学习和使用变得快速无痛。不仅适合替换原有的工程结构，更适合微服务开发。而 `Spring Cloud` 是基于 `Spring Boot`，为微服务体系开发中的架构问题，提供了一整套的解决方案——服务注册与发现，服务消费，服务保护与熔断，网关，分布式调用追踪，分布式配置管理等。因此 `Spring Boot` 是该系统的核心框架，通过这个框架，理论上可以自由拓展无限个子系统，利用一个后台管理来进行治理。

### lmsite名字的由来：

`lmsite` 全名 `learn and memory site` 或者 `lettle and memory site`，中文名暂定为 “学忆小站” ，一个可以用来学习和记忆(个人感觉说回忆更好听)的Personal Website . 其中每一个子系统都是一个小而美系统，整合在一起又能成为一个强大的网站。这就是lmsite！

### 关于本网站：

lmsite 后端由 Jonny Chang (本人) 独立完成，前端在寻找合作同学，如果有那位前端同学希望一起来开发lmsite，可以加我微信：jonny6015. 官方域名： `lmsite.cn` 。

### lmsite 愿景：

`lmsite` 项目不仅仅是一个开发架构，而是努力打造一套从 **前端模板** ——> **基础框架** ——> **分布式架构** ——> **开源项目** ——> **持续集成** ——> **无限扩展** ——> **微服务系统** ——> **自动化部署** ——> **系统监测** ——> **无缝升级** 的全方位 `J2EE` 企业级开发解决方案。

## 2. lmsite 项目介绍

> 基于Spring Boot分布式敏捷微服务开发系统架构，提供整套公共微服务服务模块：内容管理、支付中心、用户管理（包括第三方）、微信平台、存储系统、配置中心、日志分析、任务和通知等，支持服务治理、监控和追踪。以 **主站**、**后台管理** 、**博客** 为优先实现功能，其余功能逐步实现。

### 文件组织结构

```shell


```

### 技术选型

#### 开发工具
|工具|软件版本|平台|系统版本|
|:---|:---|:---|:---|
|IntelliJ IDEA|2018.2.3|Windows 10|RS4(1803)|
|Visual Studio Code|1.26|Windows 10|RS4(1803)|
|HBuilder|9.1.19.201808300739|Windows 10|RS4(1803)|


#### 核心技术
|技术|中文说明|版本号| 官网 |
|:----|:----|:----|:----|
|Java SE Development Kit 8|Java开发工具包|jdk-8u181|[官网](http://www.oracle.com/technetwork/java/javase/downloads/index.html)|
|Spring Boot|微服务框架|2.0|[官网](http://spring.io/projects/spring-boot)|

#### 前端技术
|技术|说明|官网|
|:---|:---|:---|
|jQuery|函式库|[官网](http://jquery.com/)|
|Bootstrap|前端框架|[官网](http://getbootstrap.com/)|
|Bootstrap-table|Bootstrap数据表格|[官网](http://bootstrap-table.wenzhixin.net.cn/)|
|Font-awesome|字体图标|[官网](http://fontawesome.io/)|
|material-design-iconic-font|字体图标	|[官网](https://github.com/zavoloklom/material-design-iconic-font)|
|Waves|点击效果插件|[官网](https://github.com/fians/Waves)|
|zTree|树插件|[官网](http://www.treejs.cn/v3/)|
|Select2|选择框插件|[官网](https://github.com/select2/select2)|
|jquery-confirm|弹出窗口插件|[官网](https://github.com/craftpip/jquery-confirm)|
|jQuery EasyUI|基于jQuery的UI插件集合体|[官网](http://www.jeasyui.com)|
|React|界面构建框架|[官网](https://github.com/facebook/react)|
|Editor.md|Markdown编辑器|[官网](https://github.com/pandao/editor.md)|
|lmsiteAdmin|后台管理系统模板|[下载](https://github.com/jonny6015/lmsiteAdmin)|
|autoMail|邮箱地址自动补全插件|[下载](https://github.com/jonny6015/autoMail)
|lmsite.jprogress.js|	加载进度条插件|[下载](https://github.com/jonny6015/lmsite.jprogress.js)|
|lmsite-jtotop.js   |	返回顶部插件|[下载](https://github.com/jonny6015/lmsite-jtotop.js)|


|技术|中文说明|版本号| 官网 |
|:----|:----|:----|:----|
|HTML|前端页面|HTML5|[官网](http://www.w3school.com.cn/html/index.asp)|
|Spring Boot|微服务框架|2.0|[官网](http://spring.io/projects/spring-boot)|

#### 后端技术



#### 相关jar包



#### 中间件
















