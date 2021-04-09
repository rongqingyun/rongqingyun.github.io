本博客使用[Anatole](https://github.com/hi-caicai/farbox-theme-Anatole)主题配置

系统&环境：macOS v10.15.7; node v12.16.1; npm v6.13.4; git v2.24.3


注意：若没有安装hexo请先全局安装hexo
```
npm install -g hexo-cli
```

git clone或 download .zip并且解压后，打开下载目录在控制台执行以下命令：


```
npm install
hexo server
```

如果上面的命令都没报错的话，在浏览器中输入 http://localhost:4000 回车就可以预览效果了。

若提示4000端口被占用，可关闭占用的端口（百度解决端口占用）
或开启另一端口号运行任务:
```
hexo server -p 5000
```

另外:
由于未实现一键部署功能，在提交github时应注意的流程：先clean(清除缓存文件)，再generate(生成静态文件)，再deploy(部署网站)
```
hexo clean
hexo generate 
hexo deploy
```

