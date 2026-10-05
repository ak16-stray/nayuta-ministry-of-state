# NAYUTA Ministry of State

ナユタ公国 国務省の公式サイト（架空国家シミュレーション）。

## NAYUTA PUBLIC 自動表示

トップページは `note.json` を読み込み、最新3記事を表示します。

GitHub Actions が毎時17分に Note のRSSを取得し、`note.json` を更新します。

現在はテスト用として以下のNote RSSを使用しています。

`https://note.com/straywine/rss`

正式なNAYUTA PUBLICへ切り替える場合は、`.github/workflows/update-note.yml` の `RSS_URL` を変更してください。

## 注意

ナユタ公国は架空の国家です。
