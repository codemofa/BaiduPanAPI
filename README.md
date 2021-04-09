# BaiduPanAPI
百度网盘API

网站：https://pan.alltoapi.com

## DEMO

[点击观看DEMO](https://github.com/codemofa/BaiduPanAPI/blob/main/pan.alltoapi.com.demo.webm)


## 原理

本站采用的是Android的 [无障碍功能（AccessibilityService）](https://developer.android.com/guide/topics/ui/accessibility)

## 目前提供的API

1. 获取文件列表
2. 分享文件（夹）
3. 取消分享

## 已知问题

1. 同一个文件分享多次后不支持取消分享
2. 目前的分享只支持30天过期类型

## 使用步骤

1. 安装最新版百度网盘（11.8.2版本）并登录。
2. 注册本站用户，购买授权码（Token）。注：当前在试用期，可以在后台免费申请试用。
3. 下载本站的APK客户端`panclient`（主要是一个含有一个无障碍功能服务），安装到手机上，打开后输入第2步中获取到的授权码（Token）并保存，然后打开`panclient`无障碍功能服务权限。
4. 在后台创建相应任务进行操作。注：目前提供了列出网盘文件、分享文件（夹）、取消分享文件（夹）等功能。
