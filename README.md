# Ros-Tutorial: A Tutorial for ROS Layman
**This repository serves as a ROS tutorial for ROS layman, arranged chapter by chapter.** Each chapter contains both `code` and `tutorial`.  





### 1. Usage 

#### A. Quick Start

Tutorial in each chapter have both `Chinese` and `English` version. 

To read `English` tutorial, run command below:

```sh
git checkout main-en
```

To read `Chinese` tutorial, run command below:

```sh
git checkout main-zh
```

And then run command listed below to start learning:

```sh
git checkout chapter1
```



#### B. Detail

Github branching model of this repository is list below

```txt
(main)  *-------------------------------------------------------------*--final bool
         \                                                           /
(main-en) |--------------chapter1-en---------chapter2-en   ...    --/
          |             /                   /                      /
(main-zh) |------------chapter1-zh---------chapter2-zh     ...  --/
          |           /                   /                      /
(dev)     '----chapter1----------------chapter2------      ... -'
```

So you can first `checkout` to the branch of your language, and the `checkout` between chapters to learn.



