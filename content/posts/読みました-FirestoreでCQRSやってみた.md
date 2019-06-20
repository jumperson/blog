---
title: "読みました-FirestoreでCQRSやってみた"
date: 2019-06-20T10:59:20+09:00
draft: false
tags: [ "設計" ]
---

[Firestore で CQRS やってみた - Speaker Deck](https://speakerdeck.com/yukin01/firestore-de-cqrs-yatutemita) を読みました。

Commnads用のデータ構造とQueries用のデータ構造を用意して、Commnadsに変更が入るとQueriesを更新する設計でした。
非正規化の設計だとこういう感じなのかもしれません。
