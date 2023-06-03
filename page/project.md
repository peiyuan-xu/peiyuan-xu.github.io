---
layout: page
title: Project
permalink: /project/
---

## 面向服务链的通信管理与服务编排系统 (2019)
Service communication management system(SCMS) provides communication management between services.
Main component：
- DB using SqlAlchemy
- Control component is responsible for create queue
- Gatherer component is responsible for statistics messages
- Strategy component is responsible for give some deployment scheme
- API srvice component is responsible for call Zun、Glance
[SCMS source code][scms-source-code]
[scms-source-code]: https://github.com/peiyuan-xu/SCMS

SCMSTest provides traffic simulation and performance testing for SCMS.
[SCMSTest source code][scms-test-source-code]
[scms-test-source-code]: https://github.com/peiyuan-xu/SCMSTest

When using SCMS(Service communication management system) to manage the communication between services. 
This is a lib for the user's services to send or receive message. In SCMSDemo, we provide a demo 
service using scmsimagelib, this user defined service is in service package.
[SCMSDemo source code][scms-demo-source-code]
[scms-demo-source-code]: https://github.com/peiyuan-xu/SCMSServiceDemo

## 全球比特币交易网络构建系统 (2018)
实时爬取比特币网络所有的交易，通过交易相关性对同一个用户的多个链上账户进行聚合，并将用户之间的交易存储在图书数据库（Neo4j），
支持查询用户到用户之间的聚合交易。
[BlockChainGraph source code][blockchain-graph-source-code]
[blockchain-graph-source-code]: https://github.com/peiyuan-xu/BlockChainGrap

## 华为软件挑战赛 (2017, 2016)
最优视频服务器选址问题，最优路由问题，进行问题建模并通过智能算法对NP问题进行求解
[CDN边缘视频服务器选址系统 source code][cdn-position-source-code]
[cdn-position-source-code]:https://github.com/peiyuan-xu/cdn-position
[路由选址系统 source code][router-source-code]
[router-source-code]:https://github.com/peiyuan-xu/route-selection

## 数学建模挑战赛 (2016)
集训、国赛、美赛算法实现，各种智能算法（遗传算法、模拟退火算法、蚁群算法、粒子算法、神经网络算法等）实现和优化。
[数学建模各类问题和比赛 source code][router-source-code]
[cdn-position-source-code]:https://github.com/peiyuan-xu/cdn-position