# 如何贡献项目

首先非常感谢你愿意参与贡献这个项目，让我们一起努力越做越好。

参与贡献你可以参考下面的方法

## fork clone config

在 `GitHub` 上`fork`到自己的仓库，如 xxx/golang，然后`clone`到本地，并设置用户信息。
``` shell
$ git clone git@github.com:xxx/golang.git

$ cd golang

$ git config user.name "yourname"

$ git config user.email "your email"
```

## commit push

修改代码后提交，并推送到自己的仓库。

```bash
$ #do some change on the content

$ git commit -m "Fix issue #1: change helo to hello"

$ git push
```

## pr (pull request) 
在 `GitHub` 网站上提交 `pull request`。
当然了，如果你不会提`pr`，你可以参考我[给开源大项目贡献代码的文章](https://coding3min.com/653.html)

到这里就完成贡献的整个过程了。

## 同步代码

可以定期使用项目仓库内容更新自己仓库内容。
```bash
$ git remote add upstream https://github.com/golang-minibear2333/golang

$ git fetch upstream

$ git checkout master

$ git rebase upstream/master

$ git push -f origin master
```

这样就可以把我以后的更新同步到你本地啦~! 

## 丰富的贡献方式

其实你也不必提交代码来贡献，如果你发现项目中有任何不足、bug，或者疑问、新需求，你可以通过`issue`的方式让我提出。 我看到了会立刻给你回复

甚至你可以直接在电子书底部，直接点击`Edit this page`的链接，修改完毕后参考我的`commit`提交格式，提交后会自动`fork`到你的`github`里，此时直接发起`pr`即可！
