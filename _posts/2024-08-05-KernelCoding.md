---
layout:     post 
title:      抛砖引玉：在 Linux Kernel 源码里游泳
subtitle:   VSCode, clangd, Linux Kernel
date:       2024-08-05
author:     Haorong
header-img: img/home-bg-o.jpg
catalog: true 
tags:
- Linux
- Kernel Development
---

# 抛砖引玉：在 Linux Kernel 源码里游泳

这里抛砖引玉有两层意义：一是希望用这些粗浅的文章，来引出更加优秀的技术分享；二是对于那些对系统编程感兴趣，但还没开始实操的朋友，希望这些🧱能为第一步打下基础，期待你以后雕出的美玉。

## 获取 Linux Kernel 源代码

Linux 作为一个及其庞大的代码仓库，没法像别的小型项目一样使用基于 branch 的管理模式，即开发者通过 Pull Request 

```bash
git clone git://git.kernel.org/pub/scm/linux/kernel/git/stable/linux.git
```