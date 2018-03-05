
# Agora Tutorial for Web on PC - Live Streaming 2.0

*阅读中文版本: [中文](README.md)*

This project demonstrates how we can integrate Agora SDK to easily achieve live streaming using 2.0 api.

The small demo contains following features:

- Join/Leave calls
- Publish/Unpublish streams
- Add transcoding user and start live streaming

## How to run
Firstly you will need to register an account at [Agora.io](https://dashboard.agora.io/signin/). With your account logged in, you will be able to create your own test project at dev portal, there you can get your unique AppID. Take a note with your AppID as it will be used in later steps.

Now go to [Agora.io SDK](https://www.agora.io/en/download/) to download latest **Video + Interactive Broadcasting Web SDK**, and copy the SDK to the root folder of this project. Rename it to AgoraRTC-development.js.

Deploy the project to any http server and then use your browser to navigate to index.html

- Once you see the demo page successfully, put the AppID you get in prior step into the AppId text field.
- Now put your rtmp server url into Publish Url field.
- Press Join button to join the call. As soon as someone else joins the call, the call will be started and you will see each other from the client side.
- Press Add Transcoding User to add an existing user into the live streaming video frame, use the transcoding user configs to modify user frame's position and size.
- Press Add Streaming to start live streaming with given transcoding settings.

## Notice
If you want to run this sample app on mobile browsers, please be sure that `createClient` called with proper mode. For more please reference to the API documents.

## Connect Us

- You can find full API document at [Document Center](https://docs.agora.io/en/)
- You can file bugs about this demo at [issue](https://github.com/AgoraIO/Agora-iOS-Voice-Tutorial-Swift-1to1/issues)

## License

The MIT License (MIT).
