# app-ionic-admin

## 简介
一款由 React, Ionic, IonicFramework, 编写的 iOS, Android 跨平台原生运行时模版项目, 支持它们的平台上访问丰富的原生设备功能。通过iOS上的Swift插件API, Android上的Java和网络上的JavaScript，添加本机功能非常简单。

## 环境设置
- 首先得有 node，并确保 node 版本是 16 或以上。（推荐用 nvm 来管理 node 版本，windows 下推荐用 nvm-windows）
```bash
node --version
# v18.3.0
```
### iOS 要求
> 要构建iOS应用程序，您将需要macOS。
> 为了使用 Capacitor 开发 iOS 应用程序，您将需要四个额外的依赖项：
> - Xcode
> - Xcode Command Line Tools
> - Homebrew
> - Cocoapods

#### Xcode
> Xcode 是 Apple 的 IDE，用于创建原生 macOS、iOS 和 iPadOS 应用程序。您可以使用 Mac 上的 Apple App Store 安装 Xcode。至少需要 Xcode 14.1。
#### Xcode Command Line Tools
Xcode 命令行工具是 Xcode 核心中未包含的其他工具，是构建和测试应用程序所必需的。安装 Xcode 后，您可以通过在终端中运行以下命令来安装 Xcode 命令行工具：
```bash
xcode-select --install
```
输入密码并等待几分钟以安装软件包后，可以通过运行以下命令来验证工具是否已安装：
```bash
xcode-select -p
# /Applications/Xcode.app/Contents/Developer
```
#### Homebrew
Homebrew是macOS软件包的包管理器。您需要安装它才能为英特尔和苹果硅Mac安装CocoaPods。
要安装自制软件，请运行以下 bash 命令：
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

#### Cocoapods
CocoaPods是一个用于管理iOS和macOS项目的依赖项的软件包管理器。要安装CocoaPods，请运行以下命令：
```bash
brew install cocoapods
```
可以通过运行以下命令来验证 CocoaPods 是否已正确安装。
```bash
pod --version
# 1.12.1
```
### Android 要求
为了使用 Capacitor 开发 Android 应用程序，您需要两个额外的依赖项：
- Android Studio
- An Android SDK installation
一旦你安装了核心要求，以及带有Android Studio的Android SDK，你将能够创建Android应用程序和PWA。


## 安装使用

- 获取项目代码

```bash
git clone https://github.com/Jerry-0425/app-ionic-admin.git
```


- 安装依赖

```bash
cd app-ionic-admin

pnpm install
```

- web 调试启动服务

```bash
pnpm dev
```
