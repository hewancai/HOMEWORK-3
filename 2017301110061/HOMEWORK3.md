首先是对邮件的telnet
1. 输入 telnet whu.edu.cn 25
2. 打个招呼 ehlo whu
3. 身份认证 auth login
4. 输入base64加密后的账户和密码
5. 邮件发送方 MAIL FROM: <2017301110061@whu.edu.cn>
6. 邮件接收方 RCPT TO: <3452614062@qq.com>
7. 以DATA开始输入数据 DATA
8. 以. 结尾 homework3 test .
9. QUIT
![image](https://github.com/20192021855-DCAN/HOMEWORK-3/blob/master/2017301110061/telnet邮箱.png)
![image](https://github.com/20192021855-DCAN/HOMEWORK-3/blob/master/2017301110061/telnet邮箱2.png)

对网页的telnet
1. 输入 telnet maths.whu.edu.cn 80
2. ctrl+]
3. 回车
4. GET 你想访问的页面 HTTP/2.0
Host: maths.whu.edu.cn
5. 获得页面
![image](https://github.com/20192021855-DCAN/HOMEWORK-3/blob/master/2017301110061/telnet网页.png)
![image](https://github.com/20192021855-DCAN/HOMEWORK-3/blob/master/2017301110061/telnet网页2.png)

习题
1. p1
FTFFF 
2. P5 
a） 状态代码200和短语ok表示服务器能够找到文档成功。答复于2008年3月7日星期二提供格林威治标准时间12:39:45。
b） 上一次修改index.html文档是在2005年12月10日星期六18:27:46 格林尼治时间。
c） 返回的文档中有3874个字节。
d） 返回文件的前五个字节是：<！医生服务器同意持久连接，如connection:Keep Alive字段所示
