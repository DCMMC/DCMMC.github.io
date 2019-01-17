## DCMMC's Blog

Powered by `Hexo` and theme `hexo-theme-matery`

## 运行与部署

```bash
$ git clone --recursive https://github.com/DCMMC/DCMMC.github.io && cd ./DCMMC.github.io
$ npm install
$ hexo g && hexo s
```

> 需提前安装 npm(cnpm) 和 hexo

部署:

```bash
$ hexo d
```

> 可能需要生成一下 github 的 RSA key

## TODOs

* [x] `\_posts` 中的 `assets` 问题, 写一个小插件(hexo-markdown-assets-files)
* [x] 用 CI 进行自动部署
* [ ] `Docker` 化 (nginx) 本地测试并部署到 VPS (添加 https)
* [ ] 使用网站统计
