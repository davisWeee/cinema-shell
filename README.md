# 映屿 / 星河影院 / 影视盒（Android）

核心产品（按片源分）：映屿（原生，片源由 vod-hub 远程路由）、星河影院（H5 壳）、影视盒（TVBox 配置，预发布）。赤焰影院、追光已停止更新（旧版本保留，不再维护）。

Android 影视客户端：检索、选集、多线路切换、弹幕、续播。无需注册登录。

> 官方下载页：**https://davisweee.github.io/cinema-shell/**（三条直链自动择优，含安装教程）
>
> 更新公告与反馈：Telegram 频道 **https://t.me/yuMovieH**（每次发版附说明与校验值，欢迎在评论区提问）

## 下载

| 应用 | 版本 | 大小 | 系统要求 | 链接 |
|---|---|---|---|---|
| 星河影院 | 1.4.1 | 15.0 MB | Android 7.0+ | [下载页](https://davisweee.github.io/cinema-shell/xinghe.html) · [GitHub 直链](https://github.com/davisWeee/cinema-shell/releases/download/v1.4.1/xinghe-1.4.1.apk) |
| 影视盒（预发布） | 2.1 | arm64 55 MB / armv7 47 MB | Android 5.0+ / 电视 | [arm64-v8a（手机/新盒子）](https://github.com/davisWeee/cinema-shell/releases/download/v2.1-yingshihe/yingshihe-2.1-arm64-v8a.apk) · [armeabi-v7a（32 位电视/旧盒子）](https://github.com/davisWeee/cinema-shell/releases/download/v2.1-yingshihe/yingshihe-2.1-armeabi-v7a.apk) · [运行模块](https://github.com/davisWeee/cinema-shell/releases/tag/yingshihe-runtimes-2.1) |
| 映屿 | 1.6.0 | 23.2 MB | Android 8.0+ | [下载页](https://davisweee.github.io/cinema-shell/yingyu.html) · [GitHub 直链](https://github.com/davisWeee/cinema-shell/releases/download/v1.6.0-yingyu/yingyu-1.6.0.apk) |

每个产品页都公布了安装包的 SHA-256，下载后可核对。安装包也可在 [Releases](https://github.com/davisWeee/cinema-shell/releases) 获取。

## 截图

**星河影院**

<img src="docs/img/shots/xinghe-2.jpg" width="160" alt="星河影院截图"> <img src="docs/img/shots/xinghe-3.jpg" width="160" alt="星河影院截图">

**赤焰影院**

<img src="docs/img/shots/chiyan-1.jpg" width="160" alt="赤焰影院截图">

**映屿**

<img src="docs/img/shots/yingyu-1.jpg" width="160" alt="映屿截图"> <img src="docs/img/shots/yingyu-2.jpg" width="160" alt="映屿截图">

**追光**

<img src="docs/img/shots/zhuiguang-1.jpg" width="160" alt="追光截图"> <img src="docs/img/shots/zhuiguang-2.jpg" width="160" alt="追光截图">

> 截图为真实运行画面；影视封面来自第三方站点。

## 安装

1. 下载 `.apk` 并点开。
2. 系统提示「禁止安装未知来源应用」时，点「设置」，给浏览器/文件管理器打开「允许安装未知应用」。
3. 点「安装」。小米/华为/OPPO/vivo 与 Play 保护的提示处理方法见 [安装指南](https://davisweee.github.io/cinema-shell/index.html#install)。
4. 装好后直接打开即可。

## 更新

- 星河影院、赤焰影院：应用内「检查更新」。
- 映屿、追光：回下载页获取新版，直接覆盖安装（需与已装版本同一签名，数据保留）。

## 常见问题

- **要注册吗？** 不要。观看进度、收藏只保存在本机。
- **有广告吗？** 本版本集成第三方广告 SDK，启动后加载广告 SDK，不弹授权提示。详见 [隐私政策](https://davisweee.github.io/cinema-shell/privacy.html)。
- **内容从哪来？** 第三方公开站点；应用不存储、不上传任何视频。内容可能随时失效，可在播放页换线路。
- **无法播放/安装失败？** 见下载页 FAQ，或到 [Issues](https://github.com/davisWeee/cinema-shell/issues) 反馈（注明产品、版本、手机型号）。

## 更新日志（当前版本）

**星河影院 1.4.1**
- 更新通道、广告配置与隐私政策地址迁移到新站点

**赤焰影院 1.3.3**
- 去掉站点自带的「收藏回家地址」「站内通知」等引流弹窗，打开即看片

**映屿 1.6.0**
- 片源路由改为远程下发，片源失效时无需更新应用即可切线
- 广告配置、隐私政策与更新通道地址迁移到新站点

**追光 1.7.1**
- 新增开屏、信息流、看视频免广告 30 分钟、切集和退出插屏

## 其他

- [隐私政策](https://davisweee.github.io/cinema-shell/privacy.html) · [用户协议](https://davisweee.github.io/cinema-shell/terms.html)
- 运营者：剑透人生工作室，联系邮箱 hedd8681@gmail.com
- 权利人通知：请邮件提供权属证明与内容位置，核实后处理。

仓库的 `docs/` 目录即 GitHub Pages 站点（`update.json`、`ads.json` 为应用读取的配置，请勿手动改动格式）。
