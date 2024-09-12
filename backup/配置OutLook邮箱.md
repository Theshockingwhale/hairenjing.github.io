# 宇宙级好用软件OutLook傻瓜配置教程
## 前言
### 因为Foxmail实在难用（包括卡死、收不到邮件、邮件收半小时、界面无法关闭、开机偶尔不会自动启动等），没有道理不换界面更好设计更合理的OutLook来改善体验

### 以QQ邮箱为例
#### 1.进入设置
![5 qq设置1](https://github.com/user-attachments/assets/1a345dcb-4704-400d-80d0-2ee10d8fd365)
#### 2.切换到“账号”
![6 qq设置2](https://github.com/user-attachments/assets/5a064386-d3a5-4958-ab55-623225590544)
#### 3.往下拉，找到POP3/IMAP/SMTP服务这一项，确保开启，然后点击管理
![7 qq设置3](https://github.com/user-attachments/assets/0568f111-31e5-47fc-80b8-09596288eb16)
#### 4.点击生成授权码，把生成的码先复制下来等下使用
![8 qq设置4](https://github.com/user-attachments/assets/5dbc2234-decf-441d-b02c-eca3242bb691)
#### 5.打开OutLook，添加新账户，输入你的邮箱，点继续
![1 创建账户](https://github.com/user-attachments/assets/a3423b84-9b52-4395-8a3b-9a49f85a687c)
#### 6.确认一下提供商是IMAP，不确定的话就选择提供商->IMAP
![4 选择提供商](https://github.com/user-attachments/assets/4f8c1633-979e-49e7-bb15-99dc5b7ba80f)
#### 7.把之前的授权码复制过来，填在密码的位置，这些显示更多的选项可以不作修改
![2 创建2](https://github.com/user-attachments/assets/59a222fe-df8f-459b-a8ec-c94643b687ee)
![3 创建2](https://github.com/user-attachments/assets/e0066786-b3a2-4a02-bbf6-28a5770e33ad)

以上我的设置都是默认状态

#### 8.没有问题的话就可以使用了

#### 某些邮件可能会有如下问题：多一个/多个附件
![10，邮件问题](https://github.com/user-attachments/assets/9a0ff43b-57cb-415a-8dc2-3f615a3ca704)
#### 原因是新版的OutLook 中Exchange Server某个环节产生的，本身不是Bug，所以微软也不打算修复
#### 当编写的邮件附件先于文本写入的时候，读取文本会截断，并把这一部分识别为附件，据说下面这个选项有助于修复这个情况，但实际上我的并没有解决
![9 邮箱设置](https://github.com/user-attachments/assets/0c5a0183-ed82-41e3-8e1f-4cf780c1f4fb)
#### 设置如上图，选择纯文本和HTML均可，因为还有一个TNEF选项我这里没有
![11 微软官方解释](https://github.com/user-attachments/assets/1b7f9dd3-ad9b-4343-8e71-00d8355d27cc)
#### 这是官方的说明

### 不过再怎么样都比依托的Foxmail好用



#### 此外企业邮箱的配置要复杂一些，在第7步的地方要手动修改接收服务器和发送服务器的地址（某些时候还要填写SMTP密码），具体的地址可以查看自己企业邮箱的提示，比如263的如下图
![12 263邮箱服务器](https://github.com/user-attachments/assets/a1e333d8-7d68-4dc3-a88d-9b47b5b5bb89)



