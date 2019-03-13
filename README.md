This repository is made for mainland Chinese users to block spam, not suitable for other areas.

# PureSMS
PureSMS 是一个整理基于正则表达式的短信屏蔽与放行规则的项目，主要针对中国大陆肆虐的各种垃圾短信。

项目将提供 JSON、XML、YAML 等格式的规则，JSON、XML含压缩版（.min）。

## FAQ
### Q.我该如何使用这些规则？
A1.如果你是 [NekoSMS](https://github.com/apsun/NekoSMS) 普通用户，遵循以下步骤即可：
- 在 [Releases](https://github.com/metaphilium/PureSMS/releases) 中下载 .nsbak 文件
- 将下载好的文件置于内置存储目录的 /NekoSMS 文件夹下
- 打开 NekoSMS 在黑/白名单规则界面点击右上角选择下载好的文件导入
- 先打开拦截通知试用一段时间，没有异常情况再关闭以防止不被期待的事情发生。

A2.如果你是非 NekoSMS 用户，请确保自己掌握一定的正则表达式（Regex）知识，然后将代码转换为供自己使用的格式。

### Q.使用时有哪些注意事项？
A.手动添加规则的用户注意将匹配方式改为「正则表达式」，由于银行、运营商等也会发送促销短信，规则不含发送者白名单，若要完全放行某发送者请添加发送者白名单或将其添加在通讯录中后在 NekoSMS 设置中开启联系人白名单。

### Q.使用这些规则有什么结果？
A.首先会让你的短信列表多少干净一些，但注意：**这些规则也可能使你的重要短信被拦截，使用该规则即表明使用者已知晓一切可能的后果并由清楚使用者自己承担所有责任。**

### Q.误杀正常短信怎么办？
A.首先确保这是公认的正常短信，然后将短信内容**完整地**写在 [Issues](https://github.com/metaphilium/PureSMS/issues) 里。

### Q.漏杀垃圾短信怎么办？
A.首先确保这是公认的垃圾短信，然后将短信内容**完整地**写在 [Issues](https://github.com/metaphilium/PureSMS/issues) 里。

### Q.我想私人定制一些规则怎么办？
A1.如果你接受时间成本，自学正则表达式是最佳选择；

A2.如果你接受经济成本，我将在未来某个时间开始接受付费定制的委托；

A3.如果你不接受任何成本，Good joke!

## 使用许可
除非另有声明，本项目使用 署名-非商业性使用-禁止演绎 CC BY-NC-ND 协议开源。

🄲🄲 🄱🅈-🄽🄲-🄽🄳

## 捐赠
如果你认为这个项目很有用，欢迎捐赠。

|支付宝|微信|
|:---:|:--:|
|![AliPay](https://raw.githubusercontent.com/metaphilium/PureSMS/master/donation/AliPay.jpg)|![WeChatPay](https://raw.githubusercontent.com/metaphilium/PureSMS/master/donation/WeChatPay.jpg)|