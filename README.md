# 青龙薅羊毛-微信阅读
青龙面板 薅羊毛 微信阅读 多用户高收益

## 拉库/订阅任务：
```Shell
ql repo https://ghproxy.com/https://github.com/365360171/qlwxyd.git`
```
定时规则 
```Shell
0 0 0 * * 1
```
拉库后可以看到新增的 <微信阅读> 脚本  <br>
操作编辑 定时规则为1小时一次 10 * * * *  <br>

## 抓包
在微信中打开 https://zl1222211708-1314804847.cos.ap-nanjing.myqcloud.com/index.html?upuid=10746751
打开后自动转跳阅读文章 空白页关闭后 重新打开 打开文章停5秒 手动返回上一页

青龙需要抓包m.*.shop域名下cookie,
环境变量-新建变量 名称: wxyd  值:(你抓取的cookie)
多个账户回车换行隔开

安卓可以用 小黄鸟 HttpCanary https://www.bilibili.com/video/av292860564/
PC可以用 smartsniff Wireshark 等 抓取cookie

每天会验证2次左右，碰到会plus推送提醒
手动在微信里打开上面的链接看两篇文章 
出现 阅读成功,金币增加 的提示即可

返回定时任务 运行 微信阅读 查看日记 运行是否正常

每篇文章120金币 每3000金自动提现0.3元 
每小时30篇 每天6轮 180篇文章共21600金币=2.16
