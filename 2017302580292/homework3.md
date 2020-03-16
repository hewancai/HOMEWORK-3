## telnet whu.edu.cn 25
在windows程序设置中开启Telnet客户端后，可以在控制台使用Telnet命令。<br/>
![](pic/1-1.png)<br/>
得到连接成功的反馈<br/>
![](pic/1-2.png)<br/>
使用EHLO命令，获得whu.edu.cn邮箱服务器的可行性反馈。之后填写邮件内容并发送
![](pic/1-3.png)<br/>
另一个邮箱收到的邮件
![](pic/1-4.png)<br/>
___
## telnet math.whu.edu.cn 80
使用Telnet命令连接<br/>
![](pic/2-1.png)<br/>
服务器返回内容
![](pic/2-2.png)<br/>
___
## P4
![](pic/p4.png)<br/>
~~~
a.从get的文件/cs453/index.html和host地址gaia.cs.umass.edu可以组合得到URL为
    http://gaia.cs.umass.edu/cs453/index.html
b.HTTP/1.1 指明运行的是http1.1版本
c.报文末尾的connection:keep-alive指明是持续连接
d.此信息无法从get报文中获得
e.User-Agent部分可获得Mozilla/5.0。服务器需要浏览器类型信息以将同一对象的不同版本发送到不同类型的浏览器。
~~~
___
## P10
![](pic/p10.png)
~~~
十米的链路可忽略传播时延。
非持续：握手，下载初始对象，对引用对象并行握手后下载
t1  =3*(200b/150bps)+100000b/150bps+3*200b/(150/10)bps+100000b/(150/10)bps
    =7377.3s
持续：握手，下载初始对象，依次请求下载引用对象
t2  =3*(200b/150bps)+100000b/150bps+10*(200b/150bps+100000b/150bps)
    =7350.7s
该情况下，二者差异不大。
~~~
 <p align="right">刘涛<br/>2017302580292<br/>2020.03.16</p>