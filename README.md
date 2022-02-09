# WeChatHookapi
微信hookapi
微信hook的公共api，版本3.2.1.154，下载文件后通过注入器（自己写注入）注入进微信进程，就可以通过get方式访问。
1、检查服务是否开启 url： 127.0.0.1:8090/wechat?id=0   method：GET response：Ready
2、获取二维码      url： 127.0.0.1:8090/wechat?id=1   method：GET response：二维码保存路径
3、获取好友列表    url： 127.0.0.1:8090/wechat?id=2   method：GET response：好友信息，json或字符串格式
4、发送文本消息    url： 127.0.0.1:8090/wechat?id=3&wxid=xxx&content=xxx   method：GET response：发送结果
5、发送文件消息    url： 127.0.0.1:8090/wechat?id=4&wxid=xxx&filepath=xxx   method：GET response：发送结果
6、发送图片消息    url： 127.0.0.1:8090/wechat?id=5&wxid=xxx&filepath=xxx   method：GET response：发送结果
7、获取消息记录    url： 127.0.0.1:8090/wechat?id=6   method：GET response： 消息内容
8、删除好友        url： 127.0.0.1:8090/wechat?id=7&wxid=xxx   method：GET response： 删除结果
欢迎加群讨论：467074954
点击链接加入群聊【wchook交流】：https://jq.qq.com/?_wv=1027&k=Hl3aZ0dc

