# Tale Blog

![Tale](https://ooo.0o0.ooo/2017/02/27/58b43450c9182.png)


## 特性

+ 设计简洁，界面美观
+ Markdown 文章发布
+ 自定义文章链接
+ 支持多主题
+ 支持插件扩展
+ 支持 Emoji 表情
+ 支持网易云音乐播放
+ 支持附件和数据库备份
+ 部署简单，不依赖 Tomcat
+ 无需数据库，内嵌 Sqlite

## 界面预览

![001](https://raw.githubusercontent.com/tfssweb/tfssweb.github.io/master/source/images/blog/001.png)
![002](https://raw.githubusercontent.com/tfssweb/tfssweb.github.io/master/source/images/blog/002.png)
![003](https://raw.githubusercontent.com/tfssweb/tfssweb.github.io/master/source/images/blog/003.png)
![004](https://raw.githubusercontent.com/tfssweb/tfssweb.github.io/master/source/images/blog/004.png)
![005](https://raw.githubusercontent.com/tfssweb/tfssweb.github.io/master/source/images/blog/005.png)
![006](https://raw.githubusercontent.com/tfssweb/tfssweb.github.io/master/source/images/blog/006.png)
![007](https://raw.githubusercontent.com/tfssweb/tfssweb.github.io/master/source/images/blog/007.png)

## 如何使用
直接`Fork`到自己的GitHub使用（不要吝啬你的`Star`哦！）；

或者

将代码克隆到本地，执行：
```
git clone https://github.com/tfssweb/tale.git
``` 
然后进入到`docker`目录，依次执行：
```
cp -r ./tfss_volumes/ /opt/

docker-compose up -d
```
（注意以此方式部署你得需要docker环境）
即可！

有开发/部署问题的可以进QQ群（247158514）,之后的教程录像也会上传到群文件中！

## 开源协议

本代码以[biezhi](https://github.com/otale/tale)代码为基础作为二次开发，现主要关注于博客的Docker部署、前端界面优化以及插件的开发，所以有志同道合的朋友可以一起探讨！

QQ群（247158514）

[MIT](LICENSE)

## 感谢

	如果说我比别人看得更远些,那是因为我站在了巨人的肩上.
											——牛顿 
再次感谢为开源而努力的朋友！！

+ [biezhi](https://github.com/otale/tale)







