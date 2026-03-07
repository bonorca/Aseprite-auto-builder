# Aseprite 自动构建器

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

- 注意：请将你的 fork 设为私有仓库或下载后删除Release，以遵守 Aseprite 的 EULA 协议（不允许分发编译后的二进制文件）。

## 致谢

- [Aseprite](https://github.com/aseprite/aseprite) by David Capello

## 许可证

[MIT](LICENSE)
