# NanoPi-R2S 的 OpenWrt 极简固件

基于 [nicholas-opensource/OpenWrt-Autobuild](https://github.com/nicholas-opensource/OpenWrt-Autobuild/tree/main) 对 [openwrt/openwrt v21.02](https://github.com/openwrt/openwrt/tree/openwrt-21.02) 进行定制编译

## 特性

1. 默认主机名： `NanoPi-R2S`

2. 默认 LAN IP： `192.168.24.1`

3. 默认用户、密码： `root` `无`

4. 插件清单：

    - 应用：[`SSRPlus`](https://github.com/fw876/helloworld/tree/master)
    
    - 主题：[`Argon（默认）`](https://github.com/jerrykuku/luci-theme-argon/tree/master) [`Bootstrap`](https://github.com/openwrt/luci/tree/openwrt-21.02/themes/luci-theme-bootstrap)

5. 默认关闭 `IPv6`，移除上游的 [`fuck`](https://github.com/nicholas-opensource/OpenWrt-Autobuild/blob/main/PATCH/new/script/fuck) 等组件

## 感谢

感谢所有提供了上游项目代码和给予了帮助的大佬们，特别是 [nicholas-opensource](https://github.com/nicholas-opensource)。

....
