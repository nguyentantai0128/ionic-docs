---
previousText: 'Glossary'
previousUrl: '/docs/reference/glossary'
nextText: 'Release Notes'
nextUrl: '/docs/reference/release-notes'
---

# バージョニング

<!-- TOC goes here -->

Ionic Frameworkは<a href="https://semver.org/" target="_blank">Semantic Versioning (SemVer)</a>の形式: <code>メジャー.マイナー.パッチ.</code>に従います。互換性のないAPIの変更は<code>メジャー</code>バージョン、後方互換性のある機能を追加する時は<code>マイナー</code>バージョン、後方互換性のあるバグ修正は<code>パッチ</code>バージョンをあげます。

## リリーススケジュール

### メジャーリリース

メジャーリリースは、APIに重大な変更が加えられたときに公開されます。メジャーリリースはおよそ**6ヶ月**ごとに行われ、重大な変更が含まれる可能性があります。フィードバックを得るために、いくつかのリリース候補がメジャーリリースの前に公開されます。何が変更されているのか、またその理由がリリース候補に含まれる予定です。

### マイナーリリース

マイナーリリースは、新機能が追加されたとき、または非破壊的なAPIの変更が導入されたときに公開されます。私たちはリリースに自信を持てるように、どんな変更でも徹底的にテストしますが、新しいコードで新しい問題が起きる可能性があります。機能やAPIの変更があった場合は、**毎月**マイナーバージョンをリリースする予定です。

### パッチリリース

パッチリリースは、バグ修正が行われた時に公開されますが、APIは変更されておらず、重大な変更は導入されません。隔週で新しいパッチバージョンをリリースする予定ですが、予定からずれてリリースする必要がある場合があります。マイナーリリースの新機能で新しい問題を発生させることがないように、パッチリリースは常にマイナーリリースの前に公開されます。

## Changelog

注目すべき変更点の一覧はchangelogで確認することができます。これには、
各リリースでのすべてのバグ修正と新機能の一覧が含まれています。
<a href="https://github.com/ionic-team/ionic/blob/master/CHANGELOG.md" target="_blank">changelog</a>