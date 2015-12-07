这是我个人在工作之余开发的一款xmpp+openfire即时通讯软件，页面布局仿照微信，基于jabber协议，其功能包括用户登录、注册、获取好友列表、及时聊天、收发信息、自定义表情键盘、未读消息小红点提示、修改个人信息、用户头像、删除好友等等。此项目是基于openfire服务器的，所以需要您现在电脑上搭建openfire服务器，这个资料有很多，网上找点就可以。
服务器搭建好之后，这个客户端需要做一些和服务器交互的配置信息，其配置文件在Class->Other->Common->common.h文件中，在这个文件中修改成您的服务器ip地址，服务器端口号，服务器的域名等等。

这个项目得需要自己在电脑上搭建服务器openfire,mysql数据库，然后在openfire后台添加用户名密码，再在我的项目中common.h文件中配置服务器信息，就可以登录了。openfire服务器的搭建教程，我已经把文档上传了 供大家查看 http://download.csdn.net/detail/joonchen111/9168877

效果图如下
http://code.cocoachina.com/detail/326517/%E6%A8%A1%E4%BB%BF%E5%BE%AE%E4%BF%A1%E5%BC%80%E5%8F%91%E7%9A%84%E8%81%8A%E5%A4%A9%E8%BD%AF%E4%BB%B6%EF%BC%8C%E5%9F%BA%E4%BA%8EXMPP/

如果喜欢就在上面给个star吧，thank you。 欢迎加入iOS大神群交流 519797474

This is my personal development in the work of a xmpp+openfire instant messaging software, page layout modeled micro channel, based on the jabber protocol, its functions include user login, registration, access to friends list, timely chat, send and receive information, custom expression keyboard, not read the message little red dot, modify personal information, user avatar, delete friends, etc.. This project is based on the openfire server, so you need to build a openfire server on the computer, this information has a lot of online search can be.
After the server is set up, the client needs to do some configuration information and server interaction, its configuration file in the Class->Other->Common->common.h file, in this file to modify the IP address of your server, server port number, server name, etc..

This project will need to build on the computer openfire server, MySQL database, and then add a user name password in openfire background, and then configure the server information in the common.h file in my project, you can log in. Openfire server setup tutorial, I have uploaded the document for everyone to see
http://download.csdn.net/detail/joonchen111/9168877

The results are as follows
http://code.cocoachina.com/detail/326517/%E6%A8%A1%E4%BB%BF%E5%BE%AE%E4%BF%A1%E5%BC%80%E5%8F%91%E7%9A%84%E8%81%8A%E5%A4%A9%E8%BD%AF%E4%BB%B6%EF%BC%8C%E5%9F%BA%E4%BA%8EXMPP/

If you like it, give it to a thank, you star.
