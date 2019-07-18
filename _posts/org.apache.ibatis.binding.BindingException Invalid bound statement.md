---
layout:     post
title:      org.apache.ibatis.binding.BindingException: Invalid bound statement
subtitle:   mybatis中dao接口与mapper配置文件在做映射绑定的时候出现问题
date:       2019-07-19
author:     chenyeshen
header-img: img/bg2.jpg
catalog: true
tags:
    - SpringBoot
    - Mybatis
    - Mapper

---

org.apache.ibatis.binding.BindingException: Invalid bound statement (not found)问题，即在mybatis中dao接口与mapper配置文件在做映射绑定的时候出现问题，简单说，就是接口与xml要么是找不到，要么是找到了却匹配不到。

截图为网络中搜索到的常见原因：

![img](https://chenyeshen.oss-cn-shenzhen.aliyuncs.com/oneblog/article/20190716002234451.png)

照着修改之后，问题依旧存在。最终花费了好大的力气才找到自己代码问题的根源。dao接口与xml的文件名不一致。

接口名与接口文件名都是DepartmentDao, 而配置文件名为DeparmentDao.xml，费了很大的劲才看到两者名字查一个t字母。修改后就一切正常了。

### 这是一个很容易忽视的点，记住：接口名与Mybatis的映射文件名一定要一模一样。

![img](https://chenyeshen.oss-cn-shenzhen.aliyuncs.com/oneblog/20190716002302874.png) 
