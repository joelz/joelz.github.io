# Gitbook-cli安装

为了能在系统任意文件夹下使用gitbook命令，需要安装gitbook-cli。gitbook-cli是一个类似nrm的东西，可以自由切换不同版本的gitbook。


Gitbook-cli是使用NPM来进行安装的，可以在命令行中输入下面的命令进行安装（使用管理员身份运行）：

```bash
$ npm install gitbook-cli -g
```

接下来先看一下有哪些版本的gitbook可供安装：

```bash
$ gitbook ls-remote
```


安装特定版本的gitbook：

```bash
$ gitbook fetch 3.2.0
```


安装完成之后，你可以使用下面的命令来检验是否安装成功

```bash
$ gitbook ls
3.2.0
```

如果你看到了上面类似的版本信息，则表示你已经安装成功了。

