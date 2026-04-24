# GearMemo Landing Page

GitHub Pages で公開できる静的なランディングページです。

現在は、見出しや本文やナビゲーションを HTML テキストで実装し、ロゴやイラストやアプリ画面だけを画像として使う構成になっています。

## 構成

- `index.html`: ページ本体
- `style.css`: レイアウトとスタイル
- `assets/images/web-rough.png`: デザインラフ
- `assets/images/gearmemo-material.png`: 元素材
- `assets/images/extracted/`: ラフと素材から切り出した実使用アセット
- `assets/screenshots/`: ヒーローのスマートフォン内に表示するスクリーンショット

## スクリーンショットの差し替え

ヒーローのスマートフォン画面は、CSSで描画したフレームの中に個別画像を表示しています。
アプリのアップデート時は、以下の3ファイルを同じ名前で置き換えるだけで反映できます。

- `assets/screenshots/set-list.png`: 左のスマートフォン
- `assets/screenshots/main-set.png`: 中央のスマートフォン
- `assets/screenshots/usage-log.png`: 右のスマートフォン

推奨サイズは `390 x 844px` です。
同じ比率の画像であれば、CSS側で自動的にフィットします。

## ローカル確認

```bash
python3 -m http.server 4173
```

ブラウザで `http://127.0.0.1:4173` を開くと確認できます。


