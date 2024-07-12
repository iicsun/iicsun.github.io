
# 1. 少儿编程-软件

## 1.1 Scratch

Scratch3.0 Web版 （Srcatch-GUI） 是一个部署在服务器上的Web版本，
是MIT的Scratch开发团队联合谷歌合作开发新一代开源式“Scratch”积木，会融合更多社区资源，为更广泛的用户服务，
并运作于更多类别的设备上，为移动设备提供更好的支持，只要有浏览器就可以使用Scratch。

### 1.1.1 Scratch源码及安装
Scratch基于Node.js开发，Github上提供了源码地址和安装手册：https://github.com/LLK/scratch-gui

镜像名称：Scratch 网页版-少儿在线编程工具
镜像地址：https://market.aliyun.com/products/56014009/cmjj00035326.html

### 1.1.2 Scratch 教程(夸克网盘)
scratch3.0初级篇教程
scratch3.0中级篇教程
scratch3.0高级篇教程
scratch3.0中级篇-素材
scratch3.0高级篇-素材

### 1.1.4 Scratch与硬件的结合
Scratch也支持包括Arduino、Micro:bit在内的许多著名硬件平台，孩子们可以更深入地探索硬件与软件之间的交互关系。

### 1.1.5 Scratch与Microbit的结合
体验完scratch与micro:bit的互动，我们来分析一下官方是如何做到的。
回顾使用说明和体验过程，容易猜到Scratch Link起代理的作用，Scratch Link在内部跑了一个websocket服务，允许网页与其交互，同时在启动时扫描周围的BLE设备
思路和scratch3-adapter几乎完全一致
Scratch Link与scratch3-adapter的不同之处有：

Scratch Link目前不支持扩展，似乎也没计划开源，原因可能我猜测是Scratch Link将支持乐高机器人，而乐高机器人是闭源商业项目。scratch3-adapter允许你自行扩展
Scratch Link在使用上更为简易
scratch3-adapter兼容更多的系统环境以及支持所有的开源硬件

Scratch Link在易用性上做得非常好，这也scratch3-adapter准备向它学习的地方。scratch3-adapter的目标之一是完全兼容Scratch Link的功能
这篇文章就来分析一下官方在这块的巧思。以便于我们可以将其用到其他地方。

## 1.2 Blockly
Blockly 是 Google 出品的一款可视化编程工具，它使用积木的形式将编程代码可视化，配合易用性强的 UI 界面，无疑是一个绝佳的编程学习工具，即使是完全没有编程经验的孩子也能轻松上手。
Blockly作为一个可视化编程环境，正逐渐流行，那么你如何利用它呢，下边的优势举例可能对你有启发：

可导出的代码: 可以将基于block程序转化为基于普通文本的常规代码（多语言）
开源： 可以以任何方式定制/使用它，甚至入侵修改它的内核
可拓展： 通过添加定制化的block关联到你的api上 （将提供服务的部分视为下位机，对外提供api/指令集）
生产可用：blockly不是一个玩具，你可以用它完成复杂的编程任务，例如写一个可以计算标准差的block
国际化：blockly支持40多门语言

缺点:访问不方便需要科学上网

## 1.3 其他编程语言
1. Python
2. JavaScript
3. Html

# 2. 少儿编程-硬件

## 2.1 MicroBit

## 2.2 DFRobot
也是以Microbit为核心板

## 2.3 掌控版
有一个小液晶

## 2.4 anduino
也支持Scratch编程。


# 3. 少儿编程-培训机构

## 3.1 少儿编程-橙旭园-陈斌

### 3.1.2 橙旭园课程体系及主要内容

0. 橙旭园编程学校 
	https://www.coding61.com/static/index-image/index.html
1. 冒险岛
	
2. Scratch
	https://www.coding61.com/scratch3/#1
3. AppLab 
	https://www.coding61.com/projects/applab/index/
4. 游戏实验室



### 3.1.2 作者的少儿编程书
1. Scratch3.0趣味编程教程
2. Python趣味编程教程

## 3.1 少儿编程-编程猫


# 4. 少儿编程-竞赛

### 4.0 相关资源
https://gitee.com/winant/oi
https://github.com/winterant/oi


### 4.1 OI (Olympiad in Informatics, 信息学奥林匹克)
信息学奥赛是中国中小学生五大学科竞赛之一。和数学，物理，化学，生物竞赛，并称为五大学科竞赛。是我国信息学，计算机学科竞赛的最具含金量的赛事。 获得提高组奖项的学员，有机会得到各大名校的降分签约，以低于录取线几十分的成绩进入心仪的大学。
官网 https://www.noi.cn

### 4.2 CSP-J/S（CCF非专业级别软件能力认证）
2019年，CCF发布暂停举办NOIP（初中组）的消息，并随即推出了CCF非专业级别软件能力认证，也就是CSP-J/S。
全国统一大纲、统一认证题目，编程语言只能使用C++，任何人均可报名参加。
CSP-S成绩优异者，可参加NOI省级选拔（NOIP），省级选拔成绩优异者可参加NOI。
CSP-J/S分为CSP-J（入门级，Junior）和CSP-S（提高级，Senior）。
两个赛道难度不同，均涉及算法和编程。
两个赛道都分为两轮进行，第一轮成绩优异者可晋级第二轮参赛，第二轮成绩评选一二三等奖。

### 4.3  NOIP（全国青少年信息学奥林匹克联赛）
始于1995年，全国统一大纲、统一试卷。分为入门组和提高组，分别对应初中生和高中生。
自2019年起，NOIP停办入门组（初中组），从此仅面向高中学生参加，参赛人数仅限一万人。
自2019年起，参赛方式调整为两种：CSP-S中取得优秀成绩者；CCF认可的指导教师推荐。
自2022年起，编程语言只能使用C++，不可使用其他编程语言。
收录了1995~2018年初赛试题+参考答案，复赛试题+测试数据+部分参考程序。
收录了2020~至今的复赛试题+测试数据+部分参考程序。

### 4.4  NOI (全国青少年信息学奥林匹克竞赛)
只能通过参加NOIP获得报名资格。

### 4.5  IOI (International Olympiad in Informatics, 国际信息学奥林匹克)
每个国家可以派出4名选手。


# 5. 少儿编程-学习环境
1. PC电脑usb连接Microbit板
2. Android平板通过otg-usb线连接Microbit板卡 或者蓝牙方式下载
