# Android平台下快速集成二维码扫描、识别与生成功能

关于ZXing

>ZXing ("zebra crossing") is an open-source, multi-format 1D/2D barcode image processing library implemented in Java, with ports to other languages.

项目主页: https://github.com/zxing/zxing

开发文档: https://github.com/zxing/zxing/wiki/Getting-Started-Developing

这里我们主要讨论的是Android平台ZXing的集成, 因此只介绍和Android相关的三个工程:

- android: 这个便是我们要改造的工程, 里面包含了二维码扫描与识别等功能。

- android-core: 只有一个CameraConfigurationUtils类, 用来配置相机参数。

- core: ZXing核心功能模块。
