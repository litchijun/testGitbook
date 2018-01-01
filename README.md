> GitBook 是一个基于 Node.js 的命令行工具，可使用 Github/Git 和 Markdown 来制作精美的电子书。

本文基于[GitBook使用](http://wiki.11ten.net/Node/gitbook%E4%BD%BF%E7%94%A8.html) 整理并根据实际情况改写部分，将简单介绍如何安装、编写、生成、发布一本在线图书。

### 支持格式
GitBook支持输出多种文档格式，如：
- 静态站点：GitBook默认输出该种格式，生成的静态站点可直接托管搭载Github Pages服务上；
- PDF：需要安装gitbook-pdf依赖；
- eBook：需要安装ebook-convert；
- 单HTML网页：支持将内容输出为单页的HTML，不过一般用在将电子书格式转换为PDF或eBook的中间过程；
- JSON：一般用于电子书的调试或元数据提取。

Gitbook项目地址:
- GitBook项目官网：http://www.gitbook.io
- GitBook Github地址：https://github.com/GitbookIO/gitbook
