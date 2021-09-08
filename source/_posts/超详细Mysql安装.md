---
title: 超详细Mysql安装
date: 2021-09-07 20:58:07
tags:
- Mysql
- Windows
- 数据库
categories: 其他
cover: https://img-blog.csdnimg.cn/0748cd4d918e4010b74f347a32c9bd65.png
---

# 下载安装Mysql
从[MySQL 官网](https://dev.mysql.com/downloads/mysql/)下载最新的 Mysql，选择您的操作系统 (Microsoft Windows)，然后单击转到下载页面。它会将您重定向到 Windows Mysql的实际下载页面。

![在这里插入图片描述](https://img-blog.csdnimg.cn/0748cd4d918e4010b74f347a32c9bd65.png)

它将向您显示一般可用 (GA) 版本。我们可以看到两个不同的安装程序，一个是作为一个小文件的 web 社区安装程序，另一个是 MySQL 安装程序社区。单击第二个 (mysql-installer-community) 上的下载按钮。

![在这里插入图片描述](https://img-blog.csdnimg.cn/9a2faa78a4384c13812c55affa95acee.png)

它将要求您的 MySQL 凭据下载 .msi 文件。如果你有你的凭据，你可以登录，或者如果你想现在注册，你可以点击绿色的注册按钮。
如果您现在对登录或注册不感兴趣，可以直接点击 不，谢谢，只需开始我的下载选项。它将在您的本地计算机上为您下载选定的 MySQL。

![在这里插入图片描述](https://img-blog.csdnimg.cn/4e5379100e924ff2aab8b8e4df84eb37.png)

转到您的下载文件夹，您可以在其中看到mysql-installer-community文件，右键单击该文件并单击安装选项。

![在这里插入图片描述](https://img-blog.csdnimg.cn/bb31b82b48a845fd948f2668e2247b64.png)

此窗口配置安装程序，中间可能会要求您更改计算机设置或防火墙确认的权限，您可以接受，然后需要几秒钟的时间来配置安装程序。

![在这里插入图片描述](https://img-blog.csdnimg.cn/c4096b278777445db521c7b3ca55eacb.png)

阅读许可协议并接受许可条款。

![在这里插入图片描述](https://img-blog.csdnimg.cn/00b4fb0b1d6c44e7882baa367adaea8b.png)

此窗口提供您设置不同类型的 MySQL 安装。您可以在下面提供的 5 种不同类型中设置 Mysql。现在我选择了开发人员默认设置，因为我是一名开发人员，因此我需要所有有助于我的开发目的的产品。单击“下一步”。

![在这里插入图片描述](https://img-blog.csdnimg.cn/417dd4060fa746c2a2df49d80c03539c.png)

根据您的 Windows 配置，它可能会提示您“尚未满足一个或多个产品要求”。您只需单击YES 即可。

![在这里插入图片描述](https://img-blog.csdnimg.cn/e0035fef1e5c4a02beafcc8a2100ddcc.png)

单击执行。

![在这里插入图片描述](https://img-blog.csdnimg.cn/65780e7f7c8843a6acf97b00e705c00f.png)

执行上一步后，安装人员将所有推荐的产品都掌握到位，并要求我们批准执行产品安装过程。单击执行。

![在这里插入图片描述](https://img-blog.csdnimg.cn/0345f3b39dfd409cad09a8efbf0e3bf4.png)

成功执行所有必需的产品后，现在 MySQL 允许我们配置服务器设置。单击下一步 以配置服务器。

![在这里插入图片描述](https://img-blog.csdnimg.cn/27a905019c27472d8404350bf2db2240.png)

此步骤允许您配置服务器。我们可以将服务器设置为两种不同的模式。一种是独立模式，另一种是集群模式。我不想将它作为一个集群，因为我正在安装 MySQL 用于开发目的，所以我选择了Standalone MySQL server并单击Next。

![在这里插入图片描述](https://img-blog.csdnimg.cn/b8c86a8cc1a34591bdf488c69253ba12.png)

从配置类型下拉列表中选择开发计算机选项。您可以找到以下控件，如 TCP/IP、端口和 X 协议端口。如果您想配置您的端口，您可以在此处自行更改并单击Next。现在，我将保留其默认配置。

![在这里插入图片描述](https://img-blog.csdnimg.cn/134364b759cb41b1a0890c0223a5a5fe.png)

它会提示您选择身份验证方法，将其保留为默认推荐方法，然后单击Next。

![在这里插入图片描述](https://img-blog.csdnimg.cn/8a3f358183934be6a94a8be47dfc5c4a.png)

在这里您可以设置您的 MySQL 根用户密码。如果您想创建一个新用户，您可以单击MySQL 用户帐户部分下的添加用户按钮。

![在这里插入图片描述](https://img-blog.csdnimg.cn/ce214e4e1a5f4dcd9a03e0e84848e8ff.png)

单击添加用户按钮后，您将看到用户详细信息弹出窗口，允许您创建新用户帐户。创建用户后，单击Next。

![在这里插入图片描述](https://img-blog.csdnimg.cn/9b1aca50c3704b3a91d64c400280deca.png)

将服务详细信息保留为默认值，然后单击Next。

![在这里插入图片描述](https://img-blog.csdnimg.cn/8cf519c70155462e9a9547424e9c6a72.png)

按执行以应用上一步的配置。

![在这里插入图片描述](https://img-blog.csdnimg.cn/519f7816b4d74acbb07ee2f9ac5d0a41.png)

执行后，您可以在每个配置选项上看到下面的绿色勾号，最后您将获得 完成按钮。

![在这里插入图片描述](https://img-blog.csdnimg.cn/09a0a4d584324035bef1a20a9e3d4aac.png)

单击完成，您在 Windows 10 操作系统上安装了 MySQL。

# 测试：
在任务栏搜索项中搜索 MySQL。在那里你可以看到我们安装的所有 MySQL 产品并点击 MySQL 客户端；它会询问您的 MySQL 密码登录，成功登录后您可以看到如下所示的 MySQL 提示。  

![在这里插入图片描述](https://img-blog.csdnimg.cn/7826c4a26e184223b06d7e20735f3c43.png)

MySQL 附带一些默认数据库。我们可以使用show databases命令查看数据库。

![在这里插入图片描述](https://img-blog.csdnimg.cn/109196e70d72462e8aac4b629cd78b24.png)
