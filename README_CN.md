# Aseprite 自动构建器

[![Build](https://github.com/bonorca/Aseprite-auto-builder/actions/workflows/build-aseprite.yml/badge.svg)](https://github.com/bonorca/Aseprite-auto-builder/actions/workflows/build-aseprite.yml)
[![Verified with Aseprite](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2Fbonorca%2FAseprite-auto-builder%2Fmain%2F.github%2Fbadges%2Fverified.json&query=%24.version&label=verified%20with%20Aseprite&color=brightgreen)](https://github.com/bonorca/Aseprite-auto-builder/actions/workflows/build-aseprite.yml)
[![Last verified](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2Fbonorca%2FAseprite-auto-builder%2Fmain%2F.github%2Fbadges%2Fverified.json&query=%24.date&label=last%20verified&color=blue)](https://github.com/bonorca/Aseprite-auto-builder/actions/workflows/build-aseprite.yml)

使用 GitHub Actions 自动编译最新版 [Aseprite](https://github.com/aseprite/aseprite)（Windows）。
每天自动检查新版本并编译。

[English](README.md)

## 使用方法

1. **Fork** 本仓库
2. 进入 **Actions** 页面
3. 启用 Workflow
4. 选择 **"Build and release Aseprite"** → **Run workflow**
5. 等待约 20 分钟，然后在 **Releases** 中下载 zip 文件

之后工作流会每天自动检查 Aseprite 是否有新版本，有则自动编译。

<img src="https://github.com/user-attachments/assets/e4b7340a-8204-4ce3-9f60-e718a6b48ad2" width="600">
<img src="https://github.com/user-attachments/assets/2765b8ca-4782-47ee-878b-c77d897979a5" width="600">

- 注意：fork 仓库只能是公开的，请在下载后**删除 Release**，以遵守 Aseprite 的 EULA 协议（不允许分发编译后的二进制文件）。删除后不会重新编译：GitHub 会保留 tag，只有 Aseprite 发布新版本时才会再次编译。
- 上方徽章显示构建是否仍然可用，以及最近验证通过的 Aseprite 版本。如果你的构建失败，而这里已经修复，在你的 fork 页面点击 **Sync fork** 即可获取修复。

## 致谢

- [Aseprite](https://github.com/aseprite/aseprite) by David Capello

## 许可证

[MIT](LICENSE)
