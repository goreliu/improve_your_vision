### 《没有改善不了的视力》简体中文版

#### 阅读

[在线阅读](https://goreliu.github.io/improve_your_vision/)

[下载地址](https://github.com/goreliu/improve_your_vision/releases)

#### 构建

需要安装 [mdbook](https://github.com/rust-lang/mdBook) 和 [mdbook-epub](https://github.com/Michael-F-Bryan/mdbook-epub)。

```
mdbook build
```

pdf 文件是用 [freepdfconvert](https://www.freepdfconvert.com/epub-to-pdf) 转换 epub 文件获得的。

#### 已知问题

1. epub 文件在微信读书（手机端）等软件中表格不显示。
2. 在线版无法搜索中文（mdbook 不支持）。
