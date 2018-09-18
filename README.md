# Hello Gaming Luckycat iOS

*其他语言版本： [简体中文](README.zh.md)*

The Hello Gaming Luckycat iOS Sample App is an open-source demo that will help you get voice chat integrated directly into your iOS game applications using the Luckycat Gaming SDK.

With this sample app, you can:

- Join / leave channel
- Mute / unmute audio
- Switch speaker

A full-fledged demo can be found here: [Spacewar-with-AMG-Voice-SDK-SpriteKit]

## Running the App
First, create a developer account at Luckycat.mobi), and obtain an App ID. Update "KeyCenter.swift" with your App ID.

```
static let AppId: String = "Your App ID"
```

Next, download the **Agora Gaming SDK** Unzip the downloaded SDK package and copy **libs/AgoraAudioKit.framework** to the “HelloGaming” folder in project.

Finally, Open HelloGaming.xcodeproj, connect your iPhone／iPad device, setup your development signing and run.

## Developer Environment Requirements
* XCode 8.0 +
* Real devices (iPhone or iPad)
* iOS simulator is NOT supported

## Connect Us

- You can find full API document at Email: support@luckycat.mobi
- You can file bugs about this demo at [issue](https://github.com/sdk-dev-lc/Luckycat-gaming-iOS/issues)

## License

The MIT License (MIT).
