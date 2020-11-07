# README.md 与 SUMMARY编写

## 使用语法

在Gitbook中所有文字的编写都使用`Markdown`语法。

## README.md

这个文件相对于是一本Gitbook的简介，比如我们这本书的`README.md` :

```
# Gitbook 使用入门


> GitBook 是一个基于 Node.js 的命令行工具，可使用 Github/Git 和 Markdown 来制作精美的电子书。

本书将简单介绍如何安装、编写、生成、发布一本在线图书。
```

## SUMMARY.md

这个文件相对于是一本书的目录结构。比如我们这本书的`SUMMARY.md` :

```
# Summary

* [Introduction](README.md)
* [1. 环境配置](part/README.md)
    * [1.1 GitHubDesktop 安装](part1/InstallGitDesktop.md)
    * [1.2 GitBook 安装](part1/InstallGitBook.md)
* [2. Wiki项目结构](part2/README.md)
    * [2.1 新建git仓库](architecture/CreateGitRepo.md)
    * [2.2 README.md 与 SUMMARY编写](architecture/ReadmeAndSummary.md)
    * [2.3 插件配置](architecture/BookJson.md)
    * [2.4 忽略文件](architecture/IgnoreFiles.md)

* [3. Wiki输出和发布](publish/README.md)
  * [3.1 编译和本地调试](publish/BuildAndRun.md)
  * [3.2 发布到GitPages](publish/PublishToGitPages.md)
  * [3.3 输出PDF](publish/OutputPdf.md)


```

`SUMMARY.md`基本上是列表加链接的语法。链接中可以使用目录，也可以使用。