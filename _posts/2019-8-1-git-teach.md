---
layout: post
title: 和Little学git(1)
subtitle: git教程
---
### 使用git
#### 1 获取git权限
首先，我们创建一个文件夹。`mkdir gitlearn`
这个文件夹虾米都没有，不是git仓库。
git会对它排斥，不给它git权限。
要授予gitlearn git权限，`git init`
这样它就有了git权限。
#### 2 创建文件
```
touch hello.cc
vim hello.cc

```
在你的hello. cc里写
```cpp
int main()
{};
```
再 git commit hello.cc -m "Init"
他就被git管起来啦
