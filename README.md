# sandakobo.github.io

Sandakobo スタジオの公開サイト。GitHub Pages で配信する純粋な静的 HTML。

## 構成

```
.
├── index.html              スタジオトップ（日英両対応）
└── plain-text/
    ├── index.html          プレーンテキスト アプリ紹介ページ
    ├── privacy.html        プライバシー方針（App Store 必須）
    └── support.html        サポートページ（App Store 必須）
```

## 公開 URL

- スタジオ: `https://sandakobo.github.io/`
- アプリ: `https://sandakobo.github.io/plain-text/`
- プライバシー: `https://sandakobo.github.io/plain-text/privacy.html`
- サポート: `https://sandakobo.github.io/plain-text/support.html`

## デプロイ

`main` ブランチに push すると数十秒で反映されます。Jekyll は使わず素の HTML で配信（`.nojekyll` あり）。

## 編集ポリシー

- 1 ファイル 1 ページの素の HTML。ビルドツール不要。
- ブランド色は `#2B7BFF`。フォントはシステムフォント
- 日本語と英語を 1 ページに併記する（ハッシュ言語切替なし）。
