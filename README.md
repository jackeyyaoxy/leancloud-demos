# leancloud-demos

LeanCloud SDK Demos 分类汇总

像著名的 [android-open-project](https://github.com/Trinea/android-open-project) ，这里分类汇总了 LeanCloud平台上的示例程序和开源应用。

欢迎大家推荐使用了 LeanCloud 的开源项目，也欢迎大家开源用 LeanCloud做的小应用、练手的应用，欢迎Fork、提交PR :) 

[内容与编辑规范](https://github.com/leancloud/leancloud-demos/wiki/%E5%86%85%E5%AE%B9%E7%BC%96%E8%BE%91%E4%B8%8E%E8%A7%84%E8%8C%83)

Demo 分类：[iOS](https://github.com/leancloud/leancloud-demos#ios)、[Android](https://github.com/leancloud/leancloud-demos#android)、[JavaScript](https://github.com/leancloud/leancloud-demos#javascript)、[微信与云代码](https://github.com/leancloud/leancloud-demos#%E5%BE%AE%E4%BF%A1%E4%B8%8E%E4%BA%91%E4%BB%A3%E7%A0%81)、[Unity](https://github.com/leancloud/leancloud-demos#unity)、[Windows Phone](https://github.com/leancloud/leancloud-demos#windows-phone)

## iOS

1. 微转  
微转是一个基于微博的数码设备二手交易平台，后台完全基于LeanCloud。     
项目地址：https://github.com/leancloud/VZ       
AppStore地址： [https://itunes.apple.com/cn/app/wei-zhuan/id768074220?mt=8](https://itunes.apple.com/cn/app/wei-zhuan/id768074220?mt=8)   
GIF 介绍：   
![vz6](https://cloud.githubusercontent.com/assets/5022872/7384112/500e7b70-ee5e-11e4-943e-06ce38951092.gif)

1. LZAlbum   
LZAlbum 是 基于 LeanCloud 的朋友圈。  
项目地址：https://github.com/lzwjava/LZAlbum  
GIF 介绍：  
![lzalbum](https://cloud.githubusercontent.com/assets/5022872/7377560/c02f5838-ee19-11e4-8817-df41c63311d0.gif)

1. LeanChat-iOS     
LeanChat 是用 LeanCloud 实时通信服务做的一个沟通工具。    
项目地址：https://github.com/leancloud/leanchat-ios

1. UUChatTableView+LeanCloud IM SDK  
此项目在 ZhipingYang 大牛开发的 [UUChatTableView](https://github.com/ZhipingYang/UUChatTableView) 的基础上加入了 LeanCloud IM SDK ，精美的UI 界面搭配了优雅的 IM 服务。在原项目加入少量代码，即能聊起来。LeanCloud IM SDK 能轻易集成到应用中，因为它只用 id 就跑通了整个聊天系统，与用户系统完全解耦。  
项目地址：https://github.com/lzwjava/UUChatTableView  
截图：  
![screen](https://cloud.githubusercontent.com/assets/5022872/7604267/4973b75c-f972-11e4-8e56-22509f995374.png)

1. FreeChat  
同样是聊天应用，不过功能完整许多，有最近对话、加入、踢人、开放对话(足球直播时很多人加入的对话，有别于普通的群聊)等功能示例。  
项目地址：https://github.com/jwfing/FreeChat  
截图：  
![](https://github.com/jwfing/FreeChat/blob/master/images/%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AF%A6%E6%83%85.png)  

1. photo-wall     
photo-wall 是用Swift写的一个照片墙应用，展示了基本的AVObject、AVFile、AVQuery的用法。   
项目地址：https://github.com/leancloud/photo-wall     
截图：          
![wall](https://cloud.githubusercontent.com/assets/5022872/5719710/d9e120d4-9b55-11e4-9677-01b461b24b23.png)

1. feedback-demo      
iOS平台上的一个小程序，展示了如何快速集成LeanCloud的用户反馈功能   
项目地址：https://github.com/leancloud/feedback-demo    

1. ios-simple-demo    
展示了 LeanCloud 的存储、统计功能。   
项目地址：https://github.com/leancloud/ios-simple-demo        
截图:         
![simple1](https://cloud.githubusercontent.com/assets/5022872/5718203/39fcbaf6-9b46-11e4-8bf4-f17fd08fc551.png)

1. dian-ping-shang-shu     
用LeanCloud做的商户管理的系统，用到了文件上传下载、数据增删改查、统计功能。     
项目地址：https://github.com/leancloud/dian-ping-shang-shu       
截图:           
![b](https://cloud.githubusercontent.com/assets/5022872/5717833/a9337ba8-9b41-11e4-9446-9e2dd88a65be.png)

1. share     
iOS小项目，主要用了 LeanCloud上 的事件流功能。   
项目地址：https://github.com/leancloud/share      


## Android 

1. LeanChat-Android   
LeanChat 是用 LeanCloud 实时通信服务做的一个沟通工具，有Android、iOS版本。后台也完全基于     LeanCloud，存储用户信息，好友关系等。     
项目地址：https://github.com/leancloud/leanchat-android      
截图：      
![img](https://raw.githubusercontent.com/lzwjava/plan/master/im361.png)     

1. android-simple-demo      
android-simple-demo 涉及到基本的增删改查、子类化、用户处理、文件处理，UI较简单，需要看代码学习。      
项目地址：https://github.com/leancloud/android-simple-demo      

1. android-todolist     
Android TodoList 小应用，涉及数据的增删改查、应用内搜索。    
项目地址：https://github.com/leancloud/android-todolist   
部分截图：      
![img](https://raw.githubusercontent.com/lzwjava/plan/master/android-todo-360.png)

1. android-keepalive      
实时通信方面的Demo，有单聊群聊，相对于 LeanChat要简单一些。  
项目地址：https://github.com/leancloud/android-keepalive      

1. android-push-demo      
推送 Demo，可学到如何快速集成 LeanCloud 的推送服务。      
项目地址：https://github.com/leancloud/android-push-demo      
截图：      
![img](https://raw.githubusercontent.com/lzwjava/plan/master/push.png)

1. android-sns-demo     
示例了 QQ 、微博授权登录。      
项目地址：https://github.com/leancloud/android-sns-demo  

1. android-sms-demo       
短信验证码示例项目。     
项目地址：https://github.com/leancloud/sms-demo

1. Anytime          
开发者“猫咪神“做的一个应用，有用户注册、登陆、登出和忘记密码等用户系统相关的功能。相对复杂一些的数据增删改查操作，也有消息推送。          
项目地址：https://github.com/lzwjava/AnyTime          


## JavaScript

1. ticket-app   
ticket-app是一个工单系统，用了大部分LeanCloud上的功能。   
项目地址：https://github.com/leancloud/ticket-app     
在线网站：https://ticket.avosapps.com   

1. todolist   
TodoMVC 的一个 LeanCloud 实现，涉及数据的增删改查，前端使用 JS SDK 的好例子。  
项目地址：https://github.com/leancloud/todo   
在线地址：https://todolist.avosapps.com     
![img](http://todomvc.com/site-assets/screenshot.png)

1. 眼缘         
眼缘 是 LeanCloud 的工程师在一次黑客马拉松的作品，通过匹配人脸来找到等待邂逅的对象，并且可以通过人脸来登录系统，使用了 LeanCloud 云代码和 JS SDK ，Face++ SDK 。            
项目地址：https://github.com/leancloud/hackthon-eye         
在线地址：http://eye.avosapps.com/        

1. 留言板     
留言板是一个很好的上手项目，展示了 JS SDK 的最基本的用法。    
项目地址：https://github.com/killme2008/cloudcode-test      
在线地址：https://myapp.avosapps.com      

1. LeanChat服务端     
LeanChat的后台源码，有添加好友等逻辑，展示了如何用云代码作为应用后端，实现更复杂的后端逻辑。      
项目地址：https://github.com/leancloud/leanchat-cloudcode           

1. 微转服务端     
微转服务端给微转提供了部分接口，好实现较复杂的后端逻辑。      
项目地址：https://github.com/leancloud/VZ_Server          

1. cloud-code-alipay     
云代码接入支付宝的例子，利用云代码集成了支付宝即时到账收款的功能。      
项目地址：https://github.com/leancloud/cloud-code-alipay      

## 微信与云代码    
1. cloud-code-weixin      
云代码接入微信的例子，利用云代码可快速搭建微信服务号的后端。      
项目地址：https://github.com/leancloud/cloud-code-weixin        


## Unity

1. flappy-bird-with-leancloud        
用LeanCloud Unity SDK 做的 flappy-bird。      
项目地址：https://github.com/leancloud/unity-sdk-demos      

## Windows Phone      
1. Tutorial     
WP SDK 的教程     
项目地址：https://github.com/leancloud/windows-phone-sdk-demos        
  
