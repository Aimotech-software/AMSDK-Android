# AMSDK-Android
![AIMOSDK](https://raw.githubusercontent.com/Aimotech-software/AMSDK-iOS/master/AIMOSDKLogo.png)

English | [简体中文](./README-zh_CN.md) 

AIMO SDK, developed by Aimo Inc, is a software development kit for printers. It offers convenient interfaces for developers to easily implement various printing functions and meet diverse needs. 

- [Features](#features)
- [Requirements](#requirements)
  + [Dependency](#dependency)
- [Installation](#installation)
- [List of Mobile SDK Supported Models](#list-of-mobile-sdk-supported-models)
- [Usage](https://github.com/Aimotech-software/AMSDK-iOS/blob/master/Documentation/Usage.md)
- [FAQ](#faq)
- [License](#license)

## Features

- [x] Scan Device with BLE
- [x] Connect Device with  classic
- [x] Configure the Wi-Fi network
- [x] Connect Device with  WiFI
- [x] Connect Device with  USB Typec
- [x] Connect Device with  Port
- [x] Print Images
- [x] Upgrade OTA 

## Requirements

| MinSdk                                  | TargetSdk
| --------------------------------------- | --------------------- 
| 21                                          33  


### Dependency

We use OpenCV to crop or scale images. Currently, the version of OpenCV we depend on is shown in the following figure.

| AIMO SDK Version                                     | OpenCV Version 
| ---------------------------------------------------- | --------------------- 
| 1.0.x                                                | 4.8.0         


### List of Mobile SDK Supported Models

| Serias                                               | Suppported Models  
| ---------------------------------------------------- | --------------------- 
| M Serias                                             | M102      



## Installation

### Gradle

## FAQ
Our answers to frequently asked questions about mobile SDKs so far are shown below. Before you email us your questions, please check the following.
### Are the SDKs on this website available for free?
Yes, the SDKs obtained from GitHub and CocoaPods are free. However, you cannot directly scan for and connect to AIMO printers. You must contact the staff of AIMO Inc. to obtain the corresponding tokens and keys in order to use the SDK properly.

## License

[See LICENSE](https://github.com/Aimotech-software/AMSDK-ios/blob/master/LICENSE) for details.
