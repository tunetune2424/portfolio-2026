# Your Portfolio

フルスタック Web デベロッパーのポートフォリオサイトです。

## 📊 プロジェクト概要

React、Node.js、MongoDB を使った web 開発スキルを展示するためのポートフォリオサイトです。
3 ヶ月の学習期間で、複数の実案件レベルのプロジェクトを完成させます。

**公開 URL:** https://portfolio.vercel.app

---

## 🎨 特徴

- ✅ モダンで美しいデザイン（Tailwind CSS）
- ✅ レスポンシブ対応（PC / タブレット / スマートフォン）
- ✅ スマートフォン対応ハンバーガーメニュー
- ✅ スムーズなスクロール遷移
- ✅ ホバーエフェクト実装

---

## 🛠️ 技術スタック

### フロントエンド
- **HTML5 / CSS3**
- **Tailwind CSS 4.x** - ユーティリティファースト CSS フレームワーク
- **JavaScript (Vanilla)**
- **Vite** - 高速ビルドツール

### デプロイ
- **Vercel** - フロントエンド ホスティング

### 開発ツール
- **Git / GitHub** - バージョン管理
- **Cursor** - コードエディタ
- **npm** - パッケージマネージャー

---

## 📑 ページ構成

- **Home（ヒーロー）** - サイトの第一印象
- **About** - 自己紹介
- **Works** - 制作プロジェクト一覧
- **Skills** - 技術スキル
- **Contact** - お問い合わせフォーム

---

## 🚀 セットアップ方法

### 前提条件
- Node.js v16 以上
- npm v8 以上
- Git

### インストール手順

```bash
# リポジトリをクローン
git clone https://github.com/YOUR_USERNAME/portfolio.git
cd portfolio

# 依存パッケージをインストール
npm install

# ローカルサーバーを起動
npm run dev
```

ブラウザで `http://localhost:5173` を開くと、サイトが表示されます。

---

## 📦 本番ビルド

```bash
# 本番用にビルド
npm run build

# ビルド結果を確認（プレビュー）
npm run preview
```

`dist/` フォルダに本番用ファイルが生成されます。

---

## 🌐 デプロイ方法

このプロジェクトは Vercel で自動デプロイされています。

### 自動デプロイフロー

1. GitHub に push
2. Vercel が自動で検知
3. `npm run build` を実行
4. `dist/` フォルダを本番サーバーにデプロイ

```bash
# デプロイするだけ
git add .
git commit -m "feat: update portfolio"
git push origin main

# Vercel が自動でデプロイ開始（1～2 分で完了）
```

### カスタムドメイン設定

独自ドメインを使う場合は、Vercel ダッシュボールの「Domains」から設定できます。

---

## 📝 ファイル構成
portfolio/
├── index.html          # メインの HTML ファイル
├── main.js            # JavaScript エントリーポイント
├── vite.config.js     # Vite 設定
├── tailwind.config.js # Tailwind CSS 設定
├── package.json       # プロジェクト設定・依存パッケージ
├── dist/              # ビルド済みファイル（本番用）
└── README.md          # このファイル

---

## 🎯 今後の予定

このポートフォリオは、以下の 3 つのプロジェクトの入口となります：

1. **みかん農家 HP** - React + Tailwind CSS
2. **カフェ予約システム** - React + Express + MongoDB
3. **EC サイト** - React + Express + Stripe 決済

各プロジェクトは、このポートフォリオからリンクされます。

---

## 👤 作者

- **名前:** [Your Name]
- **GitHub:** https://github.com/YOUR_USERNAME
- **Twitter / X:** [@your_handle]
- **LinkedIn:** [Your Profile]

---

## 📄 ライセンス

このプロジェクトは MIT ライセンスの下で公開されています。

---

## 📞 お問い合わせ

お仕事のご依頼やお問い合わせは、サイトの Contact ページからお気軽にどうぞ。

---

**最終更新日:** 2026 年 4 月 10 日