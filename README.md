# GKD 规则整合去重报告

## 概览

| 指标 | 数值 |
|------|------|
| 规则源数量 | 5 |
| 总应用数（去重后） | 965 |
| 总规则组数（去重后） | 5021 |
| 总规则数（去重后） | 69175 |
| 全局规则组 | 18 |
| 分类数 | 12 |
| 输出文件大小 | 4,357,282 bytes |

## 规则源对比

| 规则源 | 应用数 | 规则组数 | 规则数 | 独有应用数 |
|--------|--------|----------|--------|------------|
| AIsouler | 886 | 2074 | 4825 | 223 |
| Adpro-Team | 678 | 1432 | 33756 | 19 |
| ganlinte | 607 | 1111 | 27804 | 16 |
| MengNianxiaoyao | 285 | 394 | 2679 | 3 |
| aoguai | 72 | 10 | 111 | 0 |

## 多源覆盖分布

| 覆盖源数 | 应用数 |
|----------|--------|
| 1 | 261 |
| 2 | 128 |
| 3 | 353 |
| 4 | 163 |
| 5 | 60 |

## 各规则源独有应用（仅被单一源覆盖）

### AIsouler（223 个独有应用）

- `ai.ling.luka.app` (Luka阅读养成)
- `anddea.youtube` (YouTube RVX)
- `android` (Android 系统)
- `app.revanced.android.apps.youtube.music` (YouTube Music)
- `app.revanced.android.youtube` (YouTube)
- `bitcoin.minning.com` (Bitcoin Mining)
- `by.green.tuber` (YouTube)
- `camera.timestamp.mark.watermark` (今日水印相机)
- `cn.com.bmac.nfc` (北京一卡通)
- `cn.com.hzb.mobilebank.per` (杭州银行)
- `cn.com.thit.wxmetro` (码上行)
- `cn.com.yunma.school.app` (易校园)
- `cn.dxy.idxyer` (丁香园)
- `cn.edu.buaa.wxwork` (智慧北航)
- `cn.runningquotient.rq` (RQrun)
- `cn.wenyu.bodian` (波点音乐)
- `cn.wps.moffice_i18n` (WPS Office Lite)
- `coding.yu.ccompiler.new` (C语言编译器)
- `com.DL.war.planes.inc.online.bomber.fighter.aircraft.ww2` (Warplane Inc. Online)
- `com.MobileTicket` (铁路12306)
- `com.Qunar` (去哪儿旅行)
- `com.akspeed.jiasuqi.gameboost` (AK加速器)
- `com.alcidae.smarthome` (海雀)
- `com.allhistory.dls.marble` (全知识)
- `com.android.calendar` (小米日历)
- `com.android.chrome` (Chrome)
- `com.android.email` (电子邮件)
- `com.android.incallui` (电话)
- `com.android.permissioncontroller` (权限控制器)
- `com.android.systemui` (系统界面)
- ... 等共 223 个

### Adpro-Team（19 个独有应用）

- `cn.lezhi.speedtest` (网速管家)
- `com.app.lantt.xs` (蓝豚豚)
- `com.baidu.input_huawei` (百度输入法华为定制版)
- `com.cib.xyk` (兴业生活)
- `com.csmbcx.candada` (餐大大)
- `com.github.catvod.app` (猫影视)
- `com.hihanhan.one.rt45` (一个)
- `com.huabenapp` (话本小说)
- `com.jihuanshe` (集换社)
- `com.kmsoft.fvplayer` (快码万能播放器)
- `com.leiting.lt65207` (山东人在山西)
- `com.netease.snailread` (网易蜗牛读书)
- `com.pingan.paces.ccms` (平安口袋银行)
- `com.sec.android.app.camera` (相机)
- `com.taobao.movie.android` (淘票票)
- `com.tencent.qqlite` (QQ极速版)
- `com.uanmi.miaojiaccount` (熊猫记账)
- `com.wls.weex` (我联智慧用电)
- `com.xyhj.hanju` (韩剧TV)

### ganlinte（16 个独有应用）

- `cn.com.cmbc.newmbank` (民生银行)
- `com.adguard.android` (AdGuard)
- `com.baidu.haokan` (好看视频)
- `com.bjsk.intelligent` (WiFi智能钥匙)
- `com.cqcsy.ifvod` (爱壹帆)
- `com.excean.splay` (OurPlay加速器)
- `com.henzanapp.miaomiaozhe` (喵喵折)
- `com.hxak.liangongbao` (链工宝)
- `com.mm.android.lchg` (乐橙含光)
- `com.onecard.hainan` (海南一卡通)
- `com.ponyemu.main` (小马模拟器)
- `com.sfacg` (菠萝包轻小说)
- `com.tencent.weishi` (微视)
- `com.tvbc.maiduidui` (埋堆堆)
- `com.weaver.emobile7` (EMobile7)
- `com.yek.android.kfc.activitys` (肯德基)

### MengNianxiaoyao（3 个独有应用）

- `com.huawei.genexcloud.speedtest` (花瓣测速)
- `com.mimikko.mimikkoui` (兽耳助手)
- `com.srcb.pmbank` (上海农商银行)

### aoguai（0 个独有应用）


## 被最多源覆盖的应用 TOP 20

| 应用包名 | 应用名称 | 覆盖源数 | 来源 |
|----------|----------|----------|------|
| `cn.com.spdb.mobilebank.per` | 浦发银行 | 5 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `cn.wps.moffice_eng` | WPS | 5 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.ai.obc.cbn.app` | 中国广电 | 5 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.alibaba.android.rimet` | 钉钉 | 5 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.alicloud.databox` | 阿里云盘 | 5 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.android.thememanager` | 主题壁纸 | 5 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.autonavi.minimap` | 高德地图 | 5 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.baidu.BaiduMap` | 百度地图 | 5 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.baidu.netdisk` | 百度网盘 | 5 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.baidu.tieba` | 百度贴吧 | 5 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.bankcomm.Bankcomm` | 交通银行 | 5 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.cainiao.wireless` | 菜鸟 | 5 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.chinamworld.main` | 中国建设银行 | 5 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.coolapk.market` | 酷安 | 5 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.ct.client` | 中国电信 | 5 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.duokan.phone.remotecontroller` | 万能遥控 | 5 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.duowan.kiwi` | 虎牙直播 | 5 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.eg.android.AlipayGphone` | 支付宝 | 5 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.google.android.documentsui` | Android 系统文件选择器 | 5 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.google.android.gm` | Gmail | 5 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |

## 规则组最多的应用 TOP 20

| 应用包名 | 应用名称 | 规则组数 | 规则数 | 来源 |
|----------|----------|----------|--------|------|
| `com.tencent.mm` | 微信 | 81 | 451 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.tencent.mobileqq` | QQ | 77 | 724 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.ss.android.ugc.aweme` | 抖音 | 59 | 850 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao |
| `com.eg.android.AlipayGphone` | 支付宝 | 54 | 297 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.sina.weibo` | 微博 | 52 | 1104 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao |
| `tv.danmaku.bili` | 哔哩哔哩 | 52 | 523 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.xunmeng.pinduoduo` | 拼多多 | 48 | 249 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.taobao.taobao` | 淘宝 | 47 | 895 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.baidu.tieba` | 百度贴吧 | 42 | 191 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.dragon.read` | 番茄免费小说 | 39 | 429 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao |
| `com.ximalaya.ting.android` | 喜马拉雅 | 36 | 639 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao |
| `com.zhihu.android` | 知乎 | 36 | 254 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.ss.android.article.news` | 今日头条 | 35 | 108 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.jingdong.app.mall` | 京东 | 34 | 417 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.netease.cloudmusic` | 网易云音乐 | 34 | 219 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `me.ele` | 饿了么 | 33 | 461 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |
| `com.qidian.QDReader` | 起点读书 | 31 | 529 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao |
| `com.sankuai.meituan` | 美团 | 29 | 214 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao |
| `com.tencent.qqlive` | 腾讯视频 | 27 | 283 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao |
| `com.autonavi.minimap` | 高德地图 | 26 | 903 | AIsouler, Adpro-Team, ganlinte, MengNianxiaoyao, aoguai |

---
*由 WorkBuddy 自动生成*
