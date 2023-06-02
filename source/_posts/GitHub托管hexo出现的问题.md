---
title: GitHub托管hexo出现的问题
date: 2023-06-02 16:51:26
---
## 问题一：`Something's wrong. Maybe you can find the solution here`
```shell
## 首先删除.deploy_git文件夹
## 然后执行之下的命令
npm install hexo-deployer-git --save
hexo g -d
```
