![](https://box.kancloud.cn/901503ed89e363a1dd81101346bba4eb_1366x768.png)
![](https://box.kancloud.cn/76079027c0d079fda05cd443aa5f84de_1366x768.png)
![](https://box.kancloud.cn/76079027c0d079fda05cd443aa5f84de_1366x768.png)

# 安装说明

###  ① 下载源码包：
~~~
你可以通过多种方式下载源码（如HTTP下载，Git克隆），下载之后进入源码目录。

Linux 下可执行下面命令：

git clone https://github.com/chenbei360/think.rbac
~~~

###  ② 导入数据库，并修改 数据库 配置文件：
~~~
把根目录下的/core/config/database.php.bak文件名改成database.php

根据你的数据库，配置database.php “hostname, database, username, password, hostport”
~~~

###  ③ 服务器绑定域名，并将文档根目录设置为源码包 public 目录下，给 runtime 目录可写权限。

#### ④ 访问服务器绑定的域名，如果能访问演示站类似的前台界面，说明您已经安装成功。

##### ⑤ 登录后台，后台使用的帐号与密码均为 admin，登入之后，您可以体验一番。

###### ⑥ 后台菜单设置方法请参考已有的那些菜单


```
[ 目录结构 ]
    project                		应用部署目录
    ├─core                 		系统核心
    │  ├─app               		应用目录
    │  │  ├─admin        		后台模块
    │  │  │  ├─controller   		控制器目录
    │  │  │  ├─model        		模型目录    
    │  │  │  ├─lang         		语言包目录   
    │  │  │  ├─common.php               后台函数文件     
    │  │  ├─common        		公共模块目录    
    │  │  ├─home            		前台模块    
    │  │  ├─more...            		自定义添加模块            
    │  │  ├─common.php      		项目公共函数文件
    │  ├─config                      配置目录
    │  │  ├─admin        		后台配置目录
    │  │  ├─home        		前台配置目录
    │  │  ├─database.php    		数据库配置文件
    │  │  ├─define.php      		项目路径常量配置文件
    │  ├─extend            		扩展类库目录
    │  ├─config.php          		网站配置文件
    ├─public              		WEB 部署目录（对外访问目录）
    │  ├─static          		静态资源存放目录(css,js,image)
    │  ├─index.php       		系统入口文件
    ├─runtime             		系统缓存目录
    ├─template            		项目模板目录
    │  ├─admin               		后台模板目录
    │  ├─home                		前台模板目录
    ├─cms.sql             		数据库文件
```

>[danger] 联系作者 
Email: 3279867796@qq.com 
官网：https://www.kancloud.cn/@tpcms
交流群：192979528
朕要体验：139.199.168.122/admin  test123 test123
