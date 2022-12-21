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
                <h4>ヘルプ記事を検索してみましょう!</h4>
                <form>
                    <input type="text" id="search-input" data-role="input" placeholder="検索したい言葉を入力...">
                </form>
                <div class="search-list"></div>
            </div>
        </div>
    </div>
</header>

<section class="main_categories">
    <h3>カテゴリから探す</h3>
    <p>サポート記事をカテゴリ別に確認できます。</p>
    <hr>
    <div class="row">
        <div class="cell-12 cell-md-4">
            <div class="more-info-box category_fg">
                <div class="content">
                    <h3 class="text-bold mb-0">グローバルチャット</h3>
                </div>
                <div class="icon">
                    <span class="mif-chat category_fg"></span>
                </div>
                <a href="#" class="more category_fg"> 読む <span class="mif-arrow-right"></span></a>
            </div>
        </div>
        <div class="cell-12 cell-md-4">
            <div class="more-info-box category_fg">
                <div class="content">
                    <h3 class="text-bold mb-0">レベル機能</h3>
                </div>
                <div class="icon">
                    <span class="mif-arrow-up category_fg"></span>
                </div>
                <a href="#" class="more category_fg"> 読む <span class="mif-arrow-right"></span></a>
            </div>
        </div>
        <div class="cell-12 cell-md-4">
            <div class="more-info-box category_fg"> <!-- https://metroui.org.ua/colors.html 有効色 -->
                <div class="content">
                    <h3 class="text-bold mb-0">サーバー管理</h3>
                </div>
                <div class="icon">
                    <span class="mif-server category_fg"></span> <!-- https://metroui.org.ua/icons.html ただしFontAwesomeなども互換性あり -->
                </div>
                <a href="#" class="more category_fg"> 読む <span class="mif-arrow-right"></span></a>
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
</section>