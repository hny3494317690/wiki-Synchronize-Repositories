---
title: CIVEarth新手教程
description: CIVEarth新手教程（2022.6修订版）
published: true
date: 2022-08-20T16:11:33.823Z
tags: 旧版复刻
editor: markdown
dateCreated: 2022-08-20T15:41:16.051Z
---

CIVEarth新手教程（2022.6修订版）

本文1750字，大约需要6分钟。游玩前请务必完整阅读。

文档原链接↓↓  本页面为原链接的复制：
<a href="https://cloud.hny3494317690.top:100/zh/civ%E6%9C%8D%E5%8A%A1%E5%99%A8%E8%BF%9B%E5%85%A5%E6%8C%87%E5%8D%97" target="_blank">进入指南</a><a href="https://docs.qq.com/doc/DREh1YUlFb3FyZXh6" target="_blank">守则</a><a href="https://docs.qq.com/doc/DRGd0QktiT2Vsemxy" target="_blank">指令大全</a><a href="https://docs.qq.com/sheet/DRExUZkNrYlVwQ3pD?u=a3c1dc273c55442bae42ca394fab74e2&tab=BB08J2" target="_blank">价目表</a><a href="https://docs.qq.com/doc/DRGNGTm9vWGhYRE1x" target="_blank">MCU指南</a><a href="https://docs.qq.com/doc/DRExacU9ZSU5raVBS" target="_blank">奇观委员会</a>

正版玩家，直接进入: server.civearth.xyz:20101

非正版JAVA玩家，须在littleskin.cn中注册并配置，参考进入指南

# 我在哪

正式进入CivEarth前需进行答题并将答题完成的截图发到qq群，请确保答题前阅读本教程及<a href="https://docs.qq.com/doc/DREh1YUlFb3FyZXh6" target="_blank">守则</a>。答题输入对应指令后会被传送到埃塞俄比亚的新手村中。可以通过查看<a href="http://server.civearth.xyz:20103" target="_blank">地图</a>确定自己的位置。注意：仅当玩家位于露天且亮度等级高于10时才可在地图上显示。可以通过`/dynmap hide`隐藏自己的位置。

# 我该干什么

在这个服务器中，你可以从两个方面去选择：自力更生独立建立城镇和国家或是加入现有城镇。如果愿意了解更多指令以及更完整的玩法，我们推荐充分了解<a href="https://docs.qq.com/doc/DRGd0QktiT2Vsemxy" target="_blank">指令大全</a>后自力更生。

## 获取金锭（货币）

1. 挖矿：服务器中的金矿分布与现实地球中的金矿分布相似，因此你可以很容易地在地下获取大量金，但考虑到开服已经有较长的时间，部分区域的矿物已被开发殆尽。
2. 交易：输入`/civ`后，点击右上角末影珍珠即可前往官方交易所(建议未建城玩家不要使用否则将难以离开)；输入`/ca gui`即可进入全球玩家市场,`/ca help`查看全球市场的用法，请在购买/销售物品时查看价目表进行对照以免吃大亏！
3. 钓鱼：收益较低,不建议新手前期通过钓鱼获取金锭。tips:本服猪灵不会掉落金锭。

## 周游世界

出生时给予的食物和装备是一次性的，在食物吃完或者被怪物击倒之前，请收集木头石头进行初步的挖矿，当获得足够物资后再前去目的地是更保险的做法。对于生存老手，可直接通过出生点传送门前往目的城市附近。本服务器在自己城市外死亡时掉落所有装备，请各位玩家注意安全

## 特殊合成

![CzSwM.png](https://s1.328888.xyz/2022/06/10/CzSwM.png)

## 基础指令

`/pay [ID] [amount]`（支付玩家金锭）

`/ca gui` （打开全球市场界面）

`/civ` （打开服务器菜单）

`/party create [name]`（创建一个派系）

`/party invite [ID]` (邀请玩家加入你的派系)

`/ptp [ID]` (申请传送到同派系玩家）

`/bottle get max` (将所有经验转换为经验瓶）

## 建立城镇

建立城镇前，你需要准备至少256金（推荐多于512金），输入`/t new [name]`(注意:城镇名字必须是英文，同时，必须是现实附近的地名。建议不擅自在已有宣称的地区建立城镇，否则可能影响游戏体验）创建城镇。创建城镇后，请立刻输入`/t deposit [数量]`给你的城镇银行存钱，否则中午12点扣除维护费时余额不足导致倒闭（城镇的基本日维护费为2.5金）浪费建城的金锭！

### 发展城镇

城镇要发展，首先需要扩大城镇范围。在准备扩大城镇范围时，请确保你给你的城镇准备了充足的金锭。站在与城镇相邻的区块（可通过地图查看）中输入`/t claim`**消耗**10金和10人力(人力可以输入`/t`后查看manpower，人力在每天中午12点结算，数值为人力最大值的1%）。更大的城镇，可以保护更多区域以满足城镇的日常需求。指令请查看指令大全

### 建立国家

建立国家与建立城镇不同，建立国家不仅需要1024金，每日维护费也会提升到10金,在建立国家前，请确保你的城镇已具有至少3点总文化值，下图为服务器部分国家宣称。

![46113c1531afd2618e08af7bec6eb39d.png](https://img1.imgtp.com/2022/06/10/x9nsNH3D.png)

确保你的城市拥有足够的文化（输入`/t`确定三个值之和大于3）,输入`/n new` 国家名字（国家名字较为随意，但必须是英文）即可建立国家。建立国家后，将金锭存入国家银行的指令是`/n deposit 数量`因此，请确保你的城市和国家的银行内有充足的金锭，否则最后将面临倒闭:(

### 建立国家后

`/mcu` 了解MCU指令的用法，插件指南MCU指南

`/n spawn` 国家名字 (回到你的首都或传送到他国首都）

`/n invite` 城镇名字 （邀请某个城镇加入你的国家）

### 建造奇观

你的国家现在已经建立，但只有一堆火柴盒可不算是一个国家，你可以在全国各地建造各种不同的奇观，来给你的国家带来一定的加成。奇观的基本标准大小为40格×40格,且具有一定美感，可以上报给奇观委员会（可戳）

## 加入城镇

如果无力建立城镇或有朋友推荐，可以去加入已建立的城镇。本服有玩家自己修建的地狱交通和主世界交通，可以帮助你去到其他城镇。**注意：请先多参观完城镇后，再选择你自己喜欢的城镇，建议不要前往和加入有争议的城镇，否则后果自负。**当然，如果你不喜欢这个城镇,或想自己出去发展建立新镇等需要离开城镇的，可以输入`/t leave`离开城镇，其他人不能以离开城镇为理由追杀

加入城镇后的常用指令

`/plot claim` (买下城镇内出售的私人地皮）

`/t leave` （离开城镇）

`/tfly` 城镇内飞行（前提是要城主给予权限）

# 其他链接
<a href="https://docs.qq.com/form/page/DRENCRGlLd3dieFpy" target="_blank">服务器管理组报名</a><a href="https://qun.qq.com/qqweb/qunpro/share?_wv=3&_wwv=128&appChannel=share&inviteCode=2kGS4V&appChannel=share&businessType=9&from=246610&biz=ka" target="_blank">qq频道</a>


如果你看到这里，那么恭喜，你已经了解了服务器大致的玩法，祝各位新人在本服务器玩得开心