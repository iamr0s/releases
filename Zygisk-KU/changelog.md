# 2.0.0

全新的实现方式

基于[Zygisk](https://github.com/topjohnwu/zygisk-module-sample)的[Magisk](https://topjohnwu.github.io/Magisk/guides.html)模块。

以[Zygisk](https://github.com/topjohnwu/zygisk-module-sample)为基础，参考[Lsposed](https://github.com/LSPosed/LSPosed/blob/fe89b8cd89bf1a7946eccba6ae49bd6c4bc673df/daemon/src/main/java/org/lsposed/lspd/service/BridgeService.java#L84)的实现方式，等待系统服务启动后，拿到系统Context，并使用BroadcastReceiver注册监听第一次开屏事件，达到模块效果。

代码已开源：[iamr0s@github/Zygisk-KU](https://github.com/iamr0s/Zygisk-KU/blob/main/README.md)

