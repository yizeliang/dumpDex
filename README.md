# 分支说明

**本分支不需要 复制so库什么的,因为没有使用jni,完全使用xposed来完成,经测试,在夜神模拟器Android5.1.1中成功脱壳(当然需要安装xposed,夜神是提供的)**

# dumpDex-Android脱壳

> 插件需要在xposed环境中使用,支持市面上大多数加密壳,软件仅供学习用，请勿用于其他用途,项目不是成品，可能会引起软件崩溃

### 编译环境

Android Studio 3.0

**无法脱壳，请在 [PackerInfo.java](app/src/main/java/com/wrbug/dumpdex/PackerInfo.java#L31)文件中，将应用的包名加到packages字段里，编译安装即可,欢迎提交Pull Requests，让软件更加全面**

### 支持设备

大多数xposed环境的手机，暂不支持模拟器，


### 使用方式

下载源码编译或者下载apk包并安装，应用xposed模块后重启，运行加固的应用后，插件会自动将dex文件dump到 **/data/data/包名/dump** 目录

**本分支不需要 复制so库什么的,因为没有so代码,完全使用Xpose来完成,经测试,在夜神模拟器Android5.1.1中成功脱壳**

### 源码编译


配置完成后激活xposed重启即可

### 更多精彩内容请关注博客

[https://www.wrbug.com/](https://www.wrbug.com/)

### 相关文章(网友分享)

[dumpDex 脱壳原理](http://liteng1220.com/blog/articles/dumpdex-principle/)



