# SendEmail--邮件分发管理系统

## 这是一个一直很想做的项目，需求就是发送邮件，以前在博客上发过各种编程语言如何发送邮件的代码，无一例外都需要配置各种参数，Python还好，有库可以直接用，但Java和PHP就得导入包，还可能出各种错，当好不容易解决了这个项目里的问题，下个项目也需要发送邮件的时候，就又开始了新的一波折腾。而且还有一个问题，就是安全性，发送邮件需要配置邮箱密码或者授权码，每个项目都配置一遍，难免会有疏漏，如果密码泄露出去就不太好了。

## 所以我想做一个这样的东西，邮件发送只在一个系统完成，其他地方需要发送邮件了，直接调用系统所开放的接口，每个接口分配一个授权码，授权码可以设置失效期，使用次数，固定IP等等，当授权码泄露了直接在系统中关闭掉就可以，安全方便，还可以查看已经发送的邮件，发送请求的IP地址，把这些都整合在一起。这个功能其他云服务商也有提供，但我就是不想用，就想自己写一个， 以前没时间都在拖，今天终于下决心开始写了。

## 这些功能只是我初步的一个设想，慢慢的会完善，如果有关注到这个项目的同学，有好的想法可以联系我，QQ：641351484

## 项目开发我会放到GitHub和码云上，有兴趣的可以关注

## [GitHub](https://github.com/rainweb521/SendEmail)

## [码云](https://gitee.com/rainweb/sendemail)

## 放一个设想图

![](/public/reade/1.jpg)