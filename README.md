# GearMemo Landing Page

GitHub Pages で公開できる静的なランディングページです。

現在は、見出しや本文やナビゲーションを HTML テキストで実装し、ロゴやイラストやアプリ画面だけを画像として使う構成になっています。

## 構成

- `index.html`: ページ本体
- `style.css`: レイアウトとスタイル
- `assets/images/web-rough.png`: デザインラフ
- `assets/images/gearmemo-material.png`: 元素材
- `assets/images/extracted/`: ラフと素材から切り出した実使用アセット

## ローカル確認

```bash
python3 -m http.server 4173
```

ブラウザで `http://127.0.0.1:4173` を開くと確認できます。

## GitHub Pages 公開手順

1. この内容を GitHub リポジトリに push します。
2. GitHub の `Settings` を開きます。
3. `Pages` を選びます。
4. `Build and deployment` の `Source` を `Deploy from a branch` にします。
5. `Branch` を `main` と `/ (root)` にして保存します。
6. 数分待つと公開 URL が発行されます。

## 補足

ラフの雰囲気を保ちながら、1枚画像ではなくセクション分割されたページとして再構成しています。
必要なら次の段階で、画像パーツをさらに細かく分解して再現度を上げることもできます。
