# blog

## 内容方向

> 收录我 2020 年后的所有博客，2020 年之前的尽在：[@hylerrix/university](https://github.com/hylerrix/university)。
> 博客文章若有修改，一切以本仓库内容为主而非其它第三方平台

* 开源 + 大前端

## 站点技术栈

* 主题：Hexo + Icarus(Cyberpunk 2077)
* 图床：先使用语雀文章中的图片源链接

## 本地开发

初始化项目，安装主题：

```bash
$ hexo init blog
$ git clone https://github.com/ppoffice/hexo-theme-icarus.git themes/icarus
# 根据 hexo server 后 icarus 的提示安装相关依赖
$ yarn add bulma-stylus@0.8.0 hexo-component-inferno@^0.3.0 hexo-renderer-inferno@^0.1.3 inferno@^7.3.3 inferno-create-element@^7.3.3
$ vim _config.yml # theme: icarus
```

本地常用命令清单：

```bash
# 启动
$ yarn server # -> hexo server
# 打包
$ yarn build # -> hexo generate
# 部署
$ yarn deploy # -> hexo deploy
# 清除缓存文件 db.json 和生成的文件 public
$ yarn clean # -> hexo clean
```

本地分支简介：

* master 分支：网站源码
* gh-pages 分支：打包分支

## 开源协议

代码：MIT，文章内容：CC BY SA 4.0