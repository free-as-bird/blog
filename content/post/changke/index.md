---
title: 好好校园跑🤐
description: 学有余力要注意锻炼身体哦
date: 2026-11-12 17:00:00+08:00
image: cover.jpg
tags: 
    - 科技
categories:
    - living
---

考虑到大家学无余力，而且次数挺多，还是推荐几个“好好”完成校园跑的方法。

## 定位漂移法
### 操作方法
浙大体艺跑步过程中，关闭手机定位➡️等待10s左右➡️打开手机定位➡️欣赏独特的路线（等待定位稳定后重复若干次）

### 原理解释
在浙大体艺跑步过程中，先关闭手机的定位功能，当定位重新被打开时，并不会精准的定位到手机位置，会有几十米的偏差，在几秒之内会校准。校准偏差的定位跳跃路径也被记录到我们的跑步历程中，校准时间短保证了速度远超十分配速，达到以走代跑的效果。

Deepseek给的专业解释：本质上是多种定位技术（GPS、Wi-Fi/基站、传感器）在强制重启后，各自的“启动时间线”不一致所导致的短暂混乱。系统可能先返回了缓存的旧位置或过时的网络定位结果，同时GPS和传感器还在后台努力“找回状态”。

## 虚拟定位法
所谓苹果手机（iOS）的专属福利。理论上 Android 可行，但可能要 Root（v.获取最高权限）你的手机，或者自行寻找工具。

### 操作方法（iOS）
[iOSRealRun-cli](https://github.com/sijunpeng123/iOSRealRun-cli)<br>
[ZJU_FakeRun](https://github.com/laiang04/ZJU_FakeRun)<br>
此类工具很多，仅列举了几个开源项目，可用性与iOS版本相关。

### 原理解释
Apple 官方为开发者和测试场景预留了“位置模拟”的合法通道，一些工具可以利用 iOS 系统开发者服务，通过 USB 或本机配对的方式，向系统发送模拟坐标指令，从而让系统向所有 App 报告一个虚假位置。这种方式不需要越狱，也不需要安装证书，但通常需要连接电脑或开启开发者模式。

## 一键式方法
Tired of the iOS lock-in of RealRun? Then switch to NeverRun.
### 操作方法（iOS）
1、打开 [NeverRun](https://run.alabtnt.cn/#/first-time)<br>
2、在**ZJU Username**框里输入自己浙大通行证的账号（就是学号），在**Password**框里输入浙大通行证的的密码，点击绿色的**Save**按钮<br>
3、耐心等待，屏幕上会出现你的信息，格式如下

    Is it you?<br>
    Then everything you provided seems OK to us.<br>

    xh    XXXXXXXXXX<br>
    xm    XXX<br>
    xymc  X学院

核对无误后点击**continue**<br>
4、点击**Get sportId**
5、等待30分钟左右
6、点击**Submit sport**，如果为女生请勾选**我是女生**

### 原理解释
自行阅读 https://run.alabtnt.cn/#/about
这里就解释一下为什么要等待30分钟。众所周知，校园跑要求10分钟内跑完一公里，三公里就是30分钟以内。你获取sportId就是你开始“跑步”的时间，30分钟之后提交就可以保证在“跑”完之前跑步记录没有被提交，防止被判断为无效。

## 应急
在浙大体艺跑步过程中按暂停键，可以获得1分钟时间，时间暂停了，但人可以继续跑。