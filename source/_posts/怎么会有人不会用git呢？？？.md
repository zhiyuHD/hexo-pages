---
title: 怎么会有人不会用git呢？？？
date: 2026-02-23 00:42:38
tags:
---

## 我真的搞不懂
为什么会有人连git都不会？？？
这玩意挺简单的啊

### Clone
把远程仓库上的东西克隆到你电脑上

```bash
git clone 仓库地址
```

### Add 
把你本地仓库里的一个东西加到缓冲区里

```bash
git add 文件
```

不过基本都是直接add .，也就是所有修改过的文件，like this

```bash
git add .
```

### Commit
拿缓冲区里的东西提交到本地仓库

```bash
git commit -m "你做了什么更改"
```

### Push/Pull
这是最简单的

你已经Commit了你就推送到远程仓库里


```bash
git push
```

别人推送了你就Pull

```bash
git pull
```

还有，push不要加-f强推，除非你不是合作开发或者你的老母是批发的
