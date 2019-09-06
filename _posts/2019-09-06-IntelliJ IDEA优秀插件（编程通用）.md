---
layout:     post
title:      IntelliJ IDEA优秀插件（编程通用）
subtitle:   学习笔记
date:       2019-09-06
author:     chenyeshen
header-img: img/img29.jpg
catalog: true
tags:
    - 插件
    - IntelliJ IDEA
    - idea
---



Statistic	代码统计
CheckStyle	代码格式检查(可以自己/公司脚本)
FindBugs	bugs插件
SonarLint	bugs插件
grep Console	控制台插件
.ignore	git 文件提交过滤
CodeGlance	右侧文档结构图
Background Image Plus	设置背景图片: view -> Set Backgroup Image
Key promoter	快捷键提示，将鼠标放上去的时候会有提示
Markdown support	编辑Markdown文件 .md 文件
Maven Helper	maven插件，打开该pom文件的Dependency Analyzer视图
GsonFormat	将json转换为object
JRebel for IntelliJ	是一款热部署插件
AceJump	代替鼠标的软件，按快捷键进入 AceJump 模式后（默认是 Ctrl+J）
javaDoc	注释插件
Free MyBatis plugin                 Mybatis插件


## 二、IDEA插件安装

IDEA的插件安装非常简单，对于很多插件来说，只要你知道插件的名字就可以在IDEA里面直接安装。 
![这里写图片描述](https://chenyeshen.oss-cn-shenzhen.aliyuncs.com/oneblog/article/20190906202512673.png)

```
Preferences—>Plugins—>查找所需插件—>Install
```

或者

```
Preferences—>Plugins—>Install plug from disk —>选择下载好的插件安装
```

安装之后重启IDEA即可生效

## 三、插件介绍

#### 1、[activate-power-mode](https://github.com/ViceFantasyPlace/activate-power-mode)

最先介绍的就是这个装B插件了，美术和策划妹子来围观的时候发挥出最大作用了。 
![这里写图片描述](https://chenyeshen.oss-cn-shenzhen.aliyuncs.com/oneblog/article/20190906202513253.png)

#### 2、IdeaVim

我所有写代码的编辑器，都要安装VIM插件，我觉得这是一种VIM的精神， 
IdeaVim是一个Vim仿真插件，用于基于IntelliJ平台上的IDE。使用IDE的插件管理器来安装这款插件的最新版本。正常启动IDE，使用“Tools | Vim Emulator”菜单项来启动Vim仿真。这时，你在所有的编辑器上都必须使用Vim键盘输入。

如果你想要禁用此插件，那么选择“Tools | Vim Emulator”菜单不被选中。此时IDE会使用常规的键盘快捷键。 Vim仿真与IDE之间的键盘快捷键冲突，可以通过 “File | Settings | Vim Emulation”，“File | Settings | Keymap” 以及在 ~/.ideavimrc 文件中的键映射命令解决。

#### 3、 [CodeGlance](https://plugins.jetbrains.com/plugin/7275-codeglance)

类似SublimeText的Mini Map插件 
![这里写图片描述](https://chenyeshen.oss-cn-shenzhen.aliyuncs.com/oneblog/article/20190906202511967.png)

### 4、Background Image Plus

这又是一款装备B插件了，想想别人看到你的IDE有个美女或者异次元背景是怎样的，安装之后，在打开View选项，就可以看到Set Background Image选项了。 
![这里写图片描述](https://chenyeshen.oss-cn-shenzhen.aliyuncs.com/oneblog/article/20190906202531234.png)

#### 5、Shifter

检测光标所在选中、行或关键字的类型，然后用键盘快捷键上的“up”或“down”键移动它。如果在一行中只有一个可移动的单词，那么它不需要碰触光标，我们就可以移动它。支持小写/大写或小写所移动单词中的第一个大写的字符。

默认键盘快捷键：

```
Ctrl + Shift + Alt+逗号：下移
Ctrl + Shift + Alt +句号：上移
Ctrl + Shift + Alt + K：上移更多
Ctrl + Shift + Alt + J：下移更多

```

移动更多：多次重复选择所选中的值。重复次数可在插件配置中进行配置（默认为10）。

#### 6、BrowseWordAtCaret

允许轻松地在光标处浏览下一个/前一个单词，并突出选中单词的其他表象。用法：用CTRL-ALT-UP、CTRL-ALT-DOWN浏览（注：在默认键映射中此快捷方式也可用于下一个/上一个事件）。

#### 7、 AceJump

AceJump其实是一款能够代替鼠标的软件，只要安装了这款插件，可以在代码中跳转到任意位置。按快捷键进入 AceJump 模式后（默认是 Ctrl+J），再按任一个字符，插件就会在屏幕中这个字符的所有出现位置都打上标签，你只要再按一下标签的字符，就能把光标移到该位置上。换言之，你要移动光标时，眼睛一直看着目标位置就行了，根本不用管光标的当前位置。

#### 8. Markdown support

安装这个插件之后，打开.md文件就可以通过一个支持md的视图查看和编辑内容。一般用于写README.md文件。 
![这里写图片描述](https://chenyeshen.oss-cn-shenzhen.aliyuncs.com/oneblog/article/20190906202510369.png)

#### 9、Key promoter

Key promoter这款插件适合新手使用。当你点击鼠标一个功能的时候，可以提示你这个功能快捷键是什么。这是一个非常有用的功能，很快就可以熟悉软件的快捷功能了。 
如果有快捷键的，会直接显示快捷键 
![这里写图片描述](https://chenyeshen.oss-cn-shenzhen.aliyuncs.com/oneblog/article/20190906202512312.png) 
没有快捷键的，会提示你去设置快捷键。比如我连续3次用鼠标创建TypeScript类，第三次就会出现下面的提示 
![这里写图片描述](https://chenyeshen.oss-cn-shenzhen.aliyuncs.com/oneblog/article/20190906202509788.png) 
选择是，自动弹到快捷键设置面板 
![这里写图片描述](https://chenyeshen.oss-cn-shenzhen.aliyuncs.com/oneblog/article/20190906202511450.png)

#### **10、Free Mybatis plugin**

一个蛮好用的mybatis插件,可以通过dao层的接口直接和mapper.xml标签id进行映射,点击下图左边的前头就可以跳转到对应的接口或是xml.

这种方式只对生成代理接口有效,对于通过session.select()的全路径的实现类是无效的

![img](https://chenyeshen.oss-cn-shenzhen.aliyuncs.com/oneblog/article/20190906203032436.png)

![img](https://chenyeshen.oss-cn-shenzhen.aliyuncs.com/oneblog/article/20190906203030806.png)

####   **11、GenerateSerialVersionUID**

**        **生成SerialVersionUID的一款插件,idea没有自动生成SerialVersionUID功能,但是这款功能可以,直接alt+insert就出来了

**        ![img](https://chenyeshen.oss-cn-shenzhen.aliyuncs.com/oneblog/article/20190906203032937.png)**

#### **12、Lombok plugin**

** **      只要加上@date不需要为实体类写get,set

**![img](https://chenyeshen.oss-cn-shenzhen.aliyuncs.com/oneblog/article/20190906203030399.png)**

#### **13、Maven Helper**

**        **idea自带的maven插件是蛮好用的各方面都很齐全,但是有些的时候jar冲突的依赖却难找,show dependenies打开的图解找依赖太不直观了,而且非常非常卡.这一点eclipse的maven找依赖就很简单,这款插件和eclipse那个一样,特别直观方便,找冲突的利器啊,炒鸡好用O(∩_∩)O

**    ![img](https://chenyeshen.oss-cn-shenzhen.aliyuncs.com/oneblog/article/20190906203031512.png)**



#### 14、Alibaba Java Coding Guidelines

经过247天的持续研发，阿里巴巴于10月14日在杭州云栖大会上，正式发布众所期待的《阿里巴巴Java开发规约》扫描插件！该插件由阿里巴巴P3C项目组研发。P3C是世界知名的反潜机，专门对付水下潜水艇，寓意是扫描出所有潜在的代码隐患。

为了让开发者更加方便、快速将规范推动并实行起来，阿里巴巴基于手册内容，研发了一套自动化的IDE检测插件（IDEA、Eclipse）。该插件在扫描代码后，将不符合规约的代码按Blocker/Critical/Major三个等级显示在下方，甚至在IDEA上，我们还基于Inspection机制提供了实时检测功能，编写代码的同时也能快速发现问题所在。对于历史代码，部分规则实现了批量一键修复的功能，如此爽心悦目的功能是不是很值得拥有？提升代码质量，提高团队研发效能，插件将会一路同行。 

![6630c2d7402f9b174d4ec090835ec8bf226.jpg](https://oscimg.oschina.net/oscnet/6630c2d7402f9b174d4ec090835ec8bf226.jpg)

#### 15、iBATIS/MyBatis plugin

轻松通过快捷键找到MyBatis中对应的Mapper和XML，CTRL+ALT+B 
![这里写图片描述](https://img-blog.csdn.net/20180104135030822?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQveGxnZW4xNTczODc=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast) 
![这里写图片描述](https://img-blog.csdn.net/20180104135040257?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQveGxnZW4xNTczODc=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

###### 

#### 16、CodeGlance

###### 类似SublimeText的Mini Map插件，看下图就知道什么用了： ![è¿éåå¾çæè¿°](https://img-blog.csdn.net/20180104135422440?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQveGxnZW4xNTczODc=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

#### 17、codehelper.generator

###### 可以让你在创建一个对象并赋值的时候，快速的生成代码，不需要一个一个属性的向里面set,根据new关键字，自动生成掉用set方法的代码，还可以一键填入默认值。GenAllSetter 特性在Java方法中, 根据 `new` 关键词, 为Java Bean 生成所有Setter方法。按GenAllSetter键两次, 会为Setter方法生成默认值。可在`Intellij Idea`中为`GenAllSetter`设置快捷键。如何使用:将光标移动到 `new` 语句的下一行。点击主菜单Tools-> Codehelper-> GenAllSetter, 或者按下`GenAllSetter`快捷键。GenDaoCode 特性根据Pojo 文件一键生成 Dao，Service，Xml，Sql文件。Pojo文件更新后一键更新对应的Sql和mybatis xml文件。提供insert，insertList，update，select，delete五种方法。能够批量生成多个Pojo的对应的文件。自动将pojo的注释添加到对应的Sql文件的注释中。 丰富的配置，如果没有配置文件，则会使用默认配置。可以在Intellij Idea中快捷键配置中配置快捷键。目前支持MySQL + Java，后续会支持更多的DB。如果喜欢我们的插件，非常感谢您的分享。GenDaoCode 使用方法主菜单Tools-> Codehelper-> GenDaoCode 按键便可生成代码。方法一：点击GenDaoCode，然后根据提示框输入Pojo名字，多个Pojo以 | 分隔。Codehelper Generator会根据默认配置为您生成代码。方法二：在工程目录下添加文件名为codehelper.properties的文件。点击GenDaoCode，Codehelper Generator会根据您的配置文件为您生成代码![Screenshot #16302](http://plugins.jetbrains.com/files/8640/screenshot_16302.png)![Screenshot #16302](http://plugins.jetbrains.com/files/8640/screenshot_16302.png)

#### 18、 Material Theme UI

###### 这是一款主题插件，可以让你的ide的图标变漂亮，配色搭配的很到位，还可以切换不同的颜色，甚至可以自定义颜色。默认的配色就很漂亮了，如果需要修改配色，可以在工具栏中Tools->Material Theme然后修改配色等。

#### 19、 Background image Plus

###### 这是一款可以设置idea背景图片的插件，不但可以设置固体的图片，还可以设置一段时间后随机变化背景图片，以及设置图片的透明度等等。

#### 20.、 active-power-mode

###### 这是一款让你在编码的时候，整个屏幕都为之颤抖的插件。

###### ![img](https://static.oschina.net/uploads/img/201807/17102846_aBZJ.gif)![772743-20180411232130374-2087271550.gif](https://images2018.cnblogs.com/blog/772743/201804/772743-20180411232130374-2087271550.gif)

#### 21、Nyan progress bar

###### 这是一个将你idea中的所有的进度条都变成萌新动画的小插件。

###### ![img](https://static.oschina.net/uploads/img/201807/17102847_cL52.png)![772743-20180411233141721-621184731.png](https://images2018.cnblogs.com/blog/772743/201804/772743-20180411233141721-621184731.png)

#### 22、.ignore

###### git提交时过滤掉不需要提交的文件，很方便，有些本地文件是不需要提交到Git上的。

#### 23、CamelCase

###### 将不是驼峰格式的名称，快速转成驼峰格式，安装好后，选中要修改的名称，按快捷键shift+alt+u。