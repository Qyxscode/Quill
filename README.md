# Quill

Android 漫画阅读器（Flutter）。

## 功能

- 在线漫画：通过 JS 源脚本浏览、搜索与追更
- 本地漫画：导入 EPUB、ZIP、RAR，支持嵌套压缩包直读
- 阅读器：条漫与翻页、双页自动拆分、亮度调节、跳页滑条
- 书架：收藏、阅读历史、离线模式、WebDAV 备份
- 源管理：通过源清单（JSON）批量安装与更新源
- 应用内更新

## 下载

在 Release 页面下载 APK（Android arm64）。

## 构建

要求 Flutter 3.47 及以上版本。

```bash
flutter pub get
flutter build apk --release --target-platform android-arm64
```

## 说明

本项目不附带任何漫画源脚本，源由用户自行导入。

## 许可

闭源，保留所有权利。第三方组件许可见应用内「设置 — 关于」。
