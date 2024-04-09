---
layout: default
title: 
description: 
---

<header class="header" role="heading">
    <div class="card">
        <div class="card-content">
            <div class="search">
                <h2>何かお困りですか?</h2>
                <h4>私たちがお手伝いします</h4>
                <form>
                    <input type="text" id="search-input" data-role="input" placeholder="検索したい言葉を入力...">
                </form>
                <div id="result-list" class="search-list"></div>
            </div>
        </div>
    </div>
</header>

<section class="main_categories">
    <h3>カテゴリから探す</h3>
    <p>サポートトピックをカテゴリ別に確認できます。</p>
    <hr>
    <div class="row">
        <div class="cell-12 cell-md-4">
            <div class="more-info-box category_fg">
                <div class="content">
                    <h3 class="text-bold mb-0">サーバー設定</h3>
                </div>
                <div class="icon">
                    <span class="mif-cog category_fg"></span>
                </div>
                <a href="/category/config" class="more category_fg"> 読む <span class="mif-arrow-right"></span></a>
            </div>
        </div>
        <div class="cell-12 cell-md-4">
            <div class="more-info-box category_fg">
                <div class="content">
                    <h3 class="text-bold mb-0">告知</h3>
                </div>
                <div class="icon">
                    <span class="mif-star-full category_fg"></span>
                </div>
                <a href="/category/notice" class="more category_fg"> 読む <span class="mif-arrow-right"></span></a>
            </div>
        </div>
        <div class="cell-12 cell-md-4">
            <div class="more-info-box category_fg">
                <div class="content">
                    <h3 class="text-bold mb-0">不具合</h3>
                </div>
                <div class="icon">
                    <span class="mif-bug category_fg"></span>
                </div>
                <a href="/category/不具合" class="more category_fg"> 読む <span class="mif-arrow-right"></span></a>
            </div>
        </div>
    </div>
    <!--
        以下必要に応じて追加 いくつでも追加できます

        <div class="cell-12 cell-md-4">
            <div class="more-info-box bg-red fg-white">
                <div class="content">
                    <h3 class="text-bold mb-0">{{TITLE}}</h3>
                </div>
                <div class="icon">
                    <span class="{{ICON_CLASS}}"></span> 
                </div>
                <a href="{{CATEGORY_LINK}}" class="more"> 読む <span class="mif-arrow-right"></span></a>
            </div>
        </div>
    </div>

    -->
    <hr>
    <h3>最近の記事</h3>
    <ul>
        {% for post in site.posts limit:5 %}
            <p>{{post.date | date:"%Y/%-m/%d" }} - <a href="{{ post.url }}">{{ post.title }}</a></p>
        {% endfor %}
    </ul>
</section>
