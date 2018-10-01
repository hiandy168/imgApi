
超简Api图床 V1.0 —— 专为Api而生
===============


超简Api图床 V1.0 基于ThinPhP 5.1实现的一套Api图床程序，主要包含以下特色：

 + 无数据库模式，简单配置，一键搭建
 + 第三方接口接入，不占用服务器空间
 + 接入搜狗Api平台，无需配置，全球CDN加速，永久不限量图片存储
 + 接入新浪Api平台，无需配置，全球CDN加速，永久不限量图片存储
 + 支持服务器存储模式，代替普通图床
 + 超简单Api使用，提供统一Api实现图片上传
 + 通讯密钥过滤恶意上传
 + 支持跨域提交访问
 + 免费、开源


> 超简Api图床的运行环境要求PHP5.6以上。

## 安装

 + 下载本套系统源码，解压至网站根目录
 + 访问 http://localhost/public/ 进入主页
 + 点击系统设置，进入设置页面，进行系统的首次配置，并修改管理员密码和通讯密钥
 + 默认管理密码为：123456
 + 默认通讯密钥为：123456
 + 保存配置后，即可开始使用

## 使用

 + 根据主页显示的Api接口，调用Api接口，将会返回对应的图片地址
 + 使用主页提供的测试工具，手动选择图片上传，会显示对应的图片地址
 
## 注意

 + 如果图床模式为服务器存储，请务必参考下面的资料将public/uploads目录设定为无权限执行PHP程序目录，保证服务器的安全性
   + https://blog.csdn.net/alen_xiaoxin/article/details/60783141
   + https://www.jb51.net/article/94061.htm

## 版权信息

超简Api图床遵循 MIT License 开源协议发布，并提供免费使用。


版权所有Copyright © 28 by vone (http://szvone.cn)

All rights reserved。

