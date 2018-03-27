# CrapApi
[![视屏演示](http://git.oschina.net/CrapApi/CrapApi/raw/master/CrapApiFiles/webPlay.jpg "视屏演示")](http://v.youku.com/v_show/id_XMjY5NzUzMjM3Ng==?spm=a2h3j.8428770.3416059.1)

[CrapApi是什么]
```
一个由angularjs+bootstrap+springMVC搭建的免费开源的API接口、文档管理系统（应用接口管理系统）
```
[CrapApi收费吗？]
```
CrapApi是完全免费开源项目，源码在GitHub、码云上可以获取，所有功能免费全部开放，终身不收取任何费用！
企业内部、个人、团体等可以免费使用该项目及源码。但未经许可，禁止任何以盈利为目的商业行为使用CrapApi！
当然项目发展离不开你的支持，如果觉得项目确实不错，可以在码云上捐赠，请作者喝杯咖啡吧！

```
[CrapApi能做什么]
```
主要功能：项目管理、用户管理、模块管理、接口管理、接口版本管理、接口拷贝、接口文档pdf下载、接口mock、模块加密访问、
接口在线调试、数据字典管理、数据字典加密访问多管理员、多权限、多角色管理、自定义菜单、自定义网站样式、文档留言、
错误码管理、接口排序、DOC、PDF、TEXT、EXCEL等资源管理、支持版本号控制、文档内容检索、操作日志记录、
根据日志恢复数据、markdown编辑器、kindeditor编辑器、angularjs编辑器、Lucene搜索、项目成员管理...

特点：
   1.单页应用、异步交互，响应速度快
   2.具有多种账户类型，具有角色、权限管理功能，适合企业内部使用
   3.支持用户注册、项目支持成员管理，适合团队协作办公，可企业内部部署，也可在线使用
   4.接口支持文档下载、在线调试、接口监控、数据mock等，适合企业内部接口开发

高并发：默认采用内存缓存，可配置redis缓存。使用redis缓存时，系统可集群部署
历经1年打磨，7版更迭，上百用户建议留言，总有一些功能是你需要的
```

[部署硬件要求]
```
Linux系统：1G内存以上，jdk7及以上，Tomcat7及以上，mysql5.6及以上
Windows系统：2G内存以上，jdk7及以上，Tomcat7及以上，mysql5.6及以上
```

[演示&帮助文档&部署文档]
```
演示地址：http://api.crap.cn
压缩包下载地址：http://ehsantang.github.io/CrapApi/
帮助文档地址：http://api.crap.cn/index.do#/top/webPage/list/ARTICLE/%E5%B8%AE%E5%8A%A9%E6%96%87%E6%A1%A3
部署文档地址：http://api.crap.cn/index.do#/top/webPage/detail/ARTICLE/19dc3d5c7-ff3d-4dff-ad72-2212869cd92a
码云源码地址：https://git.oschina.net/CrapApi/CrapApi.git
GitHub源码地址：https://github.com/EhsanTang/CrapApi

演示项目：http://api2.crap.cn
普通账号：super 123456 （该账号只拥有部分权限）
最高管理员账号：admin 123456（该账号拥有全部权限，请文明试用）
***********使用最高管理员账号时，请文明操作，请勿删除重要配置信息、请勿修改密码等危险操作*********

付费QQ群：263949884   前往http://git.oschina.net/CrapApi/CrapApi 捐赠(10元以上，用于服务器租赁)即可入群，提供部署、升级、问题解答等服务...
用户交流群：254450938[1群] 535449678[2群]
```

[主要技术]
```
主要语言：java、js
主要技术：angularjs、bootstrap、springMVC、hibernate、maven、iconfont、markdown、redis、Lucene...
```
[关键字]
```
ApiManager GitHub,apimanager github,Apimanager 码云,ApiManager 开源中国
API接口管理系统,API接口管理,在线API接口管理,API接口调试工具,RestApi,API调试插件
```

[相关技术介绍]
```
AngularJS：Google推出的前端JS框架
Bootstrap：Twitter开源工具包
Iconfont：阿里巴巴矢量图标库
```
[效果图]

http://blog.csdn.net/torrytang/article/details/52728160

最新消息：</br>
[2016 年9月获得码云推荐]</br>
[2016 年度码云新增热门开源软件排行榜 TOP 50——【CrapApi排名16】](http://www.oschina.net//news/81027/2016-oschina-git-new-software-top-50)</br>

<p>
commmit id 3054056</br>
新增功能</br>
模块增加生产环境url 页面增加输入选项</br>
增加是否能在前台操作生产环境选项</br>
前台显示url改成部分url</br>
增加选择环境下拉列表</br>
增加可用不可用类型枚举</br>

sql</br>
ALTER TABLE interface ADD COLUMN productFullUrl varchar(200) NOT NULL COMMENT 'api生产环境全路径' AFTER fullUrl;
ALTER TABLE module ADD COLUMN productUrl varchar(200) NOT NULL COMMENT '模块生产环境地址' AFTER url;
ALTER TABLE interface ADD COLUMN isOperFlag bit(1) NOT NULL DEFAULT b'0' COMMENT '前台是否可操作' AFTER isTemplate;</br>
</p>

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/cn/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/3.0/cn/88x31.png" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/cn/">知识共享署名-非商业性使用-相同方式共享 3.0 中国大陆许可协议</a>进行许可。
