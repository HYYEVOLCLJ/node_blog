# window如何启动博客系统

**前置环境：**

node、mongo、python需要安装(自行百度教程即可)



**修改mongo数据库配置：**

![pic1](D:\b_resources\github\node_blog\blog\pic\pic1.png)

换成你自己的数据库ip、port、用户名和pwd。



**安装bcrypt需要的前置环境：**

```bash
npm install -g node-gyp
npm install --global --production windows-build-tools
```



进入blog目录下，执行`npm install`命令安装依赖。

**node app.js**：启动服务

在浏览器localhost:3000/admin/login登录即可。





# linux系统如何启动博客系统

**前置环境：**

[如何在Linux系统上安装Node和npm](https://editor.csdn.net/md/?articleId=111502064)
[如何在Linux系统上安装Python3环境](https://editor.csdn.net/md/?articleId=111502595)

[Centos安装MongoDB并设置为服务](https://blog.csdn.net/huyang_1995/article/details/111373686)

**修改mongo数据库配置：**

![pic1](D:\b_resources\github\node_blog\blog\pic\pic1.png)

换成你自己的数据库ip、port、用户名和pwd。



**安装bcrypt需要的前置环境：**

```bash
npm install -g node-gyp
npm install --production --unsafe-perm=true --allow-root
```



进入blog目录下，执行`npm install`命令安装依赖。

**node app.js**：启动服务

在浏览器localhost:3000/admin/login登录即可。