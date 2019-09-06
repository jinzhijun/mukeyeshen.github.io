---
layout:     post
title:      如何免费激活Windows10 只需要Copy&Paste
subtitle:   学习笔记
date:       2019-09-07
author:     chenyeshen
header-img: img/img13.jpg
catalog: true
tags:
    - 免费激活Windows10
    - 激活Windows10
---

### 在cmd 中 或者powershell输入以下是激活分别需要用的指令

-  slmgr.vbs /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX
-  slmgr.vbs /skms kms.lotro.cc
-  slmgr.vbs /ato
-  slmgr.vbs -xpr   查询到期时间



**测试成功了**



方法2:

- 解除內建金鑰匙:  slmgr /upk 
- 打入金鑰匙指令:  slmgr /ipk XC88X-9N9QX-CDRVP-4XV22-RVV26
- 添加伺服器:  slmgr /skms kms.digiboy.ir
- 激活win10:  slmgr /ato

​    **测试失败 可能秘钥支持家庭版的 原因不清楚**



**如果是win10家庭版请把第一个指令换成以下这个**

```
 slmgr.vbs /ipk TX9XD-98N7V-6WMQ6-BX7FG-H8Q99
```

**win10企业版则是这个**

```
 slmgr.vbs /ipk nppr9-fwdcx-d2c8j-h872k-2yt43
```

