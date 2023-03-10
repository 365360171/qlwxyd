# 青龙薅羊毛-微信阅读
青龙面板 薅羊毛 微信阅读 多用户高收益

## 拉库/订阅任务：
```Shell
ql repo https://ghproxy.com/https://github.com/365360171/qlwxyd.git
```
定时规则 
```Shell
0 0 0 * * 1
```
拉库后可以看到新增的 <微信阅读> 脚本

脚本定时规则可设置为1小时一次 10 * * * *

## 抓包
青龙需要抓包m.*.shop域名下cookie

安卓可以用 小黄鸟 HttpCanary 教程：https://www.bilibili.com/video/av292860564/

PC可以用 smartsniff Wireshark 等抓取cookie

微信扫下面二维码，打开后自动转跳阅读文章 空白页关闭后 重新打开 打开文章停5秒 手动返回上一页

<img src="https://github.com/365360171/qlwxyd/blob/main/1.png" alt="Clash" width="200">

青龙面板新增环境变量：变量名称: wxyd  值:(你抓取的cookie)

多个账户回车换行隔开

## PS
每天会验证2次左右，碰到会推送提醒

过验证方法：手动在微信里打开上面的链接看两篇文章。出现：阅读成功，金币增加 的提示即可

返回定时任务 运行脚本 查看日志 运行是否正常

每篇文章120金币 每3000金自动提现0.3元 

每小时30篇 每天6轮 180篇文章共21600金币=2.16
