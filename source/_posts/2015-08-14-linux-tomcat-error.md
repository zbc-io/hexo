---
title: Linux启动Tomcat报错：The file is absent or does not have execute permission
category:
- 技术
- Tomcat
tags:
- Linux
- Tomcat
---

错误信息如下：  

    Cannot find ./catalina.sh
    The file is absent or does not have execute permission
    This file is needed to run this program

原因：  

    没有权限  

解决：

    chmod 777 *.sh
