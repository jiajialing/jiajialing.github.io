---
layout: page
title: About
description: About Sauchye
keywords: sauchye
comments: true
menu: 关于
permalink: /about/
---

嗨！你好呀，我是何乐(@jiajialing)

## 自我介绍
- 【姓名】[**何乐**](https://jiajialing.github.io/2019/04/08/learn-writing-opencamp/)**

- 【坐标】湖南-长沙  

- 【标签】效率控 工具控 搜索控 成长控

- 【我的技能】

  - 1.修得电脑

  - 2.工具控，各类电脑工具爱好者，有一套完整的软件工具箱，满足你的各种好奇

  - 3.搜索控，搜索帮你辨别真伪找到资源，找到很多你意想不到的资源（白+黑）

  - 4.电影和阅读控

- 【我能为你做什么】

  - 1.帮你找到大多数想要找到的网络资源（付费学习课程 + 破解软件）

  - 2.如何用重构的方式强力阅读

  - 3.推荐优秀又有趣的电影和书籍

  - 4.搭建网站，付费的网站和免费的网站（比如WordPress或zblog  bitcron github+jekyll建站）
   - wordpress：类似于[我做的站www.runplay.top](www.runplay.top/)
   - github+jeykll: [我的个人站:jiajialing.github.io](https://jiajialing.github.io)


- 【想勾搭】
  - 一些有想法的伙伴，一起读书，学习，输出，赚钱，搞事情

  - 附上一些我推荐的的一些链接：
  [有趣的网站](https://mubu.com/doc/bwl-hO7B3)

- 【2019年的三个期待】   
  - 1.三个百天计划（写作-英语-运营）
  - 2.30个主题阅读输出30+小主题论文 已经完成3个了，持续推进中
  - 3.作为3场线下或者线上大于50人活动的发起人
  - ![My WeChat](/images/about-me/wechat.jpg)
## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
