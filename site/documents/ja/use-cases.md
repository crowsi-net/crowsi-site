---
path: "/use-cases"
title: "権限と実行の境界を設計する"
summary: "各場面から、Crowsiの使い方と関連するガイドへ進めます。"
kind: "page"
label: "権限と実行の境界を設計する"
category: ""
status: "published"
---

## 許可された操作だけを

対象と権限を明示し、実行前に境界を確かめるための部品を提供します。

::document-link{title="実装を選ぶ：authorized-execution, crowsi-auth-routing" href="/capabilities/authorization"}
::

## 秘密を扱う責務を分ける

認証情報の保管と利用を分離し、アプリケーションに不要な秘密を渡さない設計を支えます。

::document-link{title="実装を選ぶ：credential-custody" href="/capabilities/credentials"}
::

## 結果を確かめる

プロセスと通信の境界を観測し、判断に使う証跡を構造化します。

::document-link{title="実装を選ぶ：security-observations, crowsi-service-telemetry" href="/capabilities/observability"}
::

