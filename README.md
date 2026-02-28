# 禅リスト

和風デザインのTodo＆習慣管理PWAアプリです。

## GitHub Pagesへのデプロイ手順

1. このリポジトリをGitHubで作成（Public）
2. このフォルダのファイルをすべてアップロード
3. Settings → Pages → Branch: main / (root) → Save
4. `https://ユーザー名.github.io/リポジトリ名/` でアクセス

## AndroidへのPWAインストール

Chrome でURLを開き、下部バナー「ホーム画面に追加」をタップ、
またはメニュー（⋮）→「ホーム画面に追加」

## iOSへのインストール

Safari でURLを開き、共有ボタン →「ホーム画面に追加」

## ファイル構成

- `index.html` — アプリ本体
- `manifest.json` — PWAマニフェスト
- `sw.js` — Service Worker（オフライン対応）
- `icon-192.png` — アイコン（192×192）
- `icon-512.png` — アイコン（512×512）
- `icon.svg` — SVGアイコン
