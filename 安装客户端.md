# Git 安装客户端

Git 是目前世界上使用最广泛的现代软件版本管理系统，Github 则是目前世界上最大的开源社区，如果你想利用好 Github，Git 是你必须要掌握的工具。

[git简易指南](http://rogerdudler.github.io/git-guide/index.zh.html)，这个教程很简单，帮你快速了解 git，13 页 PPT 形式的内容覆盖了 git 最基本的操作精华。

[Pro git](http://iissnan.com/progit/)

### Git 客户端下载

可以在 [Git 官网](https://git-scm.com/downloads)下载最新版 Git 客户端。若无法下载，也可以从网盘中[点击下载](http://pan.baidu.com/s/1boMJj7x)，网盘中提供了 mac、win32、win64 不同系统的 Git 客户端。

### 第一次安装 Git

#### Mac

如果你是 mac 电脑，就先别急着单独安装 git。

Mac 电脑自带 Xcode 开发软件，Xcode 中有一款工具叫 Command Line Tools(Xcode 默认不带这个工具)。所以我们需要先安装 Xcode 的 Command Line Tools。

![](https://raw.githubusercontent.com/wiki/xugy0926/getting-started-with-javascript/terminal.png)

(在终端输入，记得 `--install` 前面要有空格)

```shell
> xcode-select —-install
```

![](https://raw.githubusercontent.com/wiki/xugy0926/getting-started-with-javascript/xcode-select-install.png)

如何判断 Xcode 的 Command Line Tools 是否成功安装了呢？

在终端中再次输入 `xcode-select —-install`，如果出现以下信息，就表明你已经成功安装 Command Line Tools 了。

```shell
xcode-select: error: command line tools are already installed, use "Software Update" to install updates
```

Xcode 的 Command Line Tools 安装成功后，意味着 Git 也安装成功了。

检查 Git 是否安装成功，在终端输入 `git —-version`

![](https://raw.githubusercontent.com/wiki/xugy0926/getting-started-with-javascript/git-check.png)

#### windows

下载 Git SCM，网址：[https://git-scm.com/download/win](https://git-scm.com/download/win)。若无法下载，也可以从网盘中[点击下载](http://pan.baidu.com/s/1boMJj7x)。

#### Linux

(在终端操作)

```shell
> sudo apt-get install git
```

#### 检查 git 的安装情况

安装成功后，在终端执行下面的指令，检查 git 是否安装成功。

(在终端操作)

```shell
// 查看 git 版本
> git --version

//或执行 git，将会看到一堆关于 git 的命令解释内容
> git
```

以上两个命令可以检查你的 git 是否安装成功。

如果提示 Command not found，说明 git 没有安装成功，需重新安装。


