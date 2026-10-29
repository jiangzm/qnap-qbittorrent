# qBittorrent for QNAP

> A file list program that supports multiple storage, powered by Gin and Solidjs. 

## 介绍
一款支持多种网络存储、挂载本地存储、阿里云盘、百度网盘、OneDrive、Google Drive 等,支持网页浏览和 WebDAV 的文件列表程序。

* openlist 版开源：https://github.com/OpenListTeam/OpenList <a href="#">
    <img src="https://img.shields.io/github/v/release/OpenListTeam/OpenList" alt="latest version" />

## 安装注意
 * 安装前先去【控制台】→【应用程序】→【Web服务器】→【☑️启用Web服务器】，不要更改默认80端口
 * 忘记密码，进入shell，运行命令 `$(getcfg openlist Install_Path -f /etc/config/qpkg.conf)/openlist admin set 123456`
 * 设置用户admin的新密码为123456


## 如何使用
在QNAP系统，通过App Center手动安装 ***.qpkg*** 后辍程序。

* 支持 x86_64 构架的QNAP存储设备【x86_64】
* 支持 ARM 构架的QNAP存储设备 【仅支持 arm-x41 及更高】 （旧版本插件）
* 支持 aach64 构架的QNAP存储设备 【arm_64】

## 开源声明
 1. 本软件为免费开源项目，无任何形式的盈利行为。
 2. 本软件服务于各种网盘，旨在让各大网盘功能更强大。如有侵权，请与我联系，会及时处理。
 3. 本软件皆调用官方接口实现，无任何“Hack”行为，无破坏官方接口行为。
 4. 本软件仅做流量转发，不拦截、存储、篡改任何用户数据。
 5. 严禁使用本软件进行盈利、损坏官方、散落任何违法信息等行为。
 6. 本软件不作任何稳定性的承诺，如因使用本软件导致的文件丢失、文件破坏等意外情况，均与本软件无关。
