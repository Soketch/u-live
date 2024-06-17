<p align="center">
  <a href="https://live.hsslive.cn" target="_blank">
    <img
      width="200"
      src="https://resource.hsslive.cn/billd-live/image/240160ddbc14367f7e0126c1f5b09b69.svg"
      alt="Billd-Live logo"
    />
  </a>
</p>

<h1 align="center">
  U-Live
</h1>

<p align="center">
  基于Vue3 + WebRTC + Node + SRS + FFmpeg搭建的直播间
</p>

## 简介

Live直播间，目前实现了类似 [bilibili 的 Web 在线直播](https://live.bilibili.com)功能，即你（房主）可以发布直播，别人进入你的直播间后能看到你的直播内容；而你也可以作为观众，进入别人的直播间看别人的直播内容。


## 功能

- [x] 原生 webrtc 推拉流
- [x] srs webrtc 推流，`http-flv` 或 `hls`拉流
- [x] msr 推流，ffmpeg转码，`http-flv` 或 `hls`拉流
- [x] 一对一打PK
- [x] 一对多打PK
- [x] 多对多打PK
- [x] 前端混流
- [x] 推流鉴权
- [x] 拉流鉴权
- [x] [OBS](https://github.com/obsproject/obs-studio)、[FFmpeg](https://ffmpeg.org)推流
- [x] 用户模块（qq 登录）
- [x] 支付模块（支付宝当面付）
- [x] 订单模块
- [x] 商品模块
- [x] 适配移动端
- [x] 在线后台
- [x] 多平台转推（b站、虎牙直播）
- [x] 接入腾讯云-云直播
- [ ] 接入腾讯云-实时音视频TRTC

## 技术栈

- 前端相关：[Vue3](https://vuejs.org) 以及相关技术栈、`Typescript`、`WebRTC`、`WebCodecs`、`Web Audio`、`Web Workder`、`Canvas`
- 后端相关：[Nodejs](https://nodejs.org) 以及相关技术栈、`Koa2`、`Sequelize`、`Mysql`、`Redis`、`Socket.io`
- 流媒体服务器相关：[SRS](https://ossrs.net)、 [FFmpeg](https://ffmpeg.org)、[Coturn](https://github.com/coturn/coturn)
- Docker 相关：[Docker](https://www.docker.com)


### 电脑端（web）

- 首页

<img
  src="https://github.com/galaxy-s10/billd-live/assets/61055341/95849774-1df0-4a59-b726-8d3bc0795619" 
  style="width:800px"
/>

- 进入直播间

<img
  src="https://github.com/galaxy-s10/billd-live/assets/61055341/91ac3f5f-b06d-46b3-84bc-ab6e0add4d5b" 
  style="width:800px"
/>

- 发起直播

<img
  src="https://github.com/galaxy-s10/billd-live/assets/61055341/81e2f413-8470-42ab-bee7-699e2f8f0290" 
  style="width:800px"
/>

- 排行榜

<img
  src="https://github.com/galaxy-s10/billd-live/assets/61055341/6d7d79b6-e8b9-42ff-9e25-d44c41948579" 
  style="width:800px"
/>
