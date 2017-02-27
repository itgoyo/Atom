# Atom
- 完成Atom文本编辑器的安装

    [1] 下载安装[Atom](https://atom.io/)

    [2] 下载[Node.js](https://nodejs.org/en/)

    [2] 配置环境变量
    打开安装Atom文件夹 复制安装路径

    ![](http://p1.bqimg.com/567571/5d065a1374244fed.png)

    在环境变量-系统变量-path中新增

    C:\Users\admin\AppData\Local\atom\app-1.14.3\resources\app\apm\bin

    C:\Users\admin\AppData\Local\atom\bin

    D:\Program Files\nodejs

    如下图所示：

    ![](http://i1.piimg.com/567571/1fafe02f452a8fe3.png)

- 添加git-plus\activate-power-mode插件

由于使用lantern翻墙还有修改了host文件都不能成功的install 插件，所以这里我安装插件的方式是采用了离线的方式

[Atom插件合集](https://atom.io/packages)

从里边下载好了插件之后解压缩复制到C:\Users\admin\.atom\packages

然后使用命令行（cmd）

1.在搜索里边键入powershell

![](http://i1.piimg.com/567571/7b6fe1b457aa7621.png)

2.

cd 到下载的插件包文件夹里

然后键入apm install

当出现了done的字样之后

再键入apm install xxx(插件名)

出现done之后代码成功安装插件

![](http://i1.piimg.com/567571/148cad92b0340589.jpg)

![](http://i1.piimg.com/567571/362a78b264be5e71.gif)
