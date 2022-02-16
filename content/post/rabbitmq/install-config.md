---
title:       "RabbitMQ安装配置手册"
subtitle:    ""
description: ""
date:        2022-02-16T08:03:06+08:00
author:      "洛维奇"
image:       ""
tags:        ["RabbitMQ", "MQ"]
categories:  ["middleware" ]
---

 # RabbitMQ安装配置手册

 ## Windows安装包msi安装
 直接下载安装包安装文件
 ## 修改配置文件
 ``` shell
 rabbitmqctl.bat list_users
 Listing users ...
user    tags
guest   [administrator]
rabbitmqctl.bat change_password guest guest
 ```