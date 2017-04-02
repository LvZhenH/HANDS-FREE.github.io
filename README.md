# 开源机器人项目 HANDS FREE

-------------------------------------------------
## 简介
HANDS FREE 是一个面向机器人研究、开发的开源软硬件系统。她有完备与科学的框架,以优秀的嵌入式系统框架为核心,精良的电路、机械设计为支撑,帮您快速实现多种形态的机器人。本系统包含机器人导航,SLAM,计算机视觉等模块,并拥有自己上层软件和调试系统。她支持国外其他的开源项目,如 ROS, MPRT, PIXHAWK 等,这一切都为您带来了无比的便捷和快乐!

## 资源索引

HandsFree 交流群: 521037187 (Hands Free Community)     

需要购买或者查看平台请看[淘宝店铺](https://shop145029875.taobao.com/?spm=a1z10.3-c.0.0.zpwB3d)  

最新最全资料请看: [HandsFree百度云](https://pan.baidu.com/s/1nuSvs7Z#list)   

最新代码请看: [HandsFree Github](https://github.com/HANDS-FREE)   

### 其他:  
- 可以通过百度云上的
[HandsFree_Introduction.pptx](https://pan.baidu.com/s/1nuSvs7Z#list/path=%2FHANDSFREE%2FHands_Free_Release%2F0_Documentation%2Fdocumentation&parentPath=%2FHANDSFREE) 
全面了解HandsFree的工作。
- [RosClub](http://www.rosclub.cn/post-14.html)   
- [西北工业大学布树辉教授个人博客](http://www.adv-ci.com/blog/source/hands-free/)    
- [exbot](http://wiki.exbot.net/HandsFree)
- [移动平台导航避障视频](http://v.youku.com/v_show/id_XMTUyODk4NTUzNg==.htm)    
- [研究领域视频展示](http://v.youku.com/v_show/id_XMTU0NzgwNzc3Mg==.html?from=y1.7-1.2) 

## 介绍
### HANDS FREE 组成
项目虽然看起来涉及很广，但目前主要任务大概有三个。      
一是 OpenRE 库，全称 Open Source Robot Embedded Library，也就是机器人嵌入式库，简单的说，角色和 pixhawk 类似，只不过 pixhwak 主要是面向飞行器，而 OpenRE 是面向多模态机器人的。  详细内容可以参考[OpenRE源码](https://github.com/HANDS-FREE/OpenRE)和[OpenRE wiki](https://github.com/HANDS-FREE/OpenRE/wiki)           
         
二是西北工业大学布树辉教授的实验室开发计算机视觉库 [PIL](https://github.com/HANDS-FREE/PIL )，布老师是我见过的特别优秀也让我特别敬佩的导师，喜欢机器人或者无人机领域的伙伴们可以关注一下他的[个人网站](http://www.adv-ci.com/blog/)，如果想读他研究生或者博士的伙伴也可以来联系群主。    
     
三是系统搭建，主要是基于前两个任务，以及 ROS 等开源项目，搭建各种机器人系统， 实现相应的功能， 给出搭建实体机器人系统的许多周边问题解决方案。机器人的机械设计，电路设计等都属于这个任务的范畴。详细内容可以参考
[ROS演示](https://github.com/HANDS-FREE/ROS_DEMO)      

其他：     
[HandsFree GUI](https://github.com/HANDS-FREE/handsfree_gui) 可视化上位机软件, 可用于基于[OpenRE](https://github.com/HANDS-FREE/OpenRE)的机器人系统。       

### 教程                 
- 关于购买的机器的入门教程，可以看
[Hands_Free_Robot_User_Manual.pdf](https://pan.baidu.com/s/1nuSvs7Z#list/path=%2FHANDSFREE%2FHands_Free_Release%2F0_Documentation%2Fdocumentation&parentPath=%2FHANDSFREE)

- 关于OpenRE2.x版本可以先看百度云上的老版教程
[OpenRE_Manual.pdf](https://pan.baidu.com/s/1nuSvs7Z#list/path=%2FHANDSFREE%2FHands_Free_Release%2F0_Documentation%2Fdocumentation&parentPath=%2FHANDSFREE) ， 最新的OpenRE3.0的教程会在[OpenRE wiki](https://github.com/HANDS-FREE/OpenRE/wiki)上更新

### 平台介绍
目前HandsFree共发布过JiLong2WD , JLong3WD ,  Stone 三款平台， 其中JiLong2WD , JLong3WD 2016上半年已经停止生产，不过仍然支持HandsFree的OpenRE3.0。   
2016下半年至今，经过对系统的不断完善，将在4月份推出新版的Mini , 和 Giraffe 平台。
相关介绍，待续。。。。。。

## HANDS FREE 鸡汤

### 概述
当你热爱某种事物，你可能会想办法去弥补它身上的缺点，即使意味着会牺牲你一点点，我们只是一群呆在大学里幼稚青年，但我们也有着对机器人事业的向往。     

Hands Free， 顾名思义解放双手。 我们想做到的是能够搭建一个共享的平台，一个友好的易于共同开发的框架。Hands Free 从嵌入式平台开始，逐步地扩展到了相应的其他周边，为的是让整个机器人的开发过程降低耦合，尽可能地减少一些底层的开发环节，在开发过程中提供了一个更好的交流方式。Hands Free 其理念核心是优化开发过程的同时，让设计的 idea 的分享过程更加 Free，是乐于分享的，鼓励分享的。        

Hands Free Team 是一个乐于奉献于机器人事业的团队，我们希望能为每一个走进机器人世界的学者带来便利。HANDS FREE 理念总结成一句话：创造一个机会共同成长。  
          
如果你觉得“哎呦不错”的话，就一起加入进来吧！！！                   

### 理念：  
探索，成长，分享

### 宗旨：  
以学习和科研为第一要义，对知识和技术的追求永无止境，不断创新，精益求精，提升自我； 其次，尽能力承担一定的社会责任，重视分享；最后，鼓励创造社会价值和财富以维持长期发展。

### 内容：  
HANDS FREE 是一个面向机器人研究、开发的开源软硬件系统。她有完备与科学的框架， 以优秀的嵌入式系统框架为核心， 精良的电路、 机械设计为支撑，帮您快速实现多种形态的机器人。本系统包含机器人导航，SLAM，计算机视觉等模块， 并拥有自己上层软件和调试系统。 她支持国外其他的开源项目， 如 ROS,MPRT, PIXHAWK 等，这一切都为您带来了无比的便捷和快乐！

###  现状： (梦想很丰满 现实很骨感)
HANDS FREE 是一个机器人开源项目，涵盖了和机器人相关的许多方面。我们面向开源的主要任务是搭建一个机器人系统， 并且尽可能使用各种工具来实现目的。       

Hands Free 人员由 **Hands Free Team** ， **Hands FreeCommunity** 组成。      

**Hands Free Team** 是 Hands Free 的缔造者和主要开发人员，负责更新，管理，建设 Hands Free 开源社区。目前 Hands Free 团队主要是由西北工业大学，厦门大学等几所大学的学生或者实验室组成。         

**Hands FreeCommunity** ，指所有参与，使用该开源项目的伙伴构建的交流圈。任何人可以在遵守 Hands Free 的发布规则的前提下发布自己成果， 并可以申请Hands Free Team 的审核，通过后整合到官方版本中发布。
       
目前 Hands Free Team 只是可数的几个人在维护，我们希望能有志同道合的人加入我们，一起学习交流。      

## HANDS FREE开源协议

HANDS FREE的OPENRE和PIL库以及电路设计标准和机械标准遵循 BSD 3-Clause 许可证，使用者可自由使用到任何途径，也可以使用HANDS FREE的标准设计硬件并用于商业。    
                 
HANDS FREE设计的硬件成品，比如每款平台的机械结构和控制器等电路板，仅属于开放资料，使用者只能学习或者少量生产，不能在未授权的情况下用于批量生产和商业行为，否则追究法律责任。              
 
版权：该项目的版权HANDS FREE TEAM所有，项目中使用的其他开放源码，版权归其原创作者所有。         
 
说明：任何一个开源控，都可以在不干扰不混淆官方版本的前提下发布自己成果，并可以申请Hands Free Team的审核，通过审核的可以整合到官方版本中发布。          
