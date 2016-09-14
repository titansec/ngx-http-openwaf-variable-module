Name
====
ngx-http-openwaf-variable-module
提供openwaf所需变量的nginx模块

Table of Contents
=================
* [Name](#name)
* [Variables](#variables)
* [Others](#others)

Variables
=========
* [stat_accepted](#stat_accepted)
* [stat_handled](#stat_handled)
* [stat_requests](#stat_requests)
* [bytes_in](#bytes_in)
* [exten](#exten)

[Back to TOC](#table-of-contents)

stat_accepted
-------------
引擎处理的总连接数

stat_handled
-------------
引擎成功创建连接数
若与stat_accepted相等，证明没有创建失败的连接

stat_requests
-------------
引擎处理的总请求数

bytes_in
--------
number of bytes recved from a client
接收到客户端信息的字节数

exten
-----
请求文件的扩展名

[Back to TOC](#table-of-contents)

Others
======
* [ngx_http_core_module变量](http://nginx.org/en/docs/http/ngx_http_core_module.html#variables)
* [nginx_http_stub_status_module变量](http://nginx.org/en/docs/http/ngx_http_stub_status_module.html#variables)

[Back to TOC](#table-of-contents)



