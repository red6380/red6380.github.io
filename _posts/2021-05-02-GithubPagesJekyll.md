---
layout: post
title: github pages和jekyll搭建个人博客
tags: 日记 博客
categories: new
---
* TOC
{:toc}

# 环境
 1. ruby 2.5以上版本即可，因为2.5以下版本ruby和devkit需要分开安装
 2. git  工具

# Github pages
登陆github，找到repositories,新建仓库,仓库名必须设置githubname.gitub.io的形式才能被别人直接访问，(githubnam为自己的github名)
![](/static/img/050303.png)
然后进入仓库，并且点击setting，进入pages生成个人github主页。
# jekyll
jekyll是github的官方内容管理系统，可以选择一个theme来完成个人博客的设置，有了theme主题，我们直接往仓库目录下的_posts文件夹下加自己写的文章就可以了，操作十分简单，省下了很多自己搭建内容管理系统。文章一般用makedown编写，文件头加上yaml配置就可以了，文件名格式有严格的规定：年-月-日-文章题目.md  (月和日都是两位数表示)
# git
git是一个开源的分布式版本控制系统，可以有效、高速地处理从很小到非常大的项目版本管理。
因为每次从远程仓库`pull`到本地仓库，本地仓库`push`到远端仓库都需要登陆github账号，相当麻烦，所以我们选择使用ssh认证来避免每次重复登陆。但是每次从本地`commit`到本地仓库需要重新认证
# 个人经历
成功搭建好自己的博客真是心酸呀！中途遇见各种坑，有环境问题，jekyll主题和ruby版本不兼容问题，对yaml和makedown语法不熟悉。庆幸的是最好经过漫长的时间都解决了，所以坚持就是胜利。遇到问题不要慌！！！！！！！！！！
