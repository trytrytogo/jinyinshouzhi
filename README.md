# 金银手指

青龙面板跑金银手指脚本教程（一天差不多1.2元）


## 前言：解放双手，挣点小毛。

注意：推荐一个容器运行1-2个账号，账号多了会限制，可以多容器跑

收益：只看文章的话，跑满每日12000金币（1.2元），被限制阅读另说
每满4000金币（4毛）微信自动提现


![Screenshot_20211009_124834_com.tencent.mm_edit_1966157526994256.jpg](https://i.loli.net/2021/10/09/2QxrqWNoTe7l15S.jpg)






**微信扫二维码，开启金银手指自动阅读文章**

![mmexport273500fe3f9e98d672683d677dcaded9_1633753891823_1_.png](https://i.loli.net/2021/10/09/Q87U3tPuz1gVmEL.png)

## 脚本链接：

```
主脚本：
ql raw https://raw.githubusercontent.com/KingRan/JD-Scripts/main/wx_jysz.js
定时：0 8-22/1 * * *

已经安装青龙自动修复依赖的下面的依赖可以不用管
安装依赖文件：crypto-js
进入容器输入：npm install crypto-js
```


![Snipaste_2021-10-09_12-37-30.jpg](https://i.loli.net/2021/10/09/uF9zLUeCODYqJNi.jpg)


运行脚本后会自动添加阅读任务



## 附依赖下载地址：(已经安装青龙自动修复依赖的下面的依赖可以不用管)

[http://shandianpan.com/f/8Oc6](https://www.juan920.com/?golink=aHR0cDovL3NoYW5kaWFucGFuLmNvbS9mLzhPYzY=)

## 重要部分：

青龙面板变量填写规则：

![](https://www.juan920.com/wp-content/uploads/2021/10/89a47a9915fa.png)

```
export soy_wx_jysz_token=""
export soy_wx_jysz_User_Agent=""

多个token用 @ 或 # 或 换行 隔开

特别注意：请使用自己的UA，防止被封，一个UA不超过两个token
```

## 开始步骤：

首先打开小黄鸟，开启抓包模式


抓包微信，微信再次扫描二维码，不用操作,自动阅读文章，阅读10S左右就可以返回，看到金币增加200即可,就会看到所需的变量值。




### 上面的TOKEN以及User_Agent的抓取教程：IOS和Android差不多，以Android为例：

（抓取变量Android使用小黄鸟，IOS使用Stream）

```
1、打开小黄鸟抓包,微信进金银手指界面 找有http://apponlie.sahaj.cn的连接
2、点进去他的请求头中token 和 User-Agent
```

![](https://www.juan920.com/wp-content/uploads/2021/10/e463b36b479a.jpg)

## 运行成功图：

![](https://www.juan920.com/wp-content/uploads/2021/10/3c54ff691157.png)
