# Totally not something sus
These instructions are in Chinese, specifically simplified. I've just simply cloned this off the original repository since Heroku likes blacklisting repos. I've tried translate parts of it (for my own reference, i live in hk so i understand most simplified)

**若需部署 (censored)，请转到分支。** click here to deploy (censored) (removeduwuwu)

## 概述 Overview

本专案用于在 sus 上部署 sus，在合理使用的程度下，本镜像不会因为大量占用资源而导致封号。 This repo is used to deploy sus to sus, that's about it. 

部署完成后，每次启动应用时，运行的 sus 将始终为最新版本 sus updates itself after deployment so yea

## 部署 Deployment

### 步骤 

 1. Fork 本专案到自己的 GitHub 账户（用户名以 `example` 为例） fork  this project to github (using `example` as a reference)
 2. 修改专案名称，注意不要包含 `sus` 和 `sus` 两个关键字（修改后的专案名以 `demo` 为例）modify the project name and make sure you don't include the words (censored) and (censored) becz blocking
 3. 修改 `README.md`，将(gone)替换为自己的内容（如 `example/demo`）modify (gone) with ur repo name

> [![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/MainDabRblx/ray-funnies) click here to deploy

 4. 回到专案首页，点击上面的链接以部署 sus

### 变量 variables and stuff

对部署时需设定的变量名称做如下说明。 these are variables that need to be set when you go in

this is pretty self explanatory

| 变量 | 默认值 | 说明 |
| :--- | :--- | :--- |
| `ID` | `ad806487-2d26-4636-98b6-ab85cc8521f7` | SUSMess 用户主 ID，用于身份验证，为 UUID 格式 |
| `AID` | `64` | 为进一步防止被探测所设额外 ID，即 SUSAlterID，范围为 0 至 65535 |
| `WSPATH` | `/` | WebSocket 所使用的 HTTP 协议路径 |
(ignore the sus)

## 接入 CloudFlare (also self explanatory)

以下两种方式均可以将应用接入 CloudFlare，从而在一定程度上提升速度。 you can connect this thingy to cloudflare (for  s p e e d  i'm assuming)

 1. 为应用绑定域名，并将该域名接入 CloudFlare bind domain to cloudflr
 2. 通过 CloudFlare Workers 反向代理 reverse
 
## 注意 note

 1. **请勿滥用本专案，类似 SUS 的免费服务少之又少，且用且珍惜** no abuse plss wuu
 2. 若使用域名接入 CloudFlare，请考虑启用 TLS 1.3 enable tls1.3 if ur gonna do it via cloudflare
 3. AWS 绝大部分 IPv4 地址已被 Twitter 屏蔽 twitter is somehow blocking ip addresses from aws lmao
