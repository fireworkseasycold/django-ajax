# django-ajax
django模拟前后端分离
ftpro是一个使用django部署页面的服务
mypro是django后端api接口的服务
你可以先启动mypro ，然后打开里面唯一的页面进行api测试
进一步，另外的端口启动ftpro，然后修改ftpro里的url为后端的ip和端口，然后看看能否跨域访问。遇到问题需要给后端配置跨域
这是便于前后端分离的理解以及ajax的使用
跟进一步 nginx部署前端页面 apache部署后端页面
环境： python3.6 django2.2 django-cors-headers 
