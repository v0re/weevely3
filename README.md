Weevely
=======

Weevely是一个命令行网壳动态扩展，在网络上运行时，专为远程管理和渗透测试。它提供了一个SSH般终端只是删除一个PHP脚本在目标服务器上，即使是在有限的环境。

在占用资源低代理和超过30个模块塑造一个可扩展的框架来管理网络帐户和后期利用Web服务器升级特权，在网络上横向移动。

**阅读 [Wiki](https://github.com/epinna/weevely3/wiki#getting-started) 对于教程和使用情况。**

The modules feature:

* Ssh-like terminal
* Run SQL console pivoting on target
* Proxy your HTTP traffic pivoting on target
* Host configurations security auditing
* Mount target file system locally
* Conduct network scans pivoting on target
* File upload and download
* Spawn reverse and direct TCP shells
* Bruteforce internal services
* Manage comprossed archives

### 后门代理


远程代理是一个小的PHP脚本，可以通过网络在运行时扩展其功能。代理代码是多态的，几乎没有检测的AV和流量是HTTP请求中的模糊处理.

### 模块开发

Weevely也提供了Python的API来开发自己的模块来实现内部审计，枚举账号，敏感数据的刮板，网络扫描仪，使模块的工作作为一个HTTP或SQL客户端，并做一个整体的很多其他很酷的东西.

> 如果你是一个开发人员或好奇的用户，并希望做出贡献，就可以开始阅读教程[开发一个新的模块 ](https://github.com/epinna/weevely3/wiki/developing-a-new-module) and the [TODO列表](https://github.com/epinna/weevely3/issues/1).
