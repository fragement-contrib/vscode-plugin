# [VSCode Plugin](https://github.com/fragement-contrib/vscode-plugin)
VSCode 插件开发

> 如果涉及语法和文件，我们使用的是 ```.zxl``` 文件和html作为演示语法。

## 开发调试

用鼠标点击 ```startUp.js```  文件，然后按键盘上的f5，点击弹出窗口中的```VS Code Extension Development```。

## 打包使用

我们当前只提供本地安装，没有发布到应用市场。

```bash
npm i @vscode/vsce -g
```

安装好打包工具后，直接运行：

```bash
vsce package
```

生成好的vsix文件从扩展的右上角选择``` Install from VSIX ```安装即可！

## 版权

MIT License

Copyright (c) [zxl20070701](https://zxl20070701.github.io/notebook/home.html) 走一步，再走一步