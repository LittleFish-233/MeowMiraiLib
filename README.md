# Meow.MiraiLib  
## 一个**还在测试**的 Mirai-C# (.net 5) 后端
## 简易使用方法(内部注释基本完整)  
```
Client c = new("ws://xxx.com.cn:1234/all?qq=123456789");
c.Connect();//链接
c.debug = false;
c.eventdebug = false;
c.OnFriendMessageRecieve += (s,e) => {.....};
c. ...... //
```
