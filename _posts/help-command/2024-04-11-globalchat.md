---
layout: post
title: コマンド紹介 - グローバルチャット
date: 2024-04-11 14:00 +0900
category: "help-command"
---

グローバルチャット(`/global_chat`)のコマンド一覧です。

<ul>
    {% for post in site.categories.cmd-globalchat reversed %}
            <p>{{post.date | date:"%Y/%-m/%d" }} - <a href="{{ post.url }}">{{ post.title }}</a></p>
    {% endfor %}
</ul>
