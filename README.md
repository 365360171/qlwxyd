# 青龙薅羊毛-微信阅读
青龙面板 薅羊毛 微信阅读 多用户高收益

## 特别声明:

* 本仓库发布的Script项目中涉及的任何解锁和解密分析脚本，仅用于测试和学习研究，禁止用于商业用途，不能保证其合法性，准确性，完整性和有效性，请根据情况自行判断.

* 本项目内所有资源文件，禁止任何公众号、自媒体进行任何形式的转载、发布。

* atyvcn 对任何脚本问题概不负责，包括但不限于由任何脚本错误导致的任何损失或损害.

* 间接使用脚本的任何用户，包括但不限于建立VPS或在某些行为违反国家/地区法律或相关法规的情况下进行传播, atyvcn 对于由此引起的任何隐私泄漏或其他后果概不负责.

* 请勿将Script项目的任何内容用于商业或非法目的，否则后果自负.

* 如果任何单位或个人认为该项目的脚本可能涉嫌侵犯其权利，则应及时通知并提供身份证明，所有权证明，我们将在收到认证文件后删除相关脚本.

* 任何以任何方式查看此项目的人或直接或间接使用该Script项目的任何脚本的使用者都应仔细阅读此声明。atyvcn 保留随时更改或补充此免责声明的权利。一旦使用并复制了任何相关脚本或Script项目的规则，则视为您已接受此免责声明.

**您必须在下载后的24小时内从计算机或手机中完全删除以上内容.**  </br>
> ***您使用或者复制了本仓库且本人制作的任何脚本，则视为`已接受`此声明，请仔细阅读***

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

## 抓包：
青龙需要抓包m.*.shop域名下cookie

安卓可以用 小黄鸟 HttpCanary 教程：https://www.bilibili.com/video/av292860564/

PC可以用 smartsniff Wireshark 等抓取cookie

微信扫下面二维码，打开后自动转跳阅读文章 空白页关闭后 重新打开 打开文章停5秒 手动返回上一页

<img src="https://github.com/365360171/qlwxyd/blob/main/2.png" alt="Clash" width="200">

青龙面板新增环境变量：变量名称: wxyd  值:(你抓取的cookie)

多个账户回车换行隔开

## 注意事项：
每天会验证2次左右，碰到会推送提醒

过验证方法：手动在微信里打开上面的链接看两篇文章。出现：阅读成功，金币增加 的提示即可

返回定时任务 运行脚本 查看日志 运行是否正常

每篇文章120金币 每3000金自动提现0.3元 

每小时30篇 每天6轮 180篇文章共21600金币=2.16
