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

按系统选择安装包即可；请忽略更新专用包，以及 GitHub 自动附带的 **Source code** 压缩包。

| 资源 | 谁需要 |
|------|--------|
| `Moxus_*_aarch64.dmg` | **macOS**（Apple 芯片）全新安装 |
| `Moxus_*_x64-setup.exe` | **Windows**（x64）全新安装（NSIS） |
| `latest.json` | 应用内更新（自动使用，无需手动下载） |
| `Moxus_*.app.tar.gz` / `*.nsis.zip` | 应用内更新（自动使用，无需手动下载） |

当前官方平台：**macOS arm64**、**Windows x64**。

### 安装（macOS）

1. 从 Latest Release 下载 `.dmg`。
2. 打开磁盘映像，将 **Moxus** 拖入「应用程序」。
3. 从「应用程序」或 Spotlight 启动 Moxus。

若首次打开被 Gatekeeper 拦截，可到 **系统设置 → 隐私与安全性** 允许打开，或对应用图标右键选择 **打开**。（尚未接入 Apple 公证。）

### 安装（Windows）

1. 从 Latest Release 下载 `*-setup.exe`。
2. 运行安装程序并按提示完成。
3. 从开始菜单启动 **Moxus**。

当前未做 Authenticode 签名，SmartScreen 可能提示未知发布者；若信任本发布渠道，可选择 **更多信息 → 仍要运行**。

### 更新

已安装版本可在 **设置 → 关于** 中检查更新。更新包会在安装前完成签名校验。

## 本仓包含 / 不包含

| 包含 | 不包含 |
|------|--------|
| Moxus Desktop 公开下载与更新分发 | 源码镜像 |
| 发布安装包与 `latest.json` | 产品问题跟踪（请走正式支持渠道） |
| 按版本管理的 GitHub Release | 未签名的日常构建产物 |

## 许可

本仓库中的发布产物为专有软件，详见 [`LICENSE`](./LICENSE)。

Copyright © Moxus. 保留所有权利。
