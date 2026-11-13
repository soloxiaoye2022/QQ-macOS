# QQ for macOS 历史版本镜像

[简体中文](README.md) | [繁體中文](README.zh-TW.md) | [English](README.en.md)

归档腾讯 QQ macOS 客户端的历史与最新安装包。

所有文件均取自腾讯官方下载源或社区归档仓库，未做任何修改。

## 下载

- 最新版本：[最新 Release](https://github.com/soloxiaoye2022/QQ-macOS/releases/latest)
- 历史版本：[全部 Releases](https://github.com/soloxiaoye2022/QQ-macOS/releases)

## 说明

全部为 Universal 包，同时支持 Intel 与 Apple Silicon。

## 文件命名

```
QQ-<版本号>-universal.dmg
```

示例：`QQ-7.0.3-54276-universal.dmg`

## 校验

每个 Release 附带 `SHA256SUMS`：

```bash
shasum -a 256 QQ-7.0.3-54276-universal.dmg
```

## 版本来源

| 来源 | 覆盖范围 |
| --- | --- |
| [A-Randomm-User/macOS-save](https://github.com/A-Randomm-User/macOS-save) | 6.9.6 至 7.0.3 全部版本 |
| 腾讯官方 CDN | 7.0.1 至 7.0.3 直链仍可用 |

## 安装

打开 dmg，将 QQ 拖入「应用程序」。

首次启动若提示「无法验证开发者」，前往「系统设置 → 隐私与安全性」点击「仍要打开」。

## 说明

本仓库仅做镜像分发，不提供任何修改或破解版本。QQ 客户端版权归腾讯所有。
