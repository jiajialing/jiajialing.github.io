---
layout: page
title: About
description: About me
keywords: 何乐
comments: true
menu: 关于我
permalink: /about/
---

嗨！你好呀，我是何乐(@jiajialing)

## 自我介绍
- 【姓名】[何乐](https://jiajialing.github.io/2019/04/08/learn-writing-opencamp/)

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


---
### 我的思考

人居于天地之间，是乃探求大道也。知其然亦知其所以然也，不恃己之所长，不揭人之所短，所谓道人善乃善也，扬人恶即恶也。

渺渺兮，处天地之间，虽不求闻达于诸侯，亦必问王侯将相宁有种乎？命自我立，福自己求。天行健，君子以自强不息，地势坤，君子以厚德载物。

于其外，世间万物变化无常，不知其所向，福兮祸之所伏，祸兮福之所伏，故不必疑困于心；于其内，处正念之中，为其善者，不以物喜，不以己悲，心知垢而可容之，是故道大也，人知心所往，因循道之所向，故心静平和，不为外物所累也。

### 立身七字

**德**：明德，乃知何为人，德在人先，利居人后；

**志**：明志， 志在长，不可常，有恒方有成；

**信**：有信，人所立于世，当知其重，无信则难以有为；

**礼**：知礼，发乎情止乎礼，礼之用和为贵；

**智**：归智，有智者，知其所以然，悟事之理 ，方得其道；

**辨**：明辨，是非辨则明，辨是非乃一要务，明辨而窥道；

**行**：笃行；知易行难，人不在知，而在能行，知行合一者，方可辨是非，明志向，悟道理，得其所法。

欢迎志同道合的朋友加我一起玩耍：**[暗号：精进]**

![My_WeChat](/images/about-me/wechat.jpg)

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
