# Hello Gaming Agora iOS

*Read this in other languages: [English](README.md)*

这个开源示例项目演示了如何快速集成Luckycat游戏SDK，实现在游戏中音频通话。

在这个示例项目中包含了以下功能：

- 加入通话和离开通话；
- 静音和解除静音；
- 切换外放和听筒；

你也可以在这里查看进阶版的示例项目：[Spacewar-with-AMG-Voice-SDK-SpriteKit]



## 运行示例程序
首先在 [luckycat 注册] 注册账号，并创建自己的测试项目，获取到 AppID。将 AppID 填写进 KeyCenter.swift

```
static let AppId: String = "Your App ID"
```
**libs/AgoraAudioKit.framework** 文件复制到本项目的 “HelloGaming” 目录下。

最后使用 XCode 打开 HelloGaming.xcodeproj，连接 iPhone／iPad 测试设备，设置有效的开发者签名后即可运行。

## 运行环境
* XCode 8.0 +
* iOS 真机设备
* 不支持模拟器

## 联系我们

- 如果需要售后技术支持, 你可以邮件 
- 如果发现了示例代码的bug, 欢迎提交 [issue](https://github.com/sdk-dev-lc/Luckycat-gaming-iOS/issues)

## 代码许可

The MIT License (MIT).
