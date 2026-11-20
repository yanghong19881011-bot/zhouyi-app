# 周易随身卦 - 安卓 APK 云端自动打包工程

本工程已将离线版周易八卦程序 (`www/index.html`) 与 Capacitor + GitHub Actions 自动编译流程封装就绪，无需在本地电脑安装 Android Studio 或任何 SDK。

## 三步免费生成 `.apk` 安装包

1. **新建 GitHub 仓库**：登录 GitHub，新建一个仓库（公开或私有均可）。
2. **上传工程文件**：将本压缩包解压后的全部文件（务必包含隐藏目录 `.github/workflows/build-apk.yml`、`www/`、`package.json`、`capacitor.config.json`）上传提交到仓库的 `main` 分支。
3. **下载编译好的 APK**：打开仓库顶部的 **Actions** 标签页，等待 `Build Android APK` 运行完成（约 2-3 分钟）后，在页面底部的 **Artifacts** 区域点击下载 `zhouyi-bagua-debug-apk`，解压即可得到可直接在安卓手机安装的 `.apk` 文件。
