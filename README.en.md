# QQ for macOS Release Archive

[简体中文](README.md) | [繁體中文](README.zh-TW.md) | [English](README.en.md)

Archived installers for the Tencent QQ macOS client, past and present.

Every file comes from Tencent's official download sources or community archives, unmodified.

## Other platforms

| Platform | Repository |
| --- | --- |
| Linux | [QQ-Linux](https://github.com/soloxiaoye2022/QQ-Linux) |
| Windows | [QQ-Windows](https://github.com/soloxiaoye2022/QQ-Windows) |
| macOS | current |
| Android | [QQ-Android](https://github.com/soloxiaoye2022/QQ-Android) |

## Download

- Latest: [latest release](https://github.com/soloxiaoye2022/QQ-macOS/releases/latest)
- Historical: [all releases](https://github.com/soloxiaoye2022/QQ-macOS/releases)

## Notes

All builds are Universal, supporting both Intel and Apple Silicon.

## File naming

```
QQ-<version>-universal.dmg
```

Example: `QQ-7.0.3.54276-universal.dmg`

## Verify

Each release ships a `SHA256SUMS` file:

```bash
shasum -a 256 QQ-7.0.3.54276-universal.dmg
```

## Provenance

| Source | Coverage |
| --- | --- |
| [A-Randomm-User/macOS-save](https://github.com/A-Randomm-User/macOS-save) | 6.9.6 through 7.0.3, all versions |
| Tencent official CDN | 7.0.1 to 7.0.3 direct links still live |

## Install

Open the dmg and drag QQ into Applications.

If macOS blocks the first launch, go to System Settings → Privacy & Security and click "Open Anyway".

## Notes

This repository only mirrors and distributes packages. It provides no modified or cracked clients. The QQ client is copyright Tencent.
