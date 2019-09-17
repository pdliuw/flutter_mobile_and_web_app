# flutter_mobile_and_web_app

A new Flutter application.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

----------------------------------------------------------------------------------------------------

---
title: Flutter适配多平台

img: /images/flutter_logo.jpg
summary: Flutter适配 Ios、Android、Web平台| 全平台创新开发体验
categories: 跨平台
tags:
- Flutter
- Dart

---


----

![图腾](https://github.com/pdliuw/pdliuw.github.io/blob/master/images/totem_four_logo.jpg?raw=true)


----

**Flutter适配 Ios、Android、Web平台| 全平台创新开发体验**

随着Flutter1.9 的发布！Flutter web 支持现已成功合并到 Flutter 的主 repo，自此以后，开发者只需使用同一套基准代码，便可为移动平台、桌面端和网页端开发应用。此外，团队也分享了来自全球互联网公司腾讯的成功案例，让现场观众体验了一把 Flutter 的蓬勃活力，亲眼见证越来越多的应用正在通过 Flutter 缔造精彩。


### 目录


1.  Flutter 适配多平台开发


####  1.  Flutter 适配多平台开发


**使用Flutter对多平台进行初步的开发设计！**

1.  创建项目，并初步运行后得到下图中的效果

    此处......省略若干“创建项目和运行项目”的步骤

    ![项目初步效果](https://github.com/pdliuw/pdliuw.github.io/blob/master/images/flutter/flutter_mobile_and_web/flutter_mobile_and_web.gif?raw=true)

2.  为各个平台增加“平台区分”

* 平台的区分

    注意：
    Android和IOS加入以下代码运行良好！Web平台加入以下代码将会停留在运行状态也就是运行不起来

    错误信息：
    Skipping compiling flutter_mobile_and_web_app|lib/main_web_entrypoint.dart with ddc because some of its
    transitive libraries have sdk dependencies that not supported on this platform:


        import 'dart:io';

        String getPlatformFlag(){
            return Platform.operatingSystem;
        }



    ![项目增加平台区分后效果](https://github.com/pdliuw/pdliuw.github.io/blob/master/images/flutter/flutter_mobile_and_web/flutter_mobile_and_web_with_platform.gif?raw=true)

####  3.  Flutter 外链!

关于Flutter内容，请以官方最新更新为准！

1.  **[Flutter 官网](https://flutter.dev/)**

----
