# 前言

在新冠疫情期间，居民疫情服务系统成为了社区管理的重要工具。本项目基于微信小程序和Spring Boot技术，致力于为社区居民提供便捷的疫情信息查询、健康上报等服务。以下是本项目的详细介绍。

## 内容介绍

本项目主要包括以下几个功能模块：

1. 疫情资讯：实时推送最新的疫情动态、政策法规等信息，帮助居民了解疫情形势。
2. 健康上报：居民可自主上报体温、健康状况等信息，便于社区进行疫情防控。
3. 核酸检测：提供核酸检测预约、结果查询等功能，方便居民进行核酸检测。
4. 生活服务：整合周边商超、药店等生活服务资源，满足居民日常生活需求。

## 技术介绍

- 语言：Java
- 使用框架：Spring、Spring MVC、MyBatis、微信小程序
- 前端技术：JS、Vue、CSS3、Uniapp
- 开发工具：IDEA/Eclipse、Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是本项目中的一个示例代码，展示了如何使用Spring Boot接收微信小程序的请求：

```java
@RestController
@RequestMapping("/api")
public class WechatController {

    @PostMapping("/login")
    public ResponseEntity<String> login(@RequestBody User user) {
        // 实现用户登录逻辑
        String token = userService.login(user);
        return ResponseEntity.ok(token);
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/331138/31/13018/81076/68c64a58F93acbedf/97f570dccd6c8514.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/348010/19/3293/13328/68c64a31F33205c67/cb3abf44f90c8877.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/326593/15/20031/25181/68c64a31F3b2a4633/2418d0611c2cfd57.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/341724/2/3084/23259/68c64a31Ff47bfb45/66570836f004bd9e.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/330216/15/13094/18877/68c64a31Fa2fa177f/dc96bbf8edfdd640.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/337104/5/10731/23036/68c64a32F4ad8a464/71b6c46ff6af804f.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/333228/16/13208/18993/68c64a32Fd1097514/95276bd04eed8809.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/343012/25/3261/39630/68c64a33Fe6a9f853/600c3732bdf0d56e.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/350321/28/3171/31874/68c64a33F1427c37b/041f8207ef0adc73.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/331750/21/12907/35294/68c64a33F3abc2a45/3ef90666bb42bce7.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
