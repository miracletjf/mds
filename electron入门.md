# electron 入门笔记

![electron](https://i.loli.net/2019/04/29/5cc69c8faa021.png)

## 简介

`Electron` 是一个可以使用纯 `JavaScript`、`HTML`和`CSS`来构建跨平台原生桌面应用的框架。借助`Electron`，我们可以用纯`JavaScript`来调用丰富的原生 `APIS`。
`Electron`用`Web`页面作为它的`GUI`,所以你能把它看作成一个被`JavaScript`控制的，简介版的`Chromium`浏览器。

## 安装 electron 应用

安装`electron`之前，需要先安装 `Node.js`（本人使用`windows`系统，所以直接从`Nodejs`官网上下载安装包，安装即可）。
`Nodejs`自带包管理工具`npm`。但本人与`npm`五行相克，所以使用`yarn`来安装，`yarn`和`npm`功能相似，不过对于安装工具包来说`yarn`更稳定一点。

使用命令行全局安装`electron`:

```
yarn global add electron
```

## 进程

`Electron`的进程