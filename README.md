# PigeonSolver — GitHub 自动生成 APK

把整个项目上传到 GitHub 后，GitHub Actions 会自动编译 APK。

## 使用
1. 新建 GitHub 仓库。
2. 上传本项目全部文件。
3. 推送到 `main` 或 `master`。
4. 打开仓库的 `Actions`。
5. 选择 `Build APK`。
6. 打开最新运行记录，在底部 `Artifacts` 下载 `PigeonSolver-debug-apk`。
7. 解压得到 `app-debug.apk`，安装到 Android 手机。

也可以在 Actions 页面手动执行 `Run workflow`。

## 构建环境
- AGP 8.2.2
- Gradle 8.2.1
- JDK 17
- compileSdk 34
- minSdk 26

APK 内置网页端识别器，截图处理在手机本地完成。
