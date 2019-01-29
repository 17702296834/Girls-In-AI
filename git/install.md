# 初识 Git

欢迎大家来到 **GirlsInAI~~**👏 

**今天来带大家简单认识一下Git。**

1. Git & GitHub简介

2. 安装Git

   2.1 MacOS版本

   2.2 Windows版本



## 1.Git & GitHub简介
简单来说，GitHub 是一个网站，Git是一个工具。把我们电脑里的代码 通过git这个工具 **上传**到github这个云端网站上，把网站上的代码 通过git这个工具 **下载**到我们电脑里。  

- git是一个version control 版本控制的工具  

  什么是version control呢？比如我昨天写了10行代码，版本一，把这段代码上传到github上面；今天又写了2行，一共12行，版本二，再把版本二上传到github上面 , **github会帮助我们记录每一次的更新！** 比如过段时间，我们发现，版本二中的第二行错了，导致我们整个代码不能运行，那么我们可以随时返回到版本一。

- git允许多人操作
  比如同事A在马来西亚写了版本三，同事B在中国写了版本四。那么同事A上传之后，同事B也可以在A的基础上继续写代码，然后上传到github上的同一个工作文档。 



## 2.安装Git  
### 检查电脑里是否已经安装Git

这里需要用到一个“看起来酷酷的”小程序，Windows这个方框叫做Command Prompt；MacOS系统里这方框叫做Terminal（终端)。

### MacOS版本  
以MacOS为例，在Finder -> Applications -> Utilities找到Terminal， 点击打开。
![](https://github.com/YZHANG1270/Girls-In-AI/blob/master/others/pics/git/install/IMG_0729.jpg?raw=true)  

在命令行输入 `git version` 

![](https://github.com/YZHANG1270/Girls-In-AI/blob/master/others/pics/git/install/2.png?raw=true)  

如果你的电脑里面出现了git version x.xx.xx这个东西，那就说明你的电脑里已经装好git啦。
如果没有， 点击官方安装网址： [https://git-scm.com/download](https://git-scm.com/download)，选择MacOS版本，进行傻瓜式安装。



### Windows

打开cmd，输入`git version` 进行检查，如果电脑里没有git，请按下面步骤进行安装。

#### Step 1. 下载

安装环境：win10，64bit

下载地址：https://git-scm.com/download

![img](http://img.xiumi.us/xmi/ua/139aW/i/f225b8288d096329b25a60f7e930df1b-sz_146323.png)



#### Step 2. 安装

开始安装的界面：

![img](http://img.xiumi.us/xmi/ua/139aW/i/826f005671bf8f0d45cbdaf8885616ea-sz_32280.png)



安装路径，可以自由决定安装在C盘还是D盘：

![img](http://img.xiumi.us/xmi/ua/139aW/i/87475b7cf6d399f7b5b074de91355e41-sz_20897.png)

（此图片来自于https://www.jianshu.com/p/414ccd423efc）

安装组件：

![img](http://img.xiumi.us/xmi/ua/139aW/i/e2faf35e66f1c8158c0ba41f0c312731-sz_30074.png)



默认编辑器：

![img](http://img.xiumi.us/xmi/ua/139aW/i/078ebd0d4265bd63b59080f319a7399d-sz_31988.png)

修改系统环境变量：

![img](http://img.xiumi.us/xmi/ua/139aW/i/5c35c875c0f49c74a69332e615fba277-sz_36098.png)



第一项：只使用Git Bash，是最安全的。

第二项：使用Git Bash和命令行都可以控制Git。

第三项：要修改windows控制台指令，不安全不建议选择。



SSL的证书选择：（选择默认项）

![img](http://img.xiumi.us/xmi/ua/139aW/i/b5a45c1caa3a6b651b281099a98ed535-sz_26219.png)



配置行尾结束符：（选择默认项）

![img](http://img.xiumi.us/xmi/ua/139aW/i/e808739f1fc9b75526733850f0355d6b-sz_36794.png)



配置终端仿真：（选择默认项）

![img](http://img.xiumi.us/xmi/ua/139aW/i/3aa4d2a9e47359ef2a0e8d930d591bb7-sz_36745.png)



一些其他配置：（选择默认项）

![img](http://img.xiumi.us/xmi/ua/139aW/i/9e0652cfb056f7ea11a75cd94d713937-sz_35557.png)



终于开始安装啦：

![img](http://img.xiumi.us/xmi/ua/139aW/i/dfc8e1a420b0330904a3c30840bc5fda-sz_15506.png)

装好了以后，大家可以通过`git version`这个指令来查看自己当前git的版本，如果显示了一个版本，说明你已经成功安装git啦~
