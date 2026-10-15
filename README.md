# MusicAgent 下载

面向音乐初学者的本地音乐工作台（Windows x64）。

本仓库**只用于发布安装包**，不包含源码。

## 下载

前往 [Releases](https://github.com/xiazhiaidao/musicagent-releases/releases) 页面下载最新版本：

- **`MusicAgent-<版本>-win-x64.exe`** — 安装包，可选择安装位置并创建桌面快捷方式
- **`MusicAgent-<版本>-win-x64.zip`** — 免安装，解压后运行其中的 `MusicAgent.exe`
- **`SHA256SUMS.txt`** — 校验值

桌面版自带界面和 Node.js 运行时，**不必启动终端或单独安装 Node.js**。

## 系统要求

- Windows x64
- 首次下载约 1.5–4 GB（翻唱 / 歌声引擎，按需在应用内下载）
- CPU 需预留 10 GB，GPU 需预留 16 GB

## 注意

- 当前是**未签名的** Alpha 版本，Windows 可能提示未知发布者。只在本机完成验证，尚未完成其他电脑的兼容测试。
- 安装包**不含**声音模型（`.pth` / `.index`）、Python、FFmpeg 或第三方权重，需在应用内自行准备，并确保有相应使用权。
- 应用使用的第三方组件**另有各自许可，部分含非商业限制**（例如 OpenVPI 声码器为 CC BY-NC-SA 4.0）。使用前请确认许可条件。
