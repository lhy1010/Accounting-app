# Test App - Flutter Hello World

一个基于 Flutter 的 Android Hello World 应用。

## 前置要求

- [Flutter SDK](https://docs.flutter.dev/get-started/install) >= 3.10.0
- Android Studio（含 Android SDK）
- 一台 Android 手机（开启 USB 调试）或 Android 模拟器

## 运行步骤

1. 确保已安装 Flutter SDK 并配置好环境变量
2. 在项目根目录执行：
   ```bash
   flutter pub get
   ```
3. 连接手机或启动模拟器，然后运行：
   ```bash
   flutter run
   ```

## 项目结构

```
test-app/
├── lib/
│   └── main.dart          # 主入口 & Hello World 页面
├── android/               # Android 原生配置
├── pubspec.yaml           # 依赖配置
└── .gitignore
```
