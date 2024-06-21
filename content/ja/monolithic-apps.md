---
title: モノリシックアプリケーション
status: Completed
category: コンセプト
tags: ["アーキテクチャ", "基礎"]
---

モノリシックアプリケーションは単独で配置できるプログラムにすべての機能を格納しており、アプリケーションを開発する時に最も簡単かつ手軽な出発点とされています。
しかし、アプリケーションが複雑になると、モノリスのメンテナンスが難しくなることがあります。
また、同じコードベースで作業する開発者が増えるため、変更が競合したり、開発者の間で直接コミュニケーションを取る必要性が高まります。

## 解決すべき問題はなんですか

アプリケーションを[マイクロサービス](/ja/microservices-architecture/)に移行するとテスト、デプロイ、実行などの運用オーバーヘッドが増加します。
そのため、製品ライフサイクルの初期段階には製品を複雑化させる物は先送り、製品が成功したと判断されるまでモノリシックアプリーケーションで設計することが有利な場合もあります。

## どのように役に立つのでしょうか

適切に設計されたモノリスはアプリケーションを起動して実行する最も簡単な方法であるため、簡潔さを維持できます。
モノリシックアプリーケーションがビジネス的に価値があると証明されれば、アプリケーションを分割し、マイクロサービス化させる事も可能です。
価値が証明される前に技術的努力を費やし、マイクロサービス基盤でアプリケーションを開発することは早計である可能性があります。
アプリケーションが価値を生まなければ、その努力も無駄になるためです。