[1.代码编辑](#1)    
[2.数据库](#2)    
[3.调试小工具](#3)    
[4.绘图工具](#4)    
[5.浏览器插件](#5)

<h1 id='1'>代码编辑</h1>

1. webstorm    
[WebStorm 2018 LICENSE SERVER](https://blog.csdn.net/zajule/article/details/80674599)
2. [emacs](https://github.com/Style-sen/Emacs_conf)
3. VSCode
    1. [vs code上配置python的运行环境](https://www.cnblogs.com/EtoDemerzel/p/8083313.html)

<h1 id='2'>数据库</h1>

1. mysql


<h1 id='3'>调试小工具</h1>

1. [HTTPie](https://httpie.org/)    
命令行HTTP客户端是否具有直观的UI、JSON支持、语法突出显示、类似wget的下载、插件等等
2. [Wireshark]()
```
1. 选择需要监听网卡接口（capture interface)->启动;
2. 过滤协议
    "显示过滤"
    ip.addr ==192.168.1.1 //显示所有目标或源地址是192.168.1.1的数据包
    ip.dst==192.168.1.1 //显示目标地址是192.168.1.1的数据包
    ip.src ==192.168.1.1 //显示源地址是192.168.1.1的数据包
    eth.addr== 80:f6:2e:ce:3f:00   //根据MAC地址过滤
    ip.src==192.168.0.0/16   //网络过滤，过滤一个网段
    tcp.port==80   //端口号为80
    "捕获过滤"
    捕捉过滤抓包前在capture option中设置，仅捕获符合条件的包，可以避免产生较大的捕获文件和内存占用，但不能完整的复现测试时的网络环境。
    host 192.168.1.1      //抓取192.168.1.1 收到和发出的所有数据包
    src host 192.168.1.1    //源地址，192.168.1.1发出的所有数据包
    dst host 192.168.1.1    //目标地址，192.168.1.1收到的所有数据包
    src host hostname    //根据主机名过滤
    ether  host 80:05:09:03:E4:35    //根据MAC地址过滤
    net 192.168.1    //网络过滤，过滤整个网段
    src net 192.168
    dst net 192
    tcp port 80   # 指定捕获端口
    "使用“非/且/或”建立组合过滤条件可以获得更精确的捕获"
    非: ! or “not” (去掉双引号)
    且: && or “and”
    或: || or “or”
```

<h1 id='4'>绘图工具</h1>

1. [Inscape](https://inkscape.org/)
    跨平台的矢量图编辑。
    
<h1 id='5'>浏览器插件</h1>

插件商店：[Crx4Chrome](https://www.crx4chrome.com/)
1.[Saladict 沙拉查词](https://github.com/crimx/ext-saladict)
