# V2rayW           
V2rayW、V2rayW配置说明 、V2rayW下载 、V2rayW使用教程 、vpn代理  



简介
----
v2rayW是windows平台上基于v2ray核心的一款简单UI程序，目前仅支持vmess协议，不支持shadowsocks和socks5。本站详细介绍v2rayW的安装和配置使用步骤，希望能帮到用v2rayW的网友

**提前准备：**  
1.已有服务端信息，如果您想获取科学上网服务器请点击[这里](https://github.com/githubvpn007/v2rayNvpn#%E8%8A%82%E7%82%B9%E5%88%86%E4%BA%AB)  
2.下载V2RayW，未下载的请到这个页面下载：[V2RayW客户端下载](https://github.com/Cenmrev/V2RayW/releases)  

<br/>


操作步骤
----

1. 安装客户端：找到下载的安装程序，找一个合适的目录解压（不建议放在C盘的”Program Files”文件夹下，会有权限问题）；  
2. 双击文件夹内的“V2RayW.exe”，程序启动后系统托盘内会出现图标（系统托盘就是桌面右下角，显示时间输入法那块）。如果程序没有反应，托盘下也没有出现图标，请先更新系统并安装 [.NET Framework 4.7.2](https://dotnet.microsoft.com/download/dotnet-framework) 和 [Microsoft Visual C++ 2015 Redistributable (x86)](https://www.microsoft.com/en-us/download/details.aspx?id=53840)。
  
![](https://i.postimg.cc/t467sVJC/v2rayw-1.png)
  
  
3.右键系统托盘的**V2RayW图标**，点击“配置”。在配置窗口点击“增加”，然后在右侧“服务器信息”中填入**服务器的ip**、**端口**、**用户id**和**额外id**(注：有些小白可能不知道哪里获得这些信息，这些信息是在您购买了**付费代理**后代理商会给到您的信息，如果您不知道在哪里购买的话 请看[这里](https://github.com/githubvpn007/v2rayNvpn#%E8%8A%82%E7%82%B9%E5%88%86%E4%BA%AB))  
加密方式一般选“auto”，网络类型和传输设置请与服务端保持一致（例如tcp或者ws）。在标签一栏填一个好记的名字，例如“小黄vmess”。  

如果使用伪装等高级技巧（没用就不用管！），点击“传输设置”，在里面配置websocket的域名、路径信息，以及配置tls一栏（勾选allowinscure等两个框）。配置好后，点击”保存“：  

![](https://i.postimg.cc/s2Rx7DGP/v2rayw-2.png)  

使用中遇到问题，请把日志等级选“info”，方便查看日志。  


4.右键托盘图标，点击“加载v2ray”，建议勾选“自动模式（pac）”：  
![](https://i.postimg.cc/W463nL0B/v2rayw-3.png)  


5.如果没有特殊需求，一般不建议改动”V2ray内部路由规则”和“PAC列表”的信息；如果你知道具体用途，可按需更改。

服务器信息配置无误的话，接下来就可以愉快的访问google的境外网站了。



<br/>

## 如果您对科学上网一知半解 迷迷糊糊，迫切想弄懂各种科学上网的工具 各种协议的区别的话  请[点击这里](https://github.com/githubvpn007/v2rayNvpn)
