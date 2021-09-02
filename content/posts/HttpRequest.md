---
title: "Http Request"
date: 2021-08-10T16:12:52+08:00
draft: true
---

### Spring4

RestTemplate
    - JDK (Default)
    - Apache Http Components (连接池)
    - OkHttp (Android常用)

### Spring5

WebClient
    - WebFlux
    - 反应式

### Java 11

HttpClient
    - HTTP/2 
    - 同步、异步
    - 连接池（暂时不知道如何进行配置）

### 抉择

Spring5以下版本，直接选择Apache Http Components OR RestTemplate + Apache Http Components