# GearMemo Landing Page

GitHub Pages でそのまま公開できる、静的なランディングページです。

## 構成

- `index.html`: ページ本体
- `style.css`: レイアウトとクリック領域のスタイル
- `assets/images/web-rough.png`: 画面ラフ
- `assets/images/gearmemo-material.png`: 元素材

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

今回は、提供された `webラフ.png` を最優先で忠実に見せる構成にしています。
今後、同じ見た目を保ったまま HTML セクションを細かく分割し、テキストやボタンを実装ベースへ置き換えていく拡張もできます。
