---
path: "/capabilities"
title: "基盤を知る"
summary: "目的から機能を選び、対応するリポジトリと導入手順へ進めます。"
kind: "page"
label: "基盤を知る"
category: ""
status: "published"
---

## 権限と実行制御

操作対象・期限・権限を確認し、プロセスや通信の実行境界を設ける。

::document-link{title="対応ライブラリと使い方" href="/capabilities/authorization"}
::

::document-link{title="authorized-execution" href="https://github.com/crowsi-net/authorized-execution" summary="許可された操作の対象・期限・権限を束縛し、実行を制御する基盤。"}
::

::document-link{title="crowsi-auth-routing" href="https://github.com/crowsi-net/crowsi-auth-routing" summary="認可の経路定義を、アプリケーションとMCPインターフェースで共有する。"}
::

## 認証情報の保管と利用

認証情報の保管、利用権限、端末移行や復旧の責務を分ける。

::document-link{title="対応ライブラリと使い方" href="/capabilities/credentials"}
::

::document-link{title="credential-custody" href="https://github.com/crowsi-net/credential-custody" summary="認証情報の保管・限定利用・端末復旧を扱う基盤。"}
::

## 観測と運用の記録

セキュリティの観測とサービス運用の記録を、共有範囲を明示して扱う。

::document-link{title="対応ライブラリと使い方" href="/capabilities/observability"}
::

::document-link{title="security-observations" href="https://github.com/crowsi-net/security-observations" summary="指定範囲のセキュリティ観測と、判断の根拠となる記録を扱う基盤。"}
::

::document-link{title="crowsi-service-telemetry" href="https://github.com/crowsi-net/crowsi-service-telemetry" summary="サービスの運用記録を保持し、許可した範囲だけを公開する。"}
::

## プロセス間通信

ローカルプロセス間で、サイズ・時間制限付きのメッセージを交換する。

::document-link{title="対応ライブラリと使い方" href="/capabilities/transport"}
::

::document-link{title="crowsi-transport-foundation" href="https://github.com/crowsi-net/crowsi-transport-foundation" summary="ローカルプロセス間で、サイズ・時間制限付きのメッセージを交換する。"}
::

