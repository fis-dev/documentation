fis用户使用手册
-------------------------

![](docs/images/logo_120x120.png?raw=true)

1. 概述
1. 工作原理
1. 命令行
    1. fis release [options]
        1. 发布目标
        1. 文件名加md5戳，url加域名
        1. 压缩、校验、测试、打包
        1. 指定项目根目录或项目配置文件
        1. 文件监听与浏览器自动刷新
        1. 缓存清除与单机多人编译
        1. 输出冗余信息
    1. fis server <command> [options]
        1. 启动nodejs服务器
        1. 启动jetty服务器
        1. 启动php服务器
    1. fis install <name> [options]
1. 配置说明
    1. 系统配置
    1. 目录规范与域名配置
    1. 插件配置
    1. 部署配置
1. 资源表
    1. 什么是资源表
    1. 资源表数据结构
    1. 打包配置与资源表结构
    1. 利用资源表进行框架设计
    1. 设置源码文件是否入表
1. 插件开发
    1. 插件工作原理
    1. 系统内置插件
    1. 文件内容处理与校验插件
        1. parser - 语言编译插件
        1. preprocessor - 标准预处理插件
        1. postprocessor - 标准后处理插件
        1. lint - 校验插件
        1. test - 测试插件
        1. optimizer - 压缩插件
    1. 打包插件
        1. prepackager - 打包预处理插件
        1. packager - 打包插件
        1. spriter - csssprites插件
        1. postpackager - 打包处理插件
1. 二次包装
    1. 包装原理
    1. 编写index.js
    1. 甄选插件
    1. 发布npm
1. 实战运用
    1. 开发部署规范设计
        1. nodejs项目开发部署配置设计
        1. hybird项目开发部署配置设计
        1. 将所有资源（字体、图片、js、css）合并到一个页面上
        1. 面向灰度发布的开发部署规范设计
    1. 纯前端解决方案
        1. 与requirejs结合
        1. 与seajs+aralejs结合
        1. 与angularjs结合
    1. 与后端模板引擎结合
        1. jsp/java
        1. smarty/php
        1. Django/python
        1. go语言方案