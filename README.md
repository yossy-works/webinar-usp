# webinar-usp

「USPが教えてくれたこと〜10年間の実践のすべて〜」セミナー特設LP（1ページ静的HTML）。

## 公開URL

https://yossy-works.github.io/webinar-usp/

## 構成

```
usp/
├── index.html
├── assets/
│   ├── banner.png              # OGP兼メインビジュアル
│   ├── logo.png                # Rip.Dロゴ（フッター）
│   └── yoshimura_profile.png   # 登壇者写真
└── README.md
```

## ローカル確認

```bash
cd usp
open index.html
# または
python3 -m http.server 8080
# → http://localhost:8080
```

## 画像の差し替え

- **banner.png** … OGP兼ヒーローバナー。差し替え後は OGP キャッシュの都合で SNS 反映に時間がかかる場合があります。
- **logo.png** … フッター用 Rip.D ロゴ（黒背景版）。

## GitHub Pages

- リポジトリ: `yossy-works/webinar-usp`
- Source: `main` ブランチ / root

## 完成チェックリスト

- [ ] ブラウザで index.html を開いてデザイン確認
- [ ] モバイル表示確認（Chrome DevTools 幅 375px）
- [ ] GitHub Pages でアクセス確認
- [ ] [OGP確認ツール](https://rakurakutools.com/ogp/) で SNS 表示確認
- [ ] 必要に応じて `og:image` / `og:url` を更新してプッシュ

## 備考

- 申込みフォーム・問い合わせボタンはなし（情報共有のみ）
- 親ディレクトリ `webinar-lp/` は将来の他ウェビナー LP 用。本リポの Git ルートは `usp/` のみ
