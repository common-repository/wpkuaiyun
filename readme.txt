=== WPKuaiYun ===
Contributors: laobuluo
Donate link: https://www.lezaiyun.com/donate/
Tags:景安快云对象存储,快云存储,网站附件存储
Requires at least: 4.5.0
Tested up to: 6.5.3
Stable tag: 2.2
Requires PHP: 5.6
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

WordPress景安快云对象存储插件（WPKuaiYun），基于景安快云对象存储与WordPress实现静态资源到静态存储。

== Description ==

<strong>基于WordPress程序，可以选择本地+快云对象存储静态资源或者单独使用远程快云对象存储，自定义域名实现自建静态文件图床。</strong>

<strong>主要功能：</strong>

* 1、基于WordPress程序且免费提供给用户使用，将网站的静态文件，比如图片、附件，选择存储在景安快云对象存储中或者同时在本地，提高网站加载速度。
* 2、景安快云对象存储调用外部资源需要自定义域名，且需要白名单才可以绑定。
* 3、建议对象存储配合景安服务器一并使用。【<a href="https://www.laobuluo.com/goto/zzidc.com" target="_blank" >快云账户注册地址</a>】
* 4、插件更多详细介绍和安装：<a href="https://www.laobuluo.com/2341.html" target="_blank" >https://www.laobuluo.com/2341.html</a>

## 网站支持

* [老部落](https://www.laobuluo.com/ "老部落")

* [老蒋部落](https://www.itbulu.com/ "老蒋部落")

* [乐在云](https://www.lezaiyun.com/ "乐在云")

* 欢迎加入插件和站长微信公众号：老蒋朋友圈（公众号）

== Installation ==

* 1、把wpkuaiyun文件夹上传到/wp-content/plugins/目录下<br />
* 2、在后台插件列表中激活wpkuaiyun<br />
* 3、在“wpkuaiyun设置”菜单中输入景安快云对象存储相关参数信息<br />
* 4、我们可以在编辑文章的时候将静态资源上传到景安对象存储以及本地备份。

== Frequently Asked Questions ==

* 1.当发现插件出错时，开启调试获取错误信息。
* 2.我们可以选择备份对象存储或者本地同时备份。
* 3.需要自定义域名，景安对象存储不提供免费域名。

== About Use API 3rd Party or external service ==

About the Plugin use 3rd Party or external service "$url = "http://api.storagesdk.com/restful/storageapi/file/deleteFile"; " ：

* 1. This plugin use kuaiyun cloud storage API interface. The wordpress Plugins can store images and attachments to cloud storage.
* 2. The link to the service：https://www.kuaiyun.cn/storage/kystorageindex
* 2. The services’ a terms of use and/or privacy policies : https://www.kuaiyun.cn/document/productdetail?sid=11&id=270&cid=6

== Screenshots ==

1. screenshot-1.png

== Changelog ==

= 2.2 =
*兼容最新WP6.2

= 2.1 =
*兼容最新WP5.9.3

= 1.1 =
*兼容最新WP5.7

= 1.0 =
*兼容最新WP5.6

= 0.1 =
* 1、wpkuaiyun本地调试发布。
* 2、根据WordPress官方要求进行多次修改审核。

== Upgrade Notice ==
* 