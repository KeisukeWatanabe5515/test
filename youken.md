[toc]
# Project概要

## 要件説明
1.websocketを利用したチャットシステム作る
2.githubを用いてソースを管理する
3.今回はチャット機能をフロントサイドで視覚化できるまで行う
4.チャット機能を幾つかの`interFace`に分けて各々ローカルリポジトリで作成し、リモートリポジトリの `master` に `pull request` を投げる形でソースを統合していく

### インターフェース案
1.`認証`
2.`チャットルーム選択`
3.`画像アップロード`
4.`参加者一覧`
5.`メッセージ検索`

## 参考資料
### websocketチャット作成方法について
https://press.monaca.io/tag/websocket
http://www.koikikukan.com/archives/2012/01/30-000300.php
https://qiita.com/riku-shiru/items/ffba3448f3aff152b6c1
http://wild-data-chase.com/index.php/2019/03/20/post-643/

### websocketについて
https://www.keicode.com/script/html5-websocket-1.php
https://www.pari.go.jp/unit/ydaku/fujita/nodejsWebSocket/
https://qiita.com/okumurakengo/items/a8ccea065f5659d1a1de

**環境構築について**
1.git をインストールする
https://qiita.com/rild/items/46ec3b2e4a99bd5cc3b0
https://qiita.com/shuntaro_tamura/items/5228a29082a844d4875c
2.github と連携する仕組み
https://techacademy.jp/magazine/6235

**※補足**
1.npm init でpackage.jsonも作っておく(node.jsを使うため)
https://techacademy.jp/magazine/16151
2.vs codeでローカル作業をしたほうがターミナルもあるので効率がよい
https://qiita.com/psychoroid/items/7d85ae6bade4a67aedb1
3.vs code は拡張機能をインストールするとさらに便利になる
https://qiita.com/sensuikan1973/items/74cf5383c02dbcd82234
https://www.hypertextcandy.com/visual-studio-code-extensions/
https://ics.media/entry/18544/a
