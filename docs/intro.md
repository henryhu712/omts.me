---
slug: /
title: Now
hide_title: true
sidebar_position: 1
---



## 计费系统

它是核心之一，因为大模型的计费形式多种，多用户管理复杂。



## The Default Room

每个用户，无论是注册用户还是匿名用户，都拥有一个默认房间 Playground。于是有了一个公开的免费使用的房间，用户点击进入，直接就可以和GPT聊天，没有什么注册、登录、绑卡等等过程。而且，聊天室的概念清晰简单，人人一看就懂。

从这里，我仿佛再一次从头开始设计 Airoom.


## Prisma

[Performance: How to make prisma perform a single SQL query with joins instead of multiple queries](https://github.com/prisma/prisma/discussions/12715)


## 客户端生成ID

[Client-Generated IDs vs. Server-Generated IDs](https://www.techyourchance.com/client-generated-ids-vs-server-generated-ids/)

[Why your software should use UUIDs](https://devforth.io/blog/why-your-software-should-use-uuids/)


## 密码工具箱

[使用 Web Crypto API 打造“密码学家的工具箱”](https://roubin.me/web-crypto-api-introduction/)


## Assis API

[Tutorial: Get started with the new OpenAI Assistants API](https://medium.com/@ralfelfving/tutorial-get-started-with-the-new-openai-assistants-api-7049c2517bfe)


## ESLint

[How to use ESLint with TypeScript](https://khalilstemmler.com/blogs/typescript/eslint-for-typescript/)


## Dto

[How To Use DTO For Validation in NestJS (2022)](https://betterprogramming.pub/how-to-use-data-transfer-objects-dto-for-validation-in-nest-js-7ff95309f650)


## 绝配

看 GPTs 创建过程，其中每一步都有太多的内容可以扩展，因此 OpenAI 目前在此所做的 GPTs 还十分单薄，GPT store 未来应该不是这个样子。

Airoom 和 Assistant API 是绝配，功能递进层级应该是这样：

- Rooms (AI workflow)
  - GPTs (Assistants)
    - LLMs

update: 奥特曼被解职了，下面这个评价很深刻：

I could barely watch the keynote. It was just another bland corp-speak bunch of product updates.

For those researchers I know that were involved from the beginning, this must have felt nausea-inducing.


## Making Assistants UI

界面参考：[How to build your own custom ChatGPT with OpenAI's GPT builder](https://zapier.com/blog/custom-chatgpt/)


## AI Agents

[AI Agent的千亿美金问题：如何重构10亿知识工作职业，掀起软件生产革命？](https://mp.weixin.qq.com/s/JYu_oXWbWbasT1fcBRo-cA)


## Room = Thread

不是给每个用户创建一个 Tread，而是一个房间对应一个 Thread，一个房间里只有一个会话。当你进入一个房间后，在房间里的 GPT 能记住之前的对话，就像它一直在房间等候一样，这很直观。


## AIROOM 首页

airoom 首页可以参考 Youtube，很贴切。

![youtube](./images/youtube.png)

但有一点要改进：标题和主要信息应该放在头部，而不是底部。图片不是最重要的，最重要的是标题和主要信息。把主要信息放到底部，看着费劲。

> 可视化：
> 把每个模型、助手、房间放到网页上，而不是通过下拉列表来选择，这样有更好的展示性，如果书店把书的封面展示一样。




