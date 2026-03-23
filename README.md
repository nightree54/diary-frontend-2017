# Diary Frontend (2017)

## GitHub Description
Bootstrapを用いて開発した日記Webフロントエンド（2017年）。  
ログインバリデーション、日記UI、カルーセル、音楽再生機能を実装（※一部はブラウザ仕様変更により動作制限あり）。

---

## 画面イメージ

### ログイン画面
![Login Page](./screenshots/screenshot-login-page.png)

### 日記画面
![Diary Page](./screenshots/screenshot-diary-page.png)

---

## 概要
本プロジェクトは大学のフロントエンド授業における課題として作成した日記サイトのフロントエンドである。  
本課題は、個人での課題提出を提案し、授業の代替として実施したものであり、ログイン画面および日記表示画面を実装した。  
その結果、最終評価において1位の成績を取得し、完成度およびデザイン性の面で高い評価を得た。

---

## 機能

- ログイン画面  
  - メールアドレス形式の入力チェック（フロントエンドバリデーション）
- 日記表示画面
- レスポンシブデザイン（デバイス自動適応）
- 画像カルーセル機能
- 背景音楽再生機能

---

## 使用技術

- HTML5
- CSS3
- JavaScript
- Bootstrap
- jQuery

---

## ディレクトリ構成

diary-frontend-2017/  
├── css/  
├── js/  
├── images/  
├── Music/  
├── vendor/  
├── Index.html  
├── Login.html  
└── README.md  

---

## 実行方法

git clone https://github.com/nightree54/diary-frontend-2017.git
cd diary-frontend-2017  

ブラウザで以下を開く：  
Login.html  

---

## 既知の問題

本プロジェクトは2017年に開発されたため、現代のブラウザ（特にMac環境）において以下の問題が発生する：

- 音楽の自動再生が動作しない  
  推測理由：ブラウザのAutoplay制限  

- カルーセル機能が正常に動作しない場合がある  
  推測理由：  
  - Bootstrap / jQueryのバージョンが古い  
  - JavaScript依存関係の影響  

※ 実装上の問題ではなく、ブラウザ仕様変更による影響である。  

---

## 特徴

- BootstrapによるUI構築  
- レスポンシブデザイン対応  
- フォームバリデーション実装  
- フロントエンド単体で動作可能  

---

## 備考

本プロジェクトでは以下を目的として開発を行った：

- フロントエンド開発の基礎理解  
- UI設計およびユーザー体験の向上  
- Bootstrapを用いた効率的な画面構築  

また、本プロジェクトは全て個人で設計・実装を行った。  

---

## 作者

Night Tree