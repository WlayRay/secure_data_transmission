##                                              项目简介

#### 1.本项目部署在Linux平台上，当然也可以部署在Windows平台上，但是应当自行添加openSSL的库文件以及操作数据可的文件。

#### 2.需要通过修改配置文件进行IP地址以及端口的设置，如果只是部署在本机上的话，可以不用修改配置文件，默认使用的是回环地址。

#### 3.使用前应该打开数据库，并通过配置文件修改用户名，密码以能够连接数据库，同时要有相应的权限进行数据库操作，建表，增删查改等权限都要有。

#### 4.服务端使用的是守护进程，客户端可以选择功能。