# ポートフォリオサイト

## 概要

個人ポートフォリオサイトです。

## 主な機能

- レスポンシブデザイン（デスクトップ、タブレット、モバイル対応）
- プロジェクト紹介セクション
- スキルセット表示
- 職務経験と資格の一覧
- SNSリンク統合

## 技術スタック

- HTML5
- CSS3（CSS Grid、Flexbox、CSS Variables）

## ファイル構成

```
portfolio/
├── portfolio.html                   　# メインHTMLファイル
├── docs/
│   └── screenshots/             　 # 画面のスクリーンショット
└── README.md                     # 本ファイル
```

## セットアップ

### 必要環境

- モダンWebブラウザ（Chrome、Firefox、Safari、Edge）

### 使用方法

1. リポジトリをクローン
```bash
git clone https://github.com/YOUR-USERNAME/portfolio.git
cd portfolio
```

2. ブラウザで開く
```bash
# 直接開く
open index.html

# またはローカルサーバーを使用
python -m http.server 8000
```

## デプロイ

### GitHub Pages

1. GitHubリポジトリにプッシュ
```bash
git add .
git commit -m "Initial commit"
git push origin main
```

2. リポジトリの Settings → Pages → Source で `main` ブランチを選択

3. 数分後、`https://YOUR-USERNAME.github.io/portfolio/` でアクセス可能

## カスタマイズ

### 個人情報の変更

`index.html` を編集し、以下の情報を更新してください：

- 名前とタイトル（ヒーローセクション）
- プロフィール文
- スキルリスト
- プロジェクト情報
- SNSリンク（GitHub、LinkedIn、Instagram）
- メールアドレス

### プロフィール画像

`Portfolio_ProfilePict.jpeg` として画像を配置してください。

### カラースキーム

CSSの `:root` セクションで色を変更できます：

```css
:root {
    --navy: #0d1117;      /* 背景色 */
    --green: #58a6ff;     /* アクセントカラー */
}
```
