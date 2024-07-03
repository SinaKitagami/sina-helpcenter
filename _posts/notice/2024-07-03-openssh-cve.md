---
layout: post
title: OpenSSHの脆弱性(CVE-2024-6387)に関して
date: 2024-07-03 23:00 +0900
category: "notice"
---

先日Xでも話題になっておりましたが、OpenSSHにおける重大かつ緊急性の高い脆弱性情報が発表されました。(<a href="https://www.cve.org/CVERecord?id=CVE-2024-6387" class="a-orange">CVE-2024-6387</a>)

本脆弱性の影響は以下の通りです。

- リモートからroot権限(Administrator)にて任意のコードが実行される可能性
- リモートからsshd(SSH接続のための常駐プログラム)のクラッシュを引き起こされる可能性

本チームでは本脆弱性の公開後、<a href="https://status.sina-chan.com/cly2zcv3w21918b5oaen5wfikh" class="a-orange">緊急メンテナンス</a>を実施し、全サーバーにて脆弱性に対する当該ソフトウェアのアップデートを実施しました。

つきましては、本チームにて使用している全てのサーバーにおきまして、本脆弱性への対応を完了しております。ご安心してご利用ください。

今後とも思椎奈ちゃんをよろしくお願いいたします。
