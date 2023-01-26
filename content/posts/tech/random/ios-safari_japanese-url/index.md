---
title: "【個人的メモ】 Safari(iOS)で日本語の含まれたURLを共有する"
date: 2023-01-27T0:00:00+09:00
draft: false
---

こんばんは、よどがわです。  
今回はiOSのSafariで日本語の含まれたURLを共有する方法を紹介します。

## なぜ必要なのか

例えば、 `https://yodogawa404.net/日本語URL` というURLを共有したいときに、
画像の部分からURLを選択してコピーすると、

![](screenshot-001.jpg)

日本語の部分がエンコードされずにコピーされます。

![](screenshot-002.jpg)

このままツイートしてしまうと、日本語の部分がURLの一部として認識されず、
意図しないURLに転送されてしまいます。

![](screenshot-003.jpg)

## 対処法

対処法としては、画面下部の共有マークをタップして、

![](screenshot-004.jpg)

出てきた画面をスクロールし、

![](screenshot-005.jpg)

コピーを押します。

![](screenshot-006.jpg)

すると今度はエンコードされたURLがされるので、意図したURLに転送されます。

![](screenshot-007.jpg)