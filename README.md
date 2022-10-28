# AutoBuild-OpenWrt-Padavan

- 定制.config文件：
- 进入工作目录输入：./scripts/diffconfig.sh > diffconfig分离出定制的插件配置，
- 输入：nano diffconfig后会列出分离后的内容
- [[StartBuild](https://github.com/lu-1991/AutoBuild-OpenWrt-Padavan/actions?query=workflow%3A%22AutoBuild-OpenWrt-Padavan%22)] 

## 说明
- 内含供小米路由R3G、R3P、mini、nano等，竞斗云使用，基于 GitHub Actions CI 的自动化 ImmortalWrt Openwrt构建，使用 [padavanonly](https://github.com/padavanonly/immortalwrt)源码 、Linux 5.10 内核，以及开启了 [MTK SDK HWNAT](https://git01.mediatek.com/plugins/gitiles/openwrt/feeds/mtk-openwrt-feeds/) 支持；
- 内含Padavan固件编译。
- 其他机型云编译还在继续测试添加中……
