# Agora Unity WebGL Plugin and Demo

*[中文](README.zh.md) | English*

Welcome to the **Agora Unity WebGL SDK (Community Edition)**! 🎉  
This project is built and maintained by the community to bring Agora’s real-time engagement features into Unity WebGL. It’s still in **open beta**, so things are evolving quickly — your feedback and contributions are what make this project grow.

---

### Notes

1. **This is a community-supported SDK in open beta.** Some features might not work perfectly yet, and behavior may differ from the official Unity SDK. **Please note that the Agora Support team cannot provide help for issues with this project.**

2. This SDK is **not compatible** with the official Agora Unity SDK version **4.x**.

3. If you just want to use the SDK, **please don’t clone this repository** unless you plan to contribute code. Instead, download the latest package from the [Releases](https://github.com/AgoraIO-Community/Agora_Unity_WebGL/releases) page.

4. Before downloading or posting questions, check out the [Wiki](https://github.com/AgoraIO-Community/Agora_Unity_WebGL/wiki) — it’s the best place to learn how this SDK works and what to expect.

5. Spatial Audio functionality is limited and may not work as expected.

6. If your post isn’t a bug report or improvement request, please use the [Discussions](https://github.com/AgoraIO-Community/Agora_Unity_WebGL/discussions) section instead.

7. If you find this project helpful, **don’t forget to give it a star!** ⭐ It’s an easy way to show support for the community members who built and maintain this SDK.


## Prerequisites
- Unity 2019 and up
- Agora Developer Account
- Knowledge of how to deploy and debug WebGL Application from Unity
- Google Chrome

## Updated main Demo

![webgldemo](https://user-images.githubusercontent.com/1261195/180123220-ca7e96e2-bff5-48d7-b5bd-30a37003bdc9.png)


## Quick Start

This section shows you how to prepare, build, and run the sample application.
 

### Obtain an App ID

Before you can build and run any Agora project, you will need to add your AppID to the configuration. Go to your [developer account’s project console](https://console.agora.io/projects), create a new AppId or copy the AppId from an existing project. 

**Note** it is important that for a production ready project, you should always use an AppId with token enabled.  However, in testing a demo, you will skip this part.  Using a testing mode AppId can save time for POC integration.
![enter image description here](https://user-images.githubusercontent.com/1261195/110023464-11eb0480-7ce2-11eb-99d6-031af60715ab.png)

  

### Run the Demo Application

1. It is optional to clone this repository,  to obtain the unity package file, go to [the release section](https://github.com/AgoraIO-Community/Agora_Unity_WebGL/releases) and download the latest version.
3. Import the WebGL SDK package (Unity Editor-> Assets -> Import Package -> Custom Package). 
4. From Project window, open Asset/AgoraEngine/Demo/Main.scene
5. Next, go into your Hierarchy window and select  ****GameController****, in the Inspector add your  ****App ID****  to to the  ****AppID****  Input field.

### API-Examples
This repository includes a set of API-Examples that shows how to use a particular feature. Starting from Refactor 8 release, these demo scene are grouped into the Home Scene for build.  Use the AppIDInfo asset to input the AppID (and token if using certificate enabled AppIDs)
![WebGL_-_WebGL_-appID](https://user-images.githubusercontent.com/1261195/232563068-f61d4d5c-b3a8-4f0c-b6a6-d7abbe9ec253.jpg)
![Screenshot 2023-04-17 at 10 25 10 AM](https://user-images.githubusercontent.com/1261195/232563080-e4055c69-7bb8-43bf-9cc0-1d7a4ef8f59f.png)


### Testing in Editor
You must download the "Complete" package from the Release.  The package includes native plugins (Windows/MacOS) that support the Editor environment.  Some may confuse on why certain functionalities work differently on Web verses "Editor".  That is because the platform differences between the WebGL and the native.

### Build and Run

 1. Go to  ****File****  >  ****Builds****  >  ****Platform****  and switch to platform WebGL 
 2. Make sure ****AgoraTemplate**** or ****AgoraTemplate2020**** is chosen under "Resolution and Presentation":
![webgl_template](https://user-images.githubusercontent.com/1261195/130500369-53dca294-2cf5-4a0d-a875-a8ab8fbabd70.png)
The difference of the templates: use AgoraTemplate2020 for Unity Editor 2020 and up.
 3. You may do Build And Run for Unity version 2020 and up.  For other versions, you need to build first, then run it from your local http server. 




## Resources
  
Please see [the Wiki page](https://github.com/AgoraIO-Community/Agora_Unity_WebGL/wiki) for more information.

## License
The MIT License (MIT).  [See doc.](LICENSE)


