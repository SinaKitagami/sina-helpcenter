---
layout: post
title: ユーザープロファイル作成時の通知
date: 2024-04-08 15:00 +0900
category: "config"
---

思惟奈ちゃんが導入されているサーバーで、初めて思惟奈ちゃんを利用したユーザーは思惟奈ちゃんのシステムにユーザープロフィールを作成し、作成した旨を通知するようになっています。

これらに関しては、通知のオン・オフが可能です。(既定値: オン)

> コマンド実行には設定するサーバーにおけるサーバー管理権限が必要です。(caution)

## 1. 通知をオフにする

{% picture jpt-webp disable-profile-notifi.jpg %}

`/comlock`の`add`オプションを使用し、`disable_profile_msg`を利用制限対象に追加してください。

コマンドを実行すると以下スクリーンショットにあるメッセージが送信され、ユーザープロファイルの作成通知が停止されます。

{% picture jpt-webp comlock-view.jpg %}

設定完了後、`/comlock`の`view`オプションを使用することにより、設定状況が確認できます。

なお、この際は`comname`オプションは不要です。

{% picture jpt-webp comlock-disable-profile-notifi.jpg %}

## 2. 通知をオンにする

{% picture jpt-webp enable-profile-notifi.jpg %}

`/comlock`の`del`オプションを使用し、`disable_profile_msg`を利用制限対象から削除してください。

コマンドを実行するとユーザープロファイルの作成通知が再開されます。

{% picture jpt-webp comlock-none.jpg %}

設定完了後、`/comlock`の`view`オプションを使用し、上記の状態になっていれば問題ありません。
