
<div align=center>

![Image text](https://github.com/AwakenCN/Almost-Famous/blob/master/famous-static/images/awakencn.jpg?raw=true)

[![build](https://img.shields.io/travis/AwakenCN/Almost-Famous)](https://travis-ci.org/AwakenCN/Almost-Famous)
[![官网](https://img.shields.io/badge/%E5%AE%98%E7%BD%91-page-blue)](https://awakencn.github.io/Almost-Famous/)
[![QQ群](https://img.shields.io/badge/QQ%E7%BE%A4-670252084-yellow)](https://jq.qq.com/?_wv=1027&k=5gXmfE2)
[![作者](https://img.shields.io/badge/%E4%BD%9C%E8%80%85-Noseparte-orange)](https://github.com/noseparte)
[![Netty入门](https://img.shields.io/badge/%E5%AD%A6%E4%B9%A0-Netty%E5%85%A5%E9%97%A8-ff69b4.svg)](doc/study/mulu.md)


</div>

## 申明

本项目入驻[**AwakenCN**](https://github.com/AwakenCN)开源组织，后续将继续更新调整，部分API后续会更改，感谢每一位朋友的支持与关注。

## 简介

***(Almost-Famous)Java GameServer Framework***

    Almost-Famous(成名之路) —— 架构使用 -> (
            SpringBoot, Netty, Maven, SpringCloud
        ).explain(多进程分布式框架卡牌游戏开源项目，包括Cloud、Unique、Login、Game、Match、Battle 服务).

## 项目组织模块

~~~
Root project 'Almost-Famous'
+--- Project ':famous-battle'
+--- Project ':famous-cloud'
+--- Project ':famous-common'
+--- Project ':famous-game'
+--- Project ':famous-login'
+--- Project ':famous-match'
+--- Project ':famous-static'
\--- Project ':famous-unique'
~~~

* [famous-unique Unique服(so TM what? 用来生成唯一ID)](./famous-unique/README.md)
* [famous-cloud 传说中的微服务(服务注册与发现)](./famous-unique/README.md)
* [famous-Login 哪个游戏还没个登录啊](./famous-login/README.md)
* [famous-Game 断剑重铸之日，其势归来之时。 哈撒给，面对疾风吧](./famous-game/README.md)
* [famous-Match 上来就匹配一波, wo就知道你会选我](./famous-game/README.md)
* [famous-Battle 战个痛快！Penta Kill! Legendary!](./famous-battle/README.md)
* [famous-static Almost-Famous世界的藏宝图](./famous-battle/README.md)

## 项目架构图

![Image file](https://noseparte-1256862255.cos.ap-chengdu.myqcloud.com/TIM%E5%9B%BE%E7%89%8720191214174229.png)

## 项目研发日志更新

* [项目研发进度](./famous-static/doc/almost-famous/progress.md)

## 快速开始

1. 使用git下载代码 git clone https://github.com/AwakenCN/Almost-Famous.git;
2. 将代码导入带有maven插件的IDE(推荐使用IntelliJ IDEA);
3. 保证本地安装Maven、mongodb、redis等服务, 以及lombok插件;
4. 启动Cloud服务端，入口为FamousCloudApplication类;
5. 启动Unique服务端，入口为RpcServer类;
6. 启动Login服务端，入口为FamousLoginApplication类;
7. 启动Game服务端，入口为FamousGameApplication类;
7. 启动Game服务端，入口为FamousMatchApplication类;
8. 启动Battle服务端，入口为FamousBattleApplication类;

![Almost-Famous服务启动界面](https://noseparte-1256862255.cos.ap-chengdu.myqcloud.com/20191214182137.png)

## 一起交流

    如果您发现bug，或者有任何疑问，请提交issue !!
    或者加入QQ交流群：780465774

* [QQ群 670252084](https://jq.qq.com/?_wv=1027&k=5gXmfE2)

 (Chinese ver.) 持续更新中，保持关注。
