# Okamoto Takumi Sony Portfolio

## 構成
- `index.html`: トップページ
- `styles.css`: デザイン・レスポンシブ設定
- `app.js`: 実績カード、写真拡大、スクロール表示
- `data/achievements.js`: 実績データ
- `assets/images/`: 掲載画像とPDFプレビュー
- `assets/pdfs/`: PROFILE・RESEARCHのPDF原本
- `netlify.toml`: Netlify公開設定とnoindexヘッダー
- `robots.txt`: 検索エンジンのクロール抑制

## GitHub
このフォルダ内のファイルを、GitHubリポジトリのルートへアップロードしてください。`index.html`がリポジトリ直下にある状態にします。

## Netlify
GitHubリポジトリをNetlifyへ接続し、以下で公開します。
- Build command: 空欄
- Publish directory: `.`

`netlify.toml`に同じ公開ディレクトリを設定済みです。

## 注意
`noindex`と`robots.txt`は検索結果への登録を抑制する設定であり、URLを知っている人へのアクセス制限ではありません。
