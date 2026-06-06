-----------此处是分割线-----------
如何使用AI+自动化工具playwright狂赚2000万美金
Playwright 是微软开源的现代浏览器自动化框架，用少量代码就能在 Chromium（Chrome/Edge）、Firefox、WebKit（Safari 引擎）里自动完成人类的浏览器操作：打开网页、点击、输入、拖拽、上传文件、截图/PDF、录制日志与回放，最常见的用途是 端到端（E2E）测试，也可做轻量爬取与流程自动化。


龙鹏-笔名言有三
龙鹏-笔名言有三
2379 人赞同了该回答
有一些给你推荐一下，参考
龙鹏-言有三：【杂谈】GitHub上有哪些好用的爬虫(从Google百度，腾讯视频抖音，豆瓣知乎到不可描述)
445 赞同 · 8 评论 文章
1、awesome-spiderD为facert的一个知乎工程师开源的，star6000+，内容如下：
这一款爬虫，里面搜集了几乎所有可以爬取的中文网址，从知乎豆瓣到知网，抖音微博到QQ，还有很多的不可描述的网站，你懂的。
2、Nyspider
地是ID为Nyloner的一个今日头条的工程师弄的，star1000+，风格与上面的项目大有不同。
可以看出，都是各类网址。这很头条，跟这位小哥哥的工作内容估计有关系。
3、awesome-python-login-model
地址：https://github.com/CriseLYJ/awesome-python-login-model
这是ID为CriseLYJ(职业不详)的用户，这个项目用于模拟各种网址登陆，也包含一些简单的爬虫，star6000+。
先从这个项目开始分析各大网站的登录方式，非常有用，可谓摸清对手再动手。
4、python-spider
地址：https://github.com/Jack-Cherish/python-spider
这是ID为Jack-Cherish的东北大学的一个学生整理的学习python爬虫的资料，star6000+，包含不少的实战项目，非常适合想学习的朋友。
其他还有一些项目，不再一一介绍。
https://github.com/jhao104/proxy_poolhttps://github.com/Ehco1996/Python-crawler
--------------------------------------此处是分割线--------------------------------------
如果你是做图像的，我再推荐两个功能强大，简单好用的图片和视频爬虫。工具亲测长期有效，省去了很多找爬虫工具的时间，早用早好。
1、Google，Baidu，Bing三大搜素引擎图片爬虫
地址：https://github.com/sczhengyabin/Image-Downloader
这个爬虫由ID为sczhengyabin的用户整理，可以按要求爬取百度、Bing、Google上的图片，我已经用了几年了，提供了非常人性化的GUI方便操作，使用方法如下：
使用python image_downloader_gui.py调用GUI界面，配置好参数(关键词，路径，爬取数目等)，关键词可以直接在这里输入也可以选择从txt文件中选择。
可以配置需要爬取的样本数目，这里一次爬了2000张，妥妥的3分钟搞定。
这个爬虫足够满足小型项目初始数据集的积累(爬几千张高质量图片妥妥的)，结果命名也非常整齐规范，最大的优势就是稳定啊，不会三天两天不能用了。
2、各大视频网站爬虫
地址：https://github.com/iawia002/annie
由ID为iawia002的用户整理，Annie是一款以go语言编码的视频下载工具，使用便捷并支持youtube，腾讯视频，抖音等多个网站视频和图像的下载，收录站点如下，可以说是该有的都有的：
虽然这个项目可以下载图片，但是我们还是来用它下载视频吧，使用方法很简单：
annie ［可选参数］http://…  (视频网址)
视频会下载到当前目录，至于那些可选参数，赶紧去摸索吧。
编辑于2019-04-03 19:40
赞同 2379
52 条评论
1.2 万
1033
分享
收起
白露未晞me
白露未晞me
有的人喜欢瞻仰皇陵，而有的人喜欢凭吊荒冢。
1968 人赞同了该回答


可以毛遂自荐么，虽然没有楼上推荐的那些爬虫项目那么优秀，完全是业余时候打发时间的小作品，不过供新手学习使用还是绰绰有余的。（收藏是点赞的两倍，小伙伴们随手点个赞同呀~）
1. 模拟登录各大网站——DecryptLogin
项目地址：
https://github.com/CharlesPikachu/DecryptLogin
项目中文文档：
https://httpsgithubcomcharlespikachudecryptlogin.readthedocs.io/zh/latest/
这是一个利用requests来模拟登录各大网站的开源包，目前支持模拟登录以下平台：
利用pip命令安装该包后：
pip install DecryptLogin
只需要简单的几行代码就可以实现支持列表中的任意一个网站的模拟登录操作，例如模拟登录百度网盘：
from DecryptLogin import login
lg = login.Login()
infos_return, session = lg.baidupan(username, password, 'pc')
其中infos_return是一个字典对象，里面有用户登录后的一些基本信息，session是已经登录了目标网站的会话(requests.Session对象)。
那么模拟登录网站后有什么用呢？别担心，该开源项目会不定期添加一些需要模拟登录的爬虫小案例，帮助你更好地学习爬虫：
每个案例都对应了我微信公众号里的一篇讲解文章(虽然文章可能不太走心，写的比较粗略，微信公众号名是“Charles的皮卡丘”，感兴趣的可以搜索关注一下)。例如微博监控：

Python监控小姐姐/小哥哥微博，了解一下？
"https://mp.weixin.qq.com/s/uOT1cGqXkOq-Hdc8TVnglg" (https://mp.weixin.qq.com/s/uOT1cGqXkOq-Hdc8TVnglg)
网易云音乐自动签到脚本：
整个小例子呗，实现一下网易云音乐自动签到
"https://mp.weixin.qq.com/s/8d7smUSzW2ds1ypZq-yeFw" (https://mp.weixin.qq.com/s/8d7smUSzW2ds1ypZq-yeFw)
大吼一声发条微博：
随便玩玩，要不要试试大吼一声来发条微博
"https://mp.weixin.qq.com/s/_aIY-iVj3xetfHQyMxflkg" (https://mp.weixin.qq.com/s/_aIY-iVj3xetfHQyMxflkg)
爬取目标用户的所有微博数据：
听说想了解一个人要从爬取她(他)的所有微博开始呢~
"https://mp.weixin.qq.com/s/-3BDTZAE1x7nfCLNq2mFBw" (https://mp.weixin.qq.com/s/-3BDTZAE1x7nfCLNq2mFBw)
生成QQ个人专属报告：
模拟登录系列 | 生成QQ个人专属报告
"https://mp.weixin.qq.com/s/dsVtEp_TFeyeSAAUn1zFEw" (https://mp.weixin.qq.com/s/dsVtEp_TFeyeSAAUn1zFEw)
下载B站指定UP主的所有视频：
模拟登录系列 | 下载B站指定UP主的所有视频
"https://mp.weixin.qq.com/s/GaVW4_nbAaO0QvphI7QgnA" (https://mp.weixin.qq.com/s/GaVW4_nbAaO0QvphI7QgnA)
网易云个人歌单下载器：
模拟登录系列 | 来写个网易云个人歌单下载器？
"https://mp.weixin.qq.com/s/_82U7luG6jmV-xb8-Qkiew" (https://mp.weixin.qq.com/s/_82U7luG6jmV-xb8-Qkiew)
等等。
或许有人懒得点进去，放几个视频吧(都是公众号+Github里的案例)：
网易云个人歌单下载器
下载B站指定UP主的所有视频
2.音乐下载器(2020.04.01完成Flag)
项目地址：
https://github.com/CharlesPikachu/musicdl
项目文档：
https://musicdl.readthedocs.io/zh/latest/index.html
目标支持的平台情况：
运行效果是这样子的：
音乐下载器
3.视频下载器
项目地址：
https://github.com/CharlesPikachu/Video-Downloader
也很久没更新了，大概长这样：
写的时间有点久了，我自己都可能看不懂自己写的代码是啥玩意了。and最近没有重构计划。有需要的可以自己看看改改。
4.其他
因为爬虫项目维护起来比较麻烦，所以我一般懒得传到Github上，有兴趣的小伙伴可以关注一下我的微信公众号"Charles的皮卡丘"，里面会不定期分享一些爬虫项目(因为现在不太喜欢写爬虫了，后面比较偏向于发自己的主业CV，或者说AI相关的内容)。然后在底部菜单栏的历史文章里可以看到我发过的所有爬虫代码，需要的自取就ok了。
对了，这里面好像也有几个零星的爬虫相关的项目：
https://github.com/CharlesPikachu/Tools
编辑于2020-10-16 22:46
赞同 1968
47 条评论
6426
711
分享
收起
查看剩余 47 条回答
