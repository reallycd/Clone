# all
可命令安装，不必fork，看以下的示例项目。https://github.com/reallycd/aria2
git clone --depth=1 https://github.com/reallycd/scrapy.git
https://github.com/scrapy/scrapy
https://github.com/iawia002/lux#download-a-video
https://github.com/ytdl-org/youtube-dl

已执行。
git clone https://github.com/xiaopeng163/python-dev-container-demo.git container相关/docker
git clone https://github.com/xiaopeng163/terraform-dev-container.git container相关/配置container
git clone https://github.com/xiaopeng163/nginx-flask-mysql.git container相关/Docker_in_Docker
git clone https://github.com/reallycd/playwright-mcp-generate.git Unsuitable/Playwright_AI生成脚本
git clone https://github.com/SimoneAvogadro/android-reverse-engineering-skill.git Unsuitable/安卓逆向AI
git clone https://github.com/Kr1s77/awesome-python-login-model.git Mark/login
git clone https://github.com/Ehco1996/Python-crawler.git Mark/Python-crawler
git clone https://github.com/Jack-Cherish/python-spider.git Mark/python-spider
git clone https://github.com/oh-my-docker/net-box.git Mark/net-box
git clone https://github.com/GrowingGit/GitHub-Chinese-Top-Charts.git Mark/GitHub-Chinese-Top-Charts
git clone https://github.com/codecrafters-io/build-your-own-x.git Mark/build-your-own
git clone https://github.com/CharlesPikachu/Video-Downloader Mark/Video-Downloader
git clone https://github.com/CharlesPikachu/DecryptLogin Mark/DecryptLogin
git clone https://github.com/CharlesPikachu/Tools Mark/Tools


运行以下命令，推送到远程仓。
git add .
git commit -m "注释" 

git push origin master。不用他，可直接点击。
git commit -am "注释" //跳过git add命令，实测不行

GitHub 上文件上传后显示为带有白色箭头图标且无法正常打开，这通常是因为这些项目被标记为了子模块或者是由于存在隐藏的.git文件夹所引起的。要在提交前删除该子文件夹内的.git文件夹。
find . -type d -name ".git"

find ./* -type d -name ".git" -exec rm -rf {} +
