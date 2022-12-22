# Ros教程：为ROS门外汉准备的教程

**本仓库是一份针对纯新手的ROS教程，教程以章节的形式组织**。每一章节中包括代码和对应的知识讲解。



### 1. 使用教程

#### A. 快速开始

本教程提供了`中文`和`英文`两种语言的版本。 

如果你要阅读`英文`版本的教程，运行下面的命令:

```sh
git checkout main-en
```

如果你要阅读`中文`版本的教程，运行下面的命令:

```sh
git checkout main-zh
```

在确定要阅读的语言后，运行下面的命令在不同的章节中切换，以进行学习

```sh
git checkout chapter1
```



#### B. 原理

本仓库的Git分支模型如下

```txt
(main)  *-------------------------------------------------------------*--final bool
         \                                                           /
(main-en) |--------------chapter1-en---------chapter2-en   ...    --/
          |             /                   /                      /
(main-zh) |------------chapter1-zh---------chapter2-zh     ...  --/
          |           /                   /                      /
(dev)     '----chapter1----------------chapter2------      ... -'
```

因此，不同语言的教程是以`branch`的形式维护的，而不同的章节是以`commit`的形式维护的。因此首先通过`git checkout branch`以确定语言，而后`git checkout commit`以阅读不同的章节。



