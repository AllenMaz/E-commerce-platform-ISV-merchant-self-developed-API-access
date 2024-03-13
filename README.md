# 各电商平台订单API接入(ISV/商家自研)

## 前言
详细介绍作为ISV(Independent Software Vendors独立软件开发商)或者商家自研的情况下，如何对接各电商平台的订单API，包括<font color="#03A9F4">订单下载</font>，<font color="#03A9F4">运单号获取</font>，<font color="#03A9F4">面单打印</font>,<font color="#03A9F4">订单出库物流信息回传</font>，<font color="#03A9F4">商品下载</font>，<font color="#03A9F4">库存同步</font>等。从而实现将各电商平台的订单管理，发货等操作集成到自己的系统中。

## 支持对接的电商平台

![TM](./images/天猫.png "天猫") | ![TB](/images/淘宝.png "淘宝") | ![JD](/images/京东.png  "京东") | ![DY](/images/抖音.png "抖音") | ![PDD](./images/拼多多.png "拼多多") | ![PDD](./images/快团团.png "快团团") | ![KS](./images/快手.png "快手") | ![DD](./images/当当.png "当当")
--- | --- | --- | --- | --- | --- | --- | --- |
![WXSPH](./images/微信视频号.png "微信视频号") | ![YZ](./images/有赞.png "有赞") | ![XHS](./images/小红书.png "小红书") | ![WPH](./images/唯品会.png "唯品会")| ![1688](./images/1688.png "1688")| ![1688TGC](./images/阿里巴巴.png "1688淘工厂")| ![DW](./images/得物.png "得物")| ![wb](./images/微博.png "微博")
![SN](./images/苏宁.png "苏宁") | ![DV](./images/大V店icon.png "大V店") | ![WYKL](./images/网易考拉2.png "网易考拉") | ![WD](./images/微店.png "微店") | ![RR](./images/人人店icon.png "人人店")

## 目录

* [x] [项目架构](#项目架构)
* [ ] 各电商平台API对接详解 [<span style="color:red">待更新</span>]
  - [天猫/淘宝](./天猫_淘宝/index.md)
  - [京东](./京东/index.md)
  - [抖音](./抖音/index.md)
  - [抖音代发](./抖音代发/index.md)
  - [拼多多](./拼多多/index.md)
  - [拼多多快团团](./拼多多快团团/index.md)
  - [快手](./快手/index.md)
  - [快手代发](./快手代发/index.md)
  - [当当网](./当当/index.md)
  - [微信视频号](./微信视频号/index.md)
  - [有赞](./有赞/index.md)
  - [小红书](./小红书/index.md)
  - [唯品会](./唯品会/index.md)
  - [1688](./1688/index.md)
  - [1688淘工厂](./1688淘工厂/index.md)
  - [得物](./得物/index.md)
  - [微博](./微博/index.md)
  - [苏宁易购](./苏宁易购/index.md)
  - [网易考拉](./网易考拉/index.md)
  - [微店](./微店/index.md)
  - [大V店](./大V店/index.md)
  - [人人店](./人人店/index.md)
* [ ] 如何打单发货 [<span style="color:red">待更新</span>]
  - 各平台订单如何获取运单号
  - 各平台订单如何打印面单（各平台打印控件接入）
  - 各平台订单如何回传发货物流信息
* [ ] 通过阿里奇门对接外部系统 [<span style="color:red">待更新</span>]
  - 作为[奇门ERP]()角色对接下游仓库
  - 作为[奇门WMS]()角色对接上游ERP
* [ ] 如何设计自己的商城API [<span style="color:red">待更新</span>]
  - 开放平台设计方案及架构
  - 基础API设计（订单API，退款API，出库API,库存同步API等）
* [ ] 设计自己的商品发布系统，将商品一件发布到各电商平台 [<span style="color:red">待更新</span>]


## 项目架构

待更新

## 微信交流

扫码加我，请先主动做自我介绍，然后拉你进微信交流群：

<img src="./images/wch.png" width="50%" height="50%">
## License

[MIT](LICENSE) © 2024-present, HeiZhu