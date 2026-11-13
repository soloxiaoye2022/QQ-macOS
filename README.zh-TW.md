# QQ for macOS 歷史版本鏡像

[简体中文](README.md) | [繁體中文](README.zh-TW.md) | [English](README.en.md)

歸檔騰訊 QQ macOS 客戶端的歷史與最新安裝包。

所有檔案均取自騰訊官方下載源或社群歸檔倉庫，未做任何修改。

## 其它平台

| 平台 | 倉庫 |
| --- | --- |
| Linux | [QQ-Linux](https://github.com/soloxiaoye2022/QQ-Linux) |
| Windows | [QQ-Windows](https://github.com/soloxiaoye2022/QQ-Windows) |
| macOS | 當前 |
| Android | [QQ-Android](https://github.com/soloxiaoye2022/QQ-Android) |

## 下載

- 最新版本：[最新 Release](https://github.com/soloxiaoye2022/QQ-macOS/releases/latest)
- 歷史版本：[全部 Releases](https://github.com/soloxiaoye2022/QQ-macOS/releases)

## 說明

全部為 Universal 包，同時支援 Intel 與 Apple Silicon。

## 檔案命名

```
QQ-<版本號>-universal.dmg
```

範例：`QQ-7.0.3.54276-universal.dmg`

## 校驗

每個 Release 附帶 `SHA256SUMS`：

```bash
shasum -a 256 QQ-7.0.3.54276-universal.dmg
```

## 版本來源

| 來源 | 涵蓋範圍 |
| --- | --- |
| [A-Randomm-User/macOS-save](https://github.com/A-Randomm-User/macOS-save) | 6.9.6 至 7.0.3 全部版本 |
| 騰訊官方 CDN | 7.0.1 至 7.0.3 直連仍可用 |

## 安裝

打開 dmg，將 QQ 拖入「應用程式」。

首次啟動若提示「無法驗證開發者」，前往「系統設定 → 隱私與安全性」點擊「仍要打開」。

## 說明

本倉庫僅做鏡像分發，不提供任何修改或破解版本。QQ 客戶端版權歸騰訊所有。
