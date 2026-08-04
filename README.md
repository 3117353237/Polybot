# PolyBot

QQ 机器人框架，支持多框架协议接入、官机代发、插件系统等功能。

## 兼容框架

| 框架 | 协议 | 说明 |
|------|------|------|
| 小栗子 (xlz) | 原生SDK | ✔ 支持 |
| 萌Q | 原生SDK | ✔ 支持 |
| 萌尘 (MC) | 原生SDK | ✔ 支持 |
| MYQQ | 原生SDK | ✔ 支持 |
| Dulu | 原生SDK | ✔ 支持 |
| NapCat | OneBot 11 | ✔ 适配 |
| ABot | OneBot 11 | ✔ 适配 |
| LLOBot | OneBot 11 | ✔ 适配 |

## 文件说明

| 文件 | 说明 |
|------|------|
| `PolyBot.exe` | 主程序 |
| `HP.dll` | HP-Socket 通信库 |
| `MyQQApi.dll` | QQ API 接口库 |
| `photo.ico` | 程序图标 |
| `main/bin/` | 运行依赖（ffmpeg、silk 编解码、HPSocket4C 等） |
| `main/data/plugin/` | 插件目录 |

## 快速开始

1. 下载本仓库所有文件
2. 运行 `PolyBot.exe`
3. 按界面提示添加账号并配置

## 下载方式

```bash
git clone https://github.com/3117353237/Polybot.git
```

或直接在 GitHub 页面点击 `Code` -> `Download ZIP`。

## 更新日志

```
Ver:1.1.0 2026-05-23
【修复】官机代发群文件无后缀问题
【修复】一键配置回调地址设置失败
【修复】音乐卡片不显示歌手名
【优化】官机代发文件发送逻辑
```

## 说明

本仓库仅用于程序更新分发，不含源码。
