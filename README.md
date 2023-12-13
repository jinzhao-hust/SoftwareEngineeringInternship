# SoftwareEngineeringInternship
## 项目信息
**项目选题:** 二手书信息平台  
**小组成员:** 金钊，彭政，曾世鹏，殷梓达
## 项目简介
本项目是一个基于微信小程序的二手书信息平台。用户可以在平台上发布自己的二手书信息，也可以浏览其他用户发布的二手书信息。用户可以通过平台上的聊天功能与其他用户进行交流，从而达成交易。
由于小程序没能正式发布，所以需要使用者自行提供云环境，具体操作如下：
1. 在微信开发者工具中打开项目
2. 在云开发中创建云环境
3. 将云环境ID填入miniprogram/envList.js中的envId中
4. 再云环境中创建user，chat_record表
5. 编译运行