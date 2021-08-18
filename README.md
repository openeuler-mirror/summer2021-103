# Summer2021-No.103 完成在树莓派上部署测试服务平台Compass-CI

#### 介绍
https://gitee.com/openeuler-competition/summer-2021/issues/I3OBTK

#### 软件架构
本仓库中的代码作用主要服务于compass-CI在运行raspbian系统树莓派上的部署。

本次提交主要包括两个文件

compass-ci/ sparrow /0-package/os/raspbian

该文件为在树莓派上部署compass-CI的依赖列表

compass-ci/ sparrow /install-rasp

该文件为部署入口

由于在为运行raspbian的树莓派安装依赖的过程中，需要重启再次安装并确定依赖有没有安装完整，所以使用自动化部署脚本“install-tiny”很不方便，于是笔者编写了用于树莓派调试的部署脚本“install-rasp”。


#### 安装教程

1.  从compass-CI仓库获取源码
2.  将本文档中的代码添加的compass-CI源码的对应位置
3.  执行compass-ci/ sparrow /install-rasp并按照提示操作即可

#### 使用说明

1. 先下载compass-CI源码，然后将本仓库的文件添加到compass-CI的对应位置。

   compass-CI仓库：

   https://gitee.com/openeuler/compass-ci#compass-ci

2. 目前，我并没有有完全成功部署compass-CI仅仅完成了添加部署所需依赖的工作。

   在执行4-docker/buildall时遭遇了问题，正在寻求解决。

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request
