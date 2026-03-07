# Aseprite Auto Builder

Auto-compile the latest [Aseprite](https://github.com/aseprite/aseprite) for Windows using GitHub Actions.
It checks daily for new Aseprite releases and compiles automatically.

[中文说明 / Aseprite 自动构建器](README_CN.md)

## Usage

1. **Fork** this repo
2. Go to **Actions** tab
3. Enable Workflow
4. Select **"Build and release Aseprite"** → **Run workflow**
5. Wait ~20 min, then download the zip from **Releases**

After that, the workflow checks daily for new Aseprite versions and builds automatically.

<img src="https://github.com/user-attachments/assets/e4b7340a-8204-4ce3-9f60-e718a6b48ad2" width="600">
<img src="https://github.com/user-attachments/assets/2765b8ca-4782-47ee-878b-c77d897979a5" width="600">



- Note: Please set your fork to private or delete the release after use to respect Aseprite's EULA, which does not allow distributing compiled binaries.

## Credits

- [Aseprite](https://github.com/aseprite/aseprite) by David Capello

## License

[MIT](LICENSE)
