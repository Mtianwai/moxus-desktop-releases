<p align="center">
  <img src="./moxus-logo.png" alt="Moxus" width="96" />
</p>

# Moxus Desktop 发布仓

**Language / 语言:** [English](./README.md) | 中文

本仓库是 **Moxus Desktop** 的公开分发渠道，提供安装包与应用内更新元数据。

此处**仅存放发布产物**，不包含应用程序源码。

## 下载

请使用最新的 GitHub Release：

**[下载 Moxus Desktop](https://github.com/Mtianwai/moxus-desktop-releases/releases/latest)**

| 资源 | 用途 |
|------|------|
| `Moxus_*_aarch64.dmg` | Apple 芯片 Mac（macOS arm64）全新安装 |
| `Moxus_*.app.tar.gz` + `.sig` | 应用内更新使用的签名包 |
| `latest.json` | 更新清单（`releases/latest/download/latest.json`） |

当前官方首发平台：**macOS arm64**。后续版本可能增加其他平台。

### 安装（macOS）

1. 从 Latest Release 下载 `.dmg`。
2. 打开磁盘映像，将 **Moxus** 拖入「应用程序」。
3. 从「应用程序」或 Spotlight 启动 Moxus。

若首次打开被 Gatekeeper 拦截，可到 **系统设置 → 隐私与安全性** 允许打开，或对应用图标右键选择 **打开**。

### 更新

已安装版本可在 **设置 → 关于** 中检查更新。更新包会在安装前完成签名校验。

## 本仓包含 / 不包含

| 包含 | 不包含 |
|------|--------|
| Moxus Desktop 公开下载与更新分发 | 源码镜像 |
| 已签名安装包与 `latest.json` | 产品问题跟踪（请走正式支持渠道） |
| 按版本管理的 GitHub Release | 未签名的日常构建产物 |

## 许可

本仓库中的发布产物为专有软件，详见 [`LICENSE`](./LICENSE)。

Copyright © Moxus. 保留所有权利。
