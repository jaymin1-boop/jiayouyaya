# 加油鸭鸭



# 金银手指同样套路 链接  https://github.com/ray154856235/jinyinshouzhi/blob/main/README.md



# 下面是加油鸭鸭脚本教程

# 使用微信扫描二维码
![image](https://user-images.githubusercontent.com/82143246/137112503-5a7774bb-e64f-4c27-bbdd-c38be1d726e8.png)





抓取变量
仅演示安卓小黄鸟
先打开小黄鸟，选择目标应用 – 微信，开始抓包。
扫码进入加油鸭鸭界面，随意点击几下，或者进行一次阅读



![dYfyXPHYjkJVGqwJhEO2ZA.png](https://i.loli.net/2021/10/12/OmesvEHo6qPG1Xr.png)



然后返回小黄鸟，停止抓包，找到域名为
**zhengshih5jiekou.zhuandayup.cn**

的抓包记录，选择请求头中的
**Authorization**

 和
**User-Agent**

。
进入青龙面板，环境变量，添加变量。

● 必要变量：
`wx_jyy_token`


可选变量：
`wx_jyy_User_Agent`


![p6lxjh52GP2FWa-LEyJBQg.png](https://i.loli.net/2021/10/12/bWRNdFxs3M5lZeq.png)
多账号使用 #  隔开

脚本拉取
BASH

`ql raw https://raw.githubusercontent.com/gcdd1993/My-Scripts/master/yd/wx_jyy.js`


定时建议为（8点到22点，每一小时跑一次）


`0 8-22 * * *`

