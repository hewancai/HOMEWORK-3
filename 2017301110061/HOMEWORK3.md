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
