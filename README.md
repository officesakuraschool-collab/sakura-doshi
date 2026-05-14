# どうしのれんしゅう

日本語初級学習者向け・動詞の形練習PWAアプリ

## ファイル構成

```
index.html      ← メインアプリ
manifest.json   ← PWA設定
sw.js           ← Service Worker（オフライン対応）
icon-16.png     ← ファビコン
icon-32.png     ← ファビコン
icon-180.png    ← Apple Touch Icon
icon-192.png    ← PWAアイコン
icon-512.png    ← PWAアイコン（大）
```

## GitHub Pages への公開手順

1. GitHubで新しいリポジトリを作成
2. このフォルダの全ファイルをアップロード
3. Settings → Pages → Branch: main / (root) → Save
4. 数分後、`https://<ユーザー名>.github.io/<リポジトリ名>/` でアクセス可能

## 機能

- て形 / ない形 / 辞書形 / た形 の練習
- 入力モード・選択モード・一覧モード
- オフライン対応（PWA）
- スマホのホーム画面に追加可能
