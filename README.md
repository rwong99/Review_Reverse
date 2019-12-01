> 郑重声明：本项目的所有代码和相关文章， 仅用于经验技术交流分享，禁止将相关技术应用到不正当途径，因为滥用技术产生的风险与本人无关。

# Review_Reverse 2019年末逆向复习系列（持续更新）

![](https://github.com/lateautumn4lin/Review_Reverse/blob/master/main.png)

# 前言

马上到2019年末啦！今年接触到到逆向案例还是很多，所以单开个项目给自己复习一下！

# 目录

- [案例分析](#案例分析)
  - [1 淘宝](#1-淘宝)
    - [1.1 WEB淘宝sign参数逆向破解](#1.1-WEB淘宝sign参数逆向破解)
  - [2 努比亚](#2-努比亚)
    - [2.1 努比亚Cookie生成逆向分析](#2.1-努比亚Cookie生成逆向分析)
  - [3 百度指数](#3-百度指数)
    - [3.1 百度指数Data加密逆向破解](#3.1-百度指数Data加密逆向破解)
  - [4 今日头条WEB版](#4-今日头条WEB版)
    - [4.1 今日头条WEB端_signature、as、cp参数逆向分析](#4.1-今日头条WEB端_signature、as、cp参数逆向分析)

# 案例分析

## 1 淘宝

## 1.1 WEB淘宝sign参数逆向破解

- **参考文章**：

  - [微信文章：2019年末逆向复习系列之淘宝M站Sign参数逆向分析](https://mp.weixin.qq.com/s?__biz=MzIzOTQzNDIyOA==&mid=100000296&idx=1&sn=bcb858c0b4f8f460d5cd6433965b9339&chksm=692b62b35e5ceba597b830ca4d7451b709c31c2aaa84351888ae7c5d82c68ef740cc53b4eb79&scene=0&xtrack=1&key=a089b840afa72487c5c947dd508eadd32a992303f4ecd2e171ce6677361f96b52daadccce30cb283e1639dffb4aa7b6c8aa6d499d0b1dd2af982b26ffd444c11bd5d07b6fd9c58e822fc2d7e77941498&ascene=1&uin=MjE5NTExNzYxMA%3D%3D&devicetype=Windows+10&version=62070158&lang=zh_CN&pass_ticket=vdb3234iVj%2FTN%2FTiZH4WfOoiCpc5yB%2FlSEc2AQtost8B7g3si%2B4YtP%2Bp6RRNb7Mc)

  - [个人博客文章：2019年末逆向复习系列之淘宝M站Sign参数逆向分析](https://cloudcrawler.club/tao-bao-m-zhan-sign-can-shu-ni-xiang-fen-xi.html)
- **逆向代码**：[WEB 淘宝 sign 参数破解代码](https://github.com/lateautumn4lin/Review_Reverse/blob/master/tb/m_tb.py)
- **实战代码**：[WEB 淘宝爬取代码](https://github.com/lateautumn4lin/Review_Reverse/blob/master/tb/m_tb_example.py)


## 2 努比亚

## 2.1 努比亚Cookie生成逆向分析

- **参考文章**：

  - [微信文章：2019年末逆向复习系列之努比亚Cookie生成逆向分析](https://mp.weixin.qq.com/s?__biz=MzIzOTQzNDIyOA==&mid=2247483980&idx=1&sn=c17b106f84cb8dd2cb88e774723bec75&chksm=e92b62d7de5cebc11f3ece8d458c76c183871b060549e01865c8e4b97ab6ce7ba47337d43a64&token=1415978371&lang=zh_CN#rd)

  - [个人博客文章：2019年末逆向复习系列之努比亚Cookie生成逆向分析](https://cloudcrawler.club/nu-bi-ya-cookie-sheng-cheng-ni-xiang-fen-xi.html)

- **逆向代码**：[努比亚Cookie参数破解代码](https://github.com/lateautumn4lin/Review_Reverse/blob/master/nubia/m_nubia.py)
- **实战代码**：[努比亚论坛爬取代码](https://github.com/lateautumn4lin/Review_Reverse/blob/master/test/test_m_nubia.py)

## 3 百度指数

## 3.1 百度指数Data加密逆向破解

- **参考文章**：

  - [微信文章：2019年末逆向复习系列之百度指数Data加密逆向破解](https://mp.weixin.qq.com/s?__biz=MzIzOTQzNDIyOA==&mid=2247484007&idx=1&sn=42cc87969f7912fdc1a68f5199cb173d&chksm=e92b62fcde5cebea0adb3f7d6bb4da2d848694b9f4f0cd5d69616bf428e7bcfad03a269ef699&token=283044481&lang=zh_CN#rd)

  - [个人博客文章：2019年末逆向复习系列之百度指数Data加密逆向破解](https://cloudcrawler.club/bai-du-zhi-shu-data-jia-mi-ni-xiang-po-jie.html)
  
## 4 今日头条WEB版

## 4.1 今日头条WEB端_signature、as、cp参数逆向分析

- **参考文章**：

  - [微信文章：2019年末逆向复习系列之今日头条WEB端_signature、as、cp参数逆向分析](https://mp.weixin.qq.com/s?__biz=MzIzOTQzNDIyOA==&mid=2247484007&idx=1&sn=42cc87969f7912fdc1a68f5199cb173d&chksm=e92b62fcde5cebea0adb3f7d6bb4da2d848694b9f4f0cd5d69616bf428e7bcfad03a269ef699&token=283044481&lang=zh_CN#rd)

  - [个人博客文章：2019年末逆向复习系列之今日头条WEB端_signature、as、cp参数逆向分析](https://cloudcrawler.club/bai-du-zhi-shu-data-jia-mi-ni-xiang-po-jie.html)

- **逆向代码**：[今日头条WEB端_signature、as、cp参数加密代码](https://github.com/lateautumn4lin/Review_Reverse/blob/master/baidu/baidu_index/m_baidu_index.py)
- **实战代码**：[今日头条WEB端文章爬取代码](https://github.com/lateautumn4lin/Review_Reverse/blob/master/baidu/baidu_index/m_baidu_index_example.py)
