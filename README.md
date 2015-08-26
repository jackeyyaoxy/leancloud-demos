# leancloud-demos

LeanCloud SDK Demos 分类汇总

像著名的 [android-open-project](https://github.com/Trinea/android-open-project) ，这里分类汇总了 LeanCloud平台上的示例程序和开源应用。

欢迎大家推荐使用了 LeanCloud 的开源项目，也欢迎大家开源用 LeanCloud做的小应用、练手的应用，欢迎Fork、提交PR :) 

[内容与编辑规范](https://github.com/leancloud/leancloud-demos/wiki/%E5%86%85%E5%AE%B9%E7%BC%96%E8%BE%91%E4%B8%8E%E8%A7%84%E8%8C%83)

对于下面的项目，若想下载到本地，请直接点击 Github 上的`Download Zip`，如图所示，这样只下载最新版本。如果是 `git clone`，则可能非常慢，因为含杂很大的提交历史。某次测试两者是 1.5M:40M。  
![qq20150618-2 2x](https://cloud.githubusercontent.com/assets/5022872/8223520/4c25415a-15ab-11e5-912d-b5dab916ce86.png)

对于 iOS 上的 CocoaPods 项目，请尽量试用 `pod install --no-repo-update` ，这样会大大加快 `pod install` 的速度。   
对于 Android 项目，大多数都是 Android Studio 所用的 Gradle 项目结构，导入 Eclipse 的话可能缺少某些类，请到 [SDK 下载页](https://leancloud.cn/docs/sdk_down.html)下载 SDK 手动添加依赖。

Demo 分类：[iOS](https://github.com/leancloud/leancloud-demos#ios)、[Swift](https://github.com/leancloud/leancloud-demos#swift)、[Android](https://github.com/leancloud/leancloud-demos#android)、[JavaScript](https://github.com/leancloud/leancloud-demos#javascript)、[微信与云代码](https://github.com/leancloud/leancloud-demos#%E5%BE%AE%E4%BF%A1%E4%B8%8E%E4%BA%91%E4%BB%A3%E7%A0%81)、[Unity](https://github.com/leancloud/leancloud-demos#unity)、[Windows Phone](https://github.com/leancloud/leancloud-demos#windows-phone)


## iOS

1. 微转    
![](https://img.shields.io/github/stars/leancloud/VZ.svg?style=social)  
微转是一个基于微博的数码设备二手交易平台，后台完全基于LeanCloud。     
项目地址：https://github.com/leancloud/VZ     
AppStore地址： [https://itunes.apple.com/cn/app/wei-zhuan/id768074220?mt=8](https://itunes.apple.com/cn/app/wei-zhuan/id768074220?mt=8)   
截图：   
![image](http://a5.mzstatic.com/us/r30/Purple/v4/83/b6/4a/83b64ae6-ed48-45e5-957c-09a925bb40e3/screen568x568.jpeg)

1. LZAlbum    
![](https://img.shields.io/github/stars/lzwjava/LZAlbum.svg?style=social)   
LZAlbum 是 基于 LeanCloud 的朋友圈。  
项目地址：https://github.com/lzwjava/LZAlbum  
截图：  
![lzalbum](https://cloud.githubusercontent.com/assets/5022872/7646374/0bffe1a0-faf5-11e4-8f56-f0006a3425a2.jpg)

1. LeanStorage-iOS-Demo   
![](https://img.shields.io/github/stars/leancloud/LeanStorage-Demo.svg?style=social)  
展示了 LeanCloud 的存储功能。   
项目地址：https://github.com/leancloud/LeanStorage-Demo      
截图:         
![demo2](https://cloud.githubusercontent.com/assets/5022872/7852211/71f4ac66-052c-11e5-868a-b98b34867a06.png)

1. LeanChat-iOS     
![](https://img.shields.io/github/stars/leancloud/leanchat-ios.svg?style=social)  
LeanChat 是用 LeanCloud 实时通信服务做的一个沟通工具。    
项目地址：https://github.com/leancloud/leanchat-ios

1. LeanMessageDemo-iOS    
![](https://img.shields.io/github/stars/leancloud/LeanMessage-Demo.svg?style=social)    
此项目是为了让大家能快速上手熟悉 LeanCloud IM SDK。之前推出的 LeanChat ，我们发现其中含杂了许多 UI 代码，不利于大家学习上手。因此我们推出了 LeanMessageDemo，只有最精简的 UI、最核心的 SDK 用法。  
项目地址：https://github.com/leancloud/LeanMessage-Demo

1. NextChat     
![](https://img.shields.io/github/stars/leancloud/NextChat.svg?style=social)    
NextChat = [JSQMessageViewController](https://github.com/jessesquires/JSQMessagesViewController) + LeanCloud IM SDK。JSQMessageViewController 大概是最流行的开源的 IM 界面框架了。 试试新的 UI 吧。  
项目地址：https://github.com/leancloud/NextChat  
截图：  
![ios simulator screen shot 2015 5 15 11 06 21](https://cloud.githubusercontent.com/assets/5022872/7646249/79a64f52-faf3-11e4-8334-85d6585edf01.png)

1. UUChatTableView+LeanCloud IM SDK   
![](https://img.shields.io/github/stars/lzwjava/UUChatTableView.svg?style=social)   
此项目在 ZhipingYang 大牛开发的 [UUChatTableView](https://github.com/ZhipingYang/UUChatTableView) 的基础上加入了 LeanCloud IM SDK ，精美的UI 界面搭配了优雅的 IM 服务。在原项目加入少量代码，即能聊起来。LeanCloud IM SDK 能轻易集成到应用中，因为它只用 id 就跑通了整个聊天系统，与用户系统完全解耦。  
项目地址：https://github.com/lzwjava/UUChatTableView  

1. FreeChat   
![](https://img.shields.io/github/stars/jwfing/FreeChat.svg?style=social)     
同样是聊天应用，不过功能完整许多，有最近对话、加入、踢人、开放对话(足球直播时很多人加入的对话，有别于普通的群聊)等功能示例。  
项目地址：https://github.com/jwfing/FreeChat  
截图：  
![](https://github.com/jwfing/FreeChat/blob/master/images/%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AF%A6%E6%83%85.png)   

1. dian-ping-shang-shu  
![](https://img.shields.io/github/stars/leancloud/dian-ping-shang-shu.svg?style=social)      
用LeanCloud做的商户管理的系统，用到了文件上传下载、数据增删改查、统计功能。     
项目地址：https://github.com/leancloud/dian-ping-shang-shu       

1. Share    
![](https://img.shields.io/github/stars/lzwjava/Share.svg?style=social)   
事件流系统的 Demo，有关注、发状态、时间线等功能。  
项目地址：https://github.com/lzwjava/Share  

## Swift  

1. WukongSNS    
![](https://img.shields.io/github/stars/pgbo/WukongSNS.svg?style=social)    
WukongSNS 是开发者 pgbo 做的一个类似朋友圈的 swift 项目，用了 AVObject Array 来实现点赞、评论，AVOSCloudIM 框架来实现通知提醒功能。非常推荐。    
项目地址：https://github.com/pgbo/WukongSNS   
项目截图：  
![wukong400](https://cloud.githubusercontent.com/assets/5022872/8989779/d819ae62-3720-11e5-8483-f0c80693c4b9.png)

1. photo-wall   
![](https://img.shields.io/github/stars/leancloud/photo-wall.svg?style=social)    
photo-wall 是用Swift写的一个照片墙应用，展示了基本的AVObject、AVFile、AVQuery的用法。   
项目地址：https://github.com/leancloud/photo-wall     
截图：          
![wall](https://cloud.githubusercontent.com/assets/5022872/5719710/d9e120d4-9b55-11e4-9677-01b461b24b23.png)

## Android 

1. LeanStorageDemo-Android    
![](https://img.shields.io/github/stars/leancloud/LeanStorage-Demo.svg?style=social)     
LeanStorageDemo-Android 涉及到基本的增删改查、子类化、用户处理、文件处理，很全面，非常推荐。      
项目地址：https://github.com/leancloud/LeanStorageDemo-Android  
截图：  
![device-2015-08-26-120002](https://cloud.githubusercontent.com/assets/5022872/9485437/92c4768c-4beb-11e5-8190-c74e586c2867.png)

1. LeanChat-Android   
![](https://img.shields.io/github/stars/leancloud/leanchat-android.svg?style=social)    
LeanChat 是用 LeanCloud 实时通信服务做的一个沟通工具，有Android、iOS版本。后台也完全基于     LeanCloud，存储用户信息，好友关系等。     
项目地址：https://github.com/leancloud/leanchat-android      
截图：      
![img](https://raw.githubusercontent.com/lzwjava/plan/master/im361.png)     

1. AnimeTaste   
![](https://img.shields.io/github/stars/daimajia/AnimeTaste.svg?style=social)   
AnimeTaste 是国内首个关注独立动画的网站。Android 移动版让人随时随地能观看动画。该应用曾获得[豌豆荚设计奖](http://www.wandoujia.com/award/blog/com.zhan_dui.animetaste)。其中，使用了 LeanCloud 来存储评论和用户反馈，可在 Terminal 中 `ack AVObject` 来找到相应的代码。    
项目地址：https://github.com/daimajia/AnimeTaste    
截图：    
![AnimeTaste](http://ww2.sinaimg.cn/mw690/610dc034jw1e885o9kjgzj208c0b40ty.jpg)   

1. LeanMessageDemo    
![](https://img.shields.io/github/stars/leancloud/LeanMessage-Demo.svg?style=social)    
此项目是为了让大家能快速上手熟悉 LeanCloud IM SDK。之前推出的 LeanChat ，我们发现其中含杂了许多 UI 代码，不利于大家学习上手。因此我们推出了 LeanMessageDemo ，只有最精简的 UI、最核心的 SDK 用法。  
项目地址：https://github.com/leancloud/LeanMessage-Demo  

1. android-todolist   
![](https://img.shields.io/github/stars/leancloud/android-todolist.svg?style=social)     
Android TodoList 小应用，涉及数据的增删改查、应用内搜索。    
项目地址：https://github.com/leancloud/android-todolist   
部分截图：      
![img](https://raw.githubusercontent.com/lzwjava/plan/master/android-todo-360.png)

1. WeShare    
![](https://img.shields.io/github/stars/lzwjava/WeShare.svg?style=social)   
此项目是用 LeanCloud [事件流系统](https://leancloud.cn/docs/status_system.html)组件做的类似朋友圈的分享小应用。具有时间线、发文字发图、点赞、关注的模块或功能。  
项目地址：https://github.com/lzwjava/WeShare

1. android-push-demo    
![](https://img.shields.io/github/stars/leancloud/android-push-demo.svg?style=social)       
推送 Demo，可学到如何快速集成 LeanCloud 的推送服务。      
项目地址：https://github.com/leancloud/android-push-demo      
截图：      
![img](https://raw.githubusercontent.com/lzwjava/plan/master/push.png)

1. android-sns-demo   
![](https://img.shields.io/github/stars/leancloud/android-sns-demo.svg?style=social)    
示例了 QQ 、微博授权登录。      
项目地址：https://github.com/leancloud/android-sns-demo  

1. android-sms-demo   
![](https://img.shields.io/github/stars/leancloud/sms-demo.svg?style=social)    
短信验证码示例项目。     
项目地址：https://github.com/leancloud/sms-demo

1. Anytime    
![](https://img.shields.io/github/stars/LunaGao/AnyTime.svg?style=social)       
开发者“猫咪神“做的一个应用，有用户注册、登陆、登出和忘记密码等用户系统相关的功能。相对复杂一些的数据增删改查操作，也有消息推送。          
项目地址：https://github.com/LunaGao/AnyTime        


## JavaScript

1. ticket-app   
![](https://img.shields.io/github/stars/leancloud/ticket-app.svg?style=social)    
ticket-app是一个工单系统，用了大部分LeanCloud上的功能。   
项目地址：https://github.com/leancloud/ticket-app     
在线网站：https://ticket.avosapps.com   

1. todolist   
![](https://img.shields.io/github/stars/leancloud/todo.svg?style=social)    
TodoMVC 的一个 LeanCloud 实现，涉及数据的增删改查，前端使用 JS SDK 的好例子。  
项目地址：https://github.com/leancloud/todo   
在线地址：https://todolist.avosapps.com     
![img](http://todomvc.com/site-assets/screenshot.png)

1. 眼缘   
![](https://img.shields.io/github/stars/leancloud/hackthon-eye.svg?style=social)         
眼缘 是 LeanCloud 的工程师在一次黑客马拉松的作品，通过匹配人脸来找到等待邂逅的对象，并且可以通过人脸来登录系统，使用了 LeanCloud 云代码和 JS SDK ，Face++ SDK 。            
项目地址：https://github.com/leancloud/hackthon-eye         
在线地址：http://eye.avosapps.com/        

1. 留言板   
![](https://img.shields.io/github/stars/killme2008/cloudcode-test.svg?style=social)   
留言板是一个很好的上手项目，展示了 JS SDK 的最基本的用法。    
项目地址：https://github.com/killme2008/cloudcode-test      
在线地址：https://myapp.avosapps.com      

1. LeanChat服务端   
![](https://img.shields.io/github/stars/leancloud/leanchat-cloudcode.svg?style=social)      
LeanChat的后台源码，有添加好友等逻辑，展示了如何用云代码作为应用后端，实现更复杂的后端逻辑。      
项目地址：https://github.com/leancloud/leanchat-cloudcode           

1. cloud-code-alipay    
![](https://img.shields.io/github/stars/leancloud/cloud-code-alipay.svg?style=social)   
云代码接入支付宝的例子，利用云代码集成了支付宝即时到账收款的功能。      
项目地址：https://github.com/leancloud/cloud-code-alipay     

1. 微转服务端   
![](https://img.shields.io/github/stars/leancloud/VZ_Server.svg?style=social)    
微转服务端给微转提供了部分接口，好实现较复杂的后端逻辑。      
项目地址：https://github.com/leancloud/VZ_Server

1. skd-demo-engine	
![](https://img.shields.io/github/stars/leancloud/sdk-demo-engine.svg?style=social)		
此项目展示了 SDK 与云引擎之间的数据交互。可以学到：如何传递 AVObject 到客户端？如何用 beforeSave Hook？如何搭一个简单的 LeanEngine 框架？  
项目地址：https://github.com/leancloud/sdk-demo-engine

## 微信与云代码    
1. cloud-code-weixin    
![](https://img.shields.io/github/stars/leancloud/cloud-code-weixin.svg?style=social)     
云代码接入微信的例子，利用云代码可快速搭建微信服务号的后端。      
项目地址：https://github.com/leancloud/cloud-code-weixin 

## Unity

1. flappy-bird-with-leancloud   
![](https://img.shields.io/github/stars/leancloud/unity-sdk-demos.svg?style=social)       
用LeanCloud Unity SDK 做的 flappy-bird。      
项目地址：https://github.com/leancloud/unity-sdk-demos      

## Windows Phone      
1. Tutorial   
![](https://img.shields.io/github/stars/leancloud/windows-phone-sdk-demos.svg?style=social)    
WP SDK 的教程     
项目地址：https://github.com/leancloud/windows-phone-sdk-demos        
  
