@https://github.com/LiuJi-Jim/h5pal

先不要管技术栈多么落后和无厘头，要理解开发者的时代技术背景。

我们要做的第一步就是正常启动项目。沿着着前人走过的路摸索一番，然后再伺机超越前人。

1、下载仙剑奇侠传dos版：http://www.paopaoche.net/down.asp?id=17968 2、下载该项目：https://github.com/LiuJi-Jim/h5pal

3、项目根目录新建pal-assets文件夹，并且将下载好的仙剑奇侠传dos版资源放入。

 4、安装nodejs 和 npm（cnpm）环境

5、安装bower

$ cnpm install -g bower
6、安装npm依赖

$ cnpm install
7、安装bower依赖

$ bower install
8、先用安装好的 gulp 编译一下静态资源

$ gulp
9、修改chrome配置：

进入 chrome://flags ， 修改 Experimental JavaScript 设置为 Enabled，然后重启浏览器

10、启动【开发】服务

$ gulp dev
11、手动在chrome浏览器打开：http://localhost:8005/h5pal.html

