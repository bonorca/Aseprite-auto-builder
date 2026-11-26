# Aseprite Auto Builder

[![Build](https://github.com/bonorca/Aseprite-auto-builder/actions/workflows/build-aseprite.yml/badge.svg)](https://github.com/bonorca/Aseprite-auto-builder/actions/workflows/build-aseprite.yml)
[![Verified](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/bonorca/Aseprite-auto-builder/main/.github/badges/verified.json)](https://github.com/bonorca/Aseprite-auto-builder/actions/workflows/build-aseprite.yml)

Auto-compile the latest [Aseprite](https://github.com/aseprite/aseprite) for Windows using GitHub Actions.
It checks daily for new Aseprite releases and compiles automatically.

[中文](README_CN.md)

## Usage

1. **Fork** this repo
2. Go to **Actions** tab
3. Enable Workflow
4. Select **"Build and release Aseprite"** → **Run workflow**
5. Wait ~20 min, then download the zip from **Releases**

After that, the workflow checks daily for new Aseprite versions and builds automatically.

<img src="https://github.com/user-attachments/assets/e4b7340a-8204-4ce3-9f60-e718a6b48ad2" width="600">
<img src="https://github.com/user-attachments/assets/2765b8ca-4782-47ee-878b-c77d897979a5" width="600">



- Note: Forks are always public, so please **delete the release** after downloading to respect Aseprite's EULA, which does not allow distributing compiled binaries. Deleting it won't trigger a rebuild: GitHub keeps the tag, and the workflow only builds again when a new Aseprite version comes out.
- The badges above show whether the build still works and which Aseprite version it was last verified with. If your build breaks after a fix has landed here, click **Sync fork** on your fork to get it.

## Credits

- [Aseprite](https://github.com/aseprite/aseprite) by David Capello

## License

[MIT](LICENSE)
