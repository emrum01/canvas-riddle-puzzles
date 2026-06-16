# Canvas Riddle Puzzles

ブラウザだけで遊べる静的パズル集です。  
元のアプリから、独立して公開できるように静的HTMLとして切り出しています。

## Included Puzzles

- `02-asterism.html`
- `03-tokino-kotonoha.html`
- `04-moon-reader.html`
- `index.html`

## Local Preview

最も軽い方法は静的HTTPサーバーで開くことです。

```bash
python3 -m http.server 4173
```

その後、以下を開きます。

```text
http://localhost:4173/
```

## Publish

このリポジトリは静的ファイルだけで動くため、GitHub Pages でそのまま公開できます。

1. GitHub に新しい public repository を作成
2. このディレクトリを push
3. GitHub Pages の公開元を `main` branch / root に設定

`index.html` が入口になります。

## Notes

- `04-moon-reader.html` は `three.js` を CDN から読み込みます
- フォントは Google Fonts を参照します
- 追加のビルド工程は不要です
