# 插件配置

Gitbook自带了强大的插件库，可以很轻松地实现搜索/分享/高亮等功能，更详细的教程可以看以下链接。

[GitBook常用的插件]: https://segmentfault.com/a/1190000019806829



在这里我们可以直接先用最简单的配置让我们的项目先跑起来。

在SUMMARY.md同级的目录下新建book.json文件，把以下代码复制进去保存，然后命令行输入`gitbook install`完成插件安装。

```
{
    "title": "Lucian's Library",
    "author": "LuLuLucian",
    "description": "select * from learn",
    "language": "zh-hans",
    "gitbook": "3.2.3",
    "styles": {
        "website": "./styles/website.css"
    },
    "links": {
        "sidebar": {
            "我的github": "https://github.com/LuLuLucian"
        }
    },
    "plugins": [
        "splitter",
        "anchors",
		"search",
        "anchor-navigation-ex"
    ],
    "pluginsConfig": {
        "anchor-navigation-ex": {
            "showLevel": false
        }
    }
}
```

