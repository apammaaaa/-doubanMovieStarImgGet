简介
    抓取并下载豆瓣电影明星的图片
说明
    请使用Chrome浏览器
    请使用对应版本的Chrome驱动
    请把Chrome驱动解压后设置为环境变量
    Chrome下载地址:https://www.google.cn/chrome/
    Chrome驱动下载地址:http://chromedriver.storage.googleapis.com/index.html

    pip install -r requirements.txt安装对用的包

    first_link为豆瓣电影明星图片首页地址
    请输入正确的地址，例如:first_link = "https://movie.douban.com/celebrity/1313742/photos/"

    mode为下载模式
    正常模式：mode = "1"
    查漏模式: mode = "3"
    正常模式会自动按顺序下载图片，如果中途停止，下次启动会接着最后一张图片下载。查漏模式会检查照片中遗漏的图片并下载

    python doubanMovieStarImg.py运行

