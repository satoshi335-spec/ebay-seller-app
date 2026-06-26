# eBay Japan Seller Assistant

日本の商品をeBayで海外販売するためのAIアシスタントアプリです。

## 機能
- 商品写真のアップロード
- AIによる英語キーワード・出品文の自動生成
- eBay相場リサーチ（Sold Items直接リンク）
- 発送方法・利益シミュレーション
- 出品前チェックリスト

## デプロイ手順

### 1. このリポジトリをGitHubにプッシュ

### 2. Vercelで新規プロジェクト作成
- https://vercel.com にログイン
- 「Add New Project」→ このリポジトリを選択

### 3. 環境変数を設定
Vercelのプロジェクト設定 → Environment Variables に追加：

| Name | Value |
|------|-------|
| `ANTHROPIC_API_KEY` | `sk-ant-xxxxxxxx`（あなたのAPIキー） |

### 4. Deploy！

## ローカルで動かす場合
```bash
npm i -g vercel
vercel dev
```

## APIキーの取得
https://console.anthropic.com でAPIキーを取得してください。
