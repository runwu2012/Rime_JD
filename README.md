﻿<h1 align="center">星空键道6</h1>

>作者：**吅吅大山** [**键道官网**][904] [加入官方群:320053116][903]
---
#### 目录结构说明：

| 路径 | 作用 |
| :-------------|:-------------: |
| /Tools | 工具目录 |
| /Tools/BackDict | 备份上次码表 |
| /Tools/Extended | 扩展码表 |
| /Tools/SystemTools | 各系统配置文件工具 |
| /Tools/TermsTools | 词组排序工具 |
| /rime | 主码表文件夹[主码表] |
| README.md | readme.md文件 |

---
#### 使用说明：
* 获取本项目内容：
 使用Git程序（可滚动更新）
 * Windows系统Git：[官网][905]|[微云][912]
> 若速度不佳建议使用微云下载
 * Linux/Mac系统Git：[自行安装]
 * Android系统Git：[下载(Pocket Git)][910]

* IOS操作系统： iRime：指导教程 [iRime-Wiki][913]

#### Git简述：
##### 首次安装：
1. 需要安装Git后，将克隆项目到本地（打开git bash中输入，下面一样的）
`git clone https://gitee.com/nshu/Rime_JD`
2. 切换到项目文件夹
`cd Rime_JD`
3. 在文件管理器打开当前目录（`pwd`可以查看目录位置），进入Rime_JD/Tools/SystemTools/对应系统的工具目录执行复制码表工具（1install），再重新部署即可更新完成

##### 获取更新：
1. 获取上游地址的master分支
`git pull`
2. 获取后，执行复制码表工具（2update），再重新部署即可更新完成

#### 最后：
> 重新部署，并尝试输入文字。安装完成。

#### 

#### 扩展说明：
1. 扩展控制文件为 xkjd6.extended.dict.yaml / xkjd6dz.extended.dict.yaml
2. 文件中有详细说明。

#### 分支说明：
> master为定期更新稳定内容。

---
##### 若你想要发起发起PR为本项目做出贡献：
创建远程仓库，指向 PR 提交者的仓库
1. 指定上游地址
`git remote add upstream https://gitee.com/nshu/Rime_JD.git`
2. 从该远程仓库拉取代码
`git fetch upstream`
**如果上游更新内容含有 缩减仓库历史，请在push 代码前 pull rebasel 详见：缩减仓库说明**
3. 将该仓库的上游分支合并到自己分支
`git merge upstream`
4. 推送到自己的仓库
`git push origin master`

##### 提交commit规范：
* 码表分类：[据议表调整： x个] 外加调整：词组 编码... x个
* 工具类：系统名：工具名 文件名 纠错/添加/删除

>详见：**[git-简明指南][909] [码云PR教程][907] [博客PR教程][906] [缩减仓库说明][908]**

---
### 星空系列其他Rime方案：

| [Morler][214] | [歌颂][216] |
| ------------- | ---------- |
| [星空两笔][213] | [星空一笔 OR 星空一道][217] |
---
### 键道6第三方维护版本：

| RIME | RIME正體字碼表 | 小小 | 
| ------------- |:-------------:|:-------------:|
| [Qshu][204] | [岳飞丫飞][207] | [thxnder][206] |
| [主页][204] | [主页][207] | [主页][205] |
---
### 键道可以运行在以下平台中：

| Windows | Linux | iOS | Android
| ------------- |:-------------:|:-------------:|:-----:
| [Windows(weasel)][101] | [Linux(ibus-rime)][104] | [Mac(squirrel)][102] | [Android(trime)][105] 
| [Windows(小小)][203] | [Linux(fcitx-rime)][103] | [IOS(iRime)][106] | [Android(小小)][203]
| [Windows(多多)][108] | [Linux(小小)][203] | [IOS(落格)][107]

> 键道的跨平台使用离不开以上优秀的输入平台

[998]: https://gitee.com/thxnder/xxjd/tree/master/release "新版本小小键道"
[999]: https://gitee.com/nshu/Rime_JD "新版本RIME键道"

[101]: https://github.com/rime/weasel "小狼毫－Rime 輸入法 for Windows"
[102]: https://github.com/rime/squirrel "鼠鬚管－Rime 輸入法 for Mac OS X"
[103]: https://github.com/fcitx/fcitx-rime "fcitx-rime for Linux"
[104]: https://github.com/rime/ibus-rime "ibus-rime for Linux"
[105]: https://github.com/osfans/trime "同文－TRime 輸入法 for Android"
[106]: https://github.com/jimmy54/iRime "iRime 輸入法 for IOS"
[107]: https://im.logcg.com/ "落格输入法 for IOS"
[108]: https://chinput.com/portal.php "多多 for Windows"

[200]: https://github.com/rime "RIME作者地址"
[201]: http://rime.im "rime主页"
[202]: https://github.com/osfans "TRIME作者页面"
[203]: https://github.com/dgod/yong "小小主页"
[204]: https://gitee.com/nshu/Rime_JD "Rime键道主页"
[205]: http://thxnder.gitee.io/xxjd "小小键道主页"
[206]: https://gitee.com/thxnder "「小小键道」 维护者"
[207]: https://gitee.com/lyserenity/xkjd6 "正体字码表"
[208]: https://gitee.com/nshu/Rime_JD/releases "发行页"
[209]: https://gitee.com/nshu/Rime_JD/repository/archive/master.zip "Download"
[210]: https://gitee.com/nshu/Rime_JD/tree/master/Tools/SystemTools "/Tools/SystemTools"
[211]: https://gitee.com/nshu/Rime_JD/tree/master/rime "/rime"
[212]: https://gitee.com/nshu/Rime_JD/tree/master/SystemTools/Android "Android"
[213]: https://gitee.com/morler/rime_xklb "两笔地址"
[214]: https://gitee.com/morler "Morler"
[215]: https://github.com/dzyht/rime_xkyb "一笔地址"
[216]: https://gitee.com/dzyht "歌颂"
[217]: https://gitee.com/dzyht/rime_xkybd "一笔一道地址"

[901]: https://gitee.com/thxnder/xxjd/blob/master/doc/xkjd3.md "星空键道 简明教程"
[902]: http://daniushuangpin.ys168.com "吅吅大山的的网盘"
[903]: https://jq.qq.com/?_wv=1027&k=5sTEYIQ "吅吅大山的QQ群"
[904]: http://xkjd.coding.me "键道官网"
[905]: https://git-scm.com/ "Git"
[906]: http://www.ruanyifeng.com/blog/2017/07/pull_request.html "阮一峰PR教程"
[907]: http://git.mydoc.io/?t=180700 "码云PR教程"
[908]: http://git.mydoc.io/?t=83153 "码云缩减仓库说明"
[909]: http://rogerdudler.github.io/git-guide/index.zh.html "git - 简明指南"
[910]: http://sj.qq.com/myapp/detail.htm?apkName=com.aor.pocketgit "Pocket Git（口袋Git）"
[911]: https://www.jianguoyun.com/p/DV2MIxsQ67buBhjNl1w "Git坚果云地址"
[912]: https://share.weiyun.com/5xfC9Qk "Git微云地址"
[913]: http://wiki.5koon.com/doku.php?id=simplified "iRime说明地址"
