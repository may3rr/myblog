---
date: "2023-03-27"
source: "微博网页版"
category: "life"
note: "通过ChatGPT一步步指导，从安装环境到运行项目，体验AI辅助学习的乐趣和实用性。"
tags: []
likesCount: 0
commentsCount: 4
repostsCount: 0
charCount: 646
id: "4883695422934067"
title: "用ChatGPT从零搭建GitHub项目"
images: ["/myblog/img/4883695422934067_0.jpg"]
---

今天用ChatGPT干了一件挺好玩的事情。

刷微博看到一个GitHub的项目分享，是一个关于gpt的文献润色。（项目地址：给特哈不.com/binary-husky/chatgpt_academic）

我就想尝试能不能用ChatGPT帮助我一步一步完成项目的Clone，项目的编译和运行。

首先，我Mac里的brew包貌似被我删掉了，gpt给我了安装homebrew的命令。

然后我发现终端貌似不能🪜，gpt给了我设置终端代理的命令（前提是有自己的节点）。

安装后发现我电脑也没装python的环境，gpt给了我安装python的网站，以及注意事项。

安装后发现终端python --version的时候，显示not found，gpt告诉我可能是电脑默认我的是python2.x，它教我改python3.x的环境，教我用nano编辑器，教我添加系统环境变量，还教我用python的idle写了一个hello world。

然后需要安装项目需要的一些依赖，也是gpt直接给的指令，还贴心的告诉我：要在python3 -m pip install -r requirements.txt的python后面加3。

最终成功运行了这个项目，但是代理目前还有点问题。。

以上所有的内容，对熟练的人来说都是最基本的知识，但是任何一个电脑小白都可以通过使用自然语言向ChatGPT学习并复现，它能帮你解决整个流程中可能遇到的大部分问题。

通过今晚的使用，帮我回忆起不少的知识，很开心。