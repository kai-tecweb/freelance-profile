# 岩崎 哲也 / Tetsuya Iwasaki

**KAIテクノウェブデザイン 代表 | フルスタックエンジニア / プロジェクトマネージャー**
山梨県甲斐市 | 開発歴40年 | 完成プロジェクト5,000件以上

エンタープライズ領域でのPM/PL経験(最大200名規模)と、自社SaaSのフルスタック開発・運用を両輪で提供しています。受託(SES/業務システム)とAI・自動化SaaS開発の双方に対応可能です。

**受賞・登壇・出版**
- 2026年度 SMB Expert企業賞 システム開発部門
- Kindle『システムは、現場でつくる』出版(2026.09)
- ランサーズ主催 Claude Codeワークショップ講師(2026.06)
- ITトレンドEXPO 2026 Summer出展

---

## ⚡ RAG / LLM 実装ハイライト

- RAGパイプライン（OpenAI Embedding + Supabase pgvector + コサイン類似度検索）をLaravelでフルスクラッチ実装
- EmbeddingService / RagService を独立モジュールとして設計し、マルチテナント対応のナレッジ検索基盤を構築
- AI工房（ai-koubo.com）：Claude APIを活用したドキュメント処理・LLM回答生成を本番稼働中
- AI買取査定システム（PM）：AI画像解析・AI-OCR・LLMを組み合わせたマルチモーダルAIパイプラインを主導
- AFA：YOLO + ByteTrackによるサッカー映像AI解析を本番稼働中

---

## 🛠 Tech Stack

**バックエンド / Web**
- Laravel 11/12 (Inertia.js / Jetstream / Livewire)
- Node.js / Express / FastAPI

**業務システム / レガシー連携**
- C# / VB.Net / Java / COBOL
- Visual Studio / BizDesigner / SVF(帳票)

**フロントエンド**
- React / Next.js / Vue.js / Vite / Tailwind CSS

**モバイル (PMとして要件定義・進捗管理)**
- iOS / Android

**データベース**
- MySQL / PostgreSQL / SQL Server / Oracle / Redis

**インフラ / クラウド**
- AWS (EC2, RDS, S3, Lambda)
- さくらVPS / OCI / Vercel / Supabase
- Docker / PM2 / Nginx

**AI / 自動化**
- Anthropic Claude API / OpenAI / Gemini / Stability AI
- AI画像解析 / AI-OCR / LLM実装
- RAGパイプライン（OpenAI Embedding + Supabase pgvector + コサイン類似度検索）
- EmbeddingService / RagService フルスクラッチ実装
- Playwright / LINE Bot / Twilio / ElevenLabs
- Deepgram / AssemblyAI(音声処理)

**決済・運用基盤**
- Stripe決済 / GitHub Actions / Redis / BullMQ

**マネジメント**
- オフショア開発管理(ベトナム / フィリピン / アメリカ / カナダ)
- 多言語プロジェクト管理(日本語 / 英語 / ベトナム語)

---

## 🏢 受託 / SES案件(直近3年・PM/PL)

エンタープライズ向けの基幹システム・業務システムを中心に、PM/PLとして上流から運用まで一貫対応した案件です。

### 化学メーカーA社 — 分析証明書発行申請システム
**役割: PM｜期間: 2025.10〜2026.04**

化学品の品質を証明する「分析証明書」を社内Webから申請・自動発行する基幹業務システムを新規構築。製造現場と営業部門をつなぐ7画面構成のフロント＋バックエンドを担当。

- **担当範囲**: 詳細設計・テスト設計、7画面のフロント＋バックエンド開発、ベトナムオフショアチーム管理
- **チーム体制**: PM1名＋メンバー2名(プロジェクト全体 100〜200名規模)
- **使用技術**: C# / Oracle / BizDesigner / Visual Studio

### リユース企業B社 — AI買取査定システム
**役割: PM｜期間: 2025.02〜2025.08**

中古品の買取査定をAIで自動化するシステムを新規開発。スマホで撮影した商品画像をAIで解析し、AI-OCRで型番・状態を読み取り、LLMで査定文を自動生成する仕組みを構築。Web / iOS / Android の3プラットフォーム同時展開。

- **担当範囲**: AI画像解析・AI-OCR・LLMコーディング、3チームの総合進捗管理、要件定義・基本設計
- **チーム体制**: PM5名＋メンバー35〜70名
- **使用技術**: AWS / AI画像解析 / AI-OCR / LLM / Web・iOS・Android

### 化学メーカーC社 — MES・分析部門 生産管理システム
**役割: PM｜期間: 2024.06〜2024.11**

製造業の基幹となるMES(製造実行システム)と分析部門システムの構築・刷新プロジェクトに参画。総合テストとユーザー受入テスト(UAT)のテストリーダーを担当し、品質保証の最終フェーズを統括。

- **担当範囲**: MES・分析部門のテストリーダー、総合テスト・UAT、要件定義・基本設計、PM管理
- **チーム体制**: PM1名＋メンバー1〜3名
- **使用技術**: AWS

### 飲食店向けプラットフォームD社 — テーブルオーダー / 食材マッチング / グルメサイト連携
**役割: PM｜期間: 2024.06〜2025.11**

飲食店向けの複数サービス(テーブルオーダー、食材マッチングサイト、グルメサイト予約連携)を並行運営する大型プラットフォームのPM。Web / iOS / Androidの3プラットフォームを同時管理。

- **担当範囲**: 複数PJの進捗・スケジュール管理、フィリピン・アメリカ・カナダにまたがるオフショア管理
- **対象**: Web / iOS / Android

### ケーブル製造会社E社 — 生産管理システム カスタマイズ
**役割: PM｜期間: 2024.04〜2024.06**

ケーブル製造工場の既存生産管理システムを、現場業務に合わせてVB.Netでカスタマイズ。短期スポット案件としてリーダーポジションで実装まで担当。

- **担当範囲**: VB.Netでの生産システムカスタマイズ実装
- **使用技術**: VB.Net / SQL Server

### 食肉工場F社 — LINE受注 / 生産管理 / 請求・入金管理 一体型システム
**役割: PM｜期間: 2023.08〜2024.04**

食肉工場向けに、LINE経由の受注・生産管理・請求書発行・入金管理までを一気通貫で扱える業務システムを新規受託開発。要件定義から運用保守まで一貫対応。

- **担当範囲**: 要件定義 〜 設計 〜 開発 〜 運用保守
- **使用技術**: SQL Server / Windows

### 玩具メーカーG社 — Web-EDI インボイス制度対応
**役割: PM｜期間: 2023.05〜2023.08**

インボイス制度(適格請求書等保存方式)対応のため、玩具メーカーの基幹システムとEDI連携を改修。請求書フォーマット改修とバッチ処理新規開発を、エンドクライアントを含む3社調整のうえで完遂。

- **担当範囲**: 帳票改修、バッチ処理新規作成、基幹システム連携改修、エンドクライアント含む3社ヒアリング 〜 設計 〜 コーディング
- **使用技術**: Java / Oracle / SVF

### BtoB SaaS企業H社 — 顧客管理・名刺OCR・感情分析SaaS
**役割: 開発担当｜期間: 2026.08〜**

BtoB向けCRM SaaSをAWS基盤でフルスクラッチ開発。名刺OCR、問い合わせ感情分析、企業自動リサーチ、Stripeセルフサーブ契約までを一気通貫で構築。

- **担当範囲**: 要件定義 〜 設計 〜 開発 〜 運用保守
- **使用技術**: AWS(ECS Fargate / RDS PostgreSQL / Cognito / Bedrock / CDK)、Stripe、Tavily API

### 美容医療クリニック向けI社 — 動画切り抜きSaaS
**役割: 開発担当｜期間: 2026〜**

動画素材をアップロードすると、Whisperで文字起こしし、GPT-4oがショート動画候補を提案、テロップ編集まで行えるSaaSを本番構築。医療広告NGワードのチェック機能を含む。

- **担当範囲**: 要件定義 〜 設計 〜 開発 〜 本番運用
- **使用技術**: Next.js / TypeScript / ffmpeg / OpenAI API / さくらVPS + Cloudflare + R2

### 教育系J社 — 語学学習者マッチングプラットフォーム
**役割: 開発担当｜期間: 2026〜**

学習者・教師・管理者の3種ユーザーが使う、即時マッチング型の語学学習マッチングサービスを新規構築。ビデオ通話連携・報酬集計・複数ログイン方式に対応。

- **担当範囲**: 要件定義 〜 設計 〜 開発 〜 本番公開
- **使用技術**: Laravel / React / Inertia.js / さくらVPS / Cloudflare

### EC/メーカー系K社 — ブランドサイト＋店舗・代理店向け動的基盤
**役割: 開発担当｜期間: 2026〜**

製品紹介の静的サイトと、レビュー・店舗カタログ・決済・代理店階層管理を備えた動的基盤を2系統で構築。動画自動生成からSNS投稿までの導線も実装。

- **担当範囲**: 要件定義 〜 設計 〜 開発
- **使用技術**: Laravel / Inertia.js / React / Stripe

### 旅行業界系L社 — OTA在庫連携・チャネルマネジメント
**役割: 開発担当｜期間: 2026〜**

GetYourGuide/Klook/Viatorなど複数OTAの在庫・レビューを日次取得する連携ツールと、JTB BÓKUN経由のチャネル接続(Klook・Airbnb)を構築。

- **担当範囲**: 要件定義 〜 開発
- **使用技術**: 外部API連携 / Googleスプレッドシート出力

### 食品業界系M社 — 原価・レシピ管理システム
**役割: 開発担当｜期間: 2026〜**

1,000品超のメニューの表記ゆれ整理と、3段階の仕入単価更新に対応した原価・レシピ管理システムを構築。

- **担当範囲**: 要件定義 〜 設計 〜 開発

### その他の小規模案件
コーポレートサイト制作(静的1ページ、永続保守契約)、LINE公式アカウントのリッチメニュー制作・設定(複数社)、基幹システムのテスト工程参画(Oracle/Amazon Workspaces)など。

---

## 🚀 自社開発 / SaaS プロダクト

### AI・自動化系

| プロジェクト | 概要 | スタック |
|---|---|---|
| **AI工房** (ai-koubo.com) | RAG・LLM活用の中小企業向けAI SaaS。OpenAI Embedding + Supabase pgvectorによるRAGパイプライン実装済み。Gmail統合・議事録・翻訳・画像生成 | Next.js + Supabase + Claude API + Stripe |
| **EagleEye** | Instagram自動投稿・ストーリー生成システム | Laravel + LINE Bot + GPT + Stripe |
| **MailHunter** | 法人クロール＋AI自動メール送信 | Anthropic SDK + Gemini |
| **AI受電システム** | 音声クローン活用のAI電話対応 | Twilio + ElevenLabs + GPT-4o |
| **threads-control-center** | Threadsデスクトップ運用アプリ | FastAPI + Playwright + Pywebview |
| **Threado** | Threads投稿自動化(β運用中、アフィリエイト管理機能付き) | Node.js + PostgreSQL + Stripe |
| **TrendCatch** | TikTok Shopドロップシッピング自動化 | CJ Dropshipping API連携 |
| **いいね分析ツール** | Threadsいいね収集→Excel化。R2経由の自動パッチ配布で保守運用中 | Ruby/Sinatra + Playwright + Cloudflare R2 |
| **aio-monitor** | AIO/GEO監視(複数AIエンジンの言及率・引用率を計測) | OpenRouter経由マルチエンジン |

### SaaS・業務システム

| プロジェクト | 概要 | スタック |
|---|---|---|
| **eLinks** | リンク管理 + LINE Bot統合(5年以上運用中) | Laravel + Jetstream + Livewire + LINE |
| **HakoPit / DriverMS** | 軽貨物ドライバー管理マルチテナントSaaS | Laravel + Inertia/React |
| **culmino** | CRM / トレーニング管理 | Laravel + Inertia/Vue + PrimeVue + Reverb |
| **simple-invoice** | 請求書管理 + Stripe決済 | React/Vite + Stripe |
| **守成クラブ名刺管理** | 名刺データ管理システム | React + Node.js/Express |
| **いきなりHP** (ikinarihp.com) | 音声回答からAIがLP自動生成するスマホ専用SaaS | Next.js + Laravel/PHP + さくらVPS |
| **AIKOBOMall** | AI関連プロダクトのモール型ECサイト | Laravel + React + Square決済 |
| **MangaLoop** (mangaloop.jp) | 漫画LP自動生成・A/Bテスト基盤 | Next.js + MySQL + BullMQ |

### 長期運用・公共系

| プロジェクト | 概要 | 運用期間 |
|---|---|---|
| **cwj-mie-infection-information** | 三重県感染症情報システム | 2020年〜(5年以上) |
| **chair-artisan** | 椅子職人向け業務管理 | 2023年〜 |

### AI・映像・コンテンツ系

| プロジェクト | 概要 | スタック |
|---|---|---|
| **POSL** | SNS自動運用システム(シリーズ5製品) | Express + OpenAI / Laravel + Remotion |
| **AFA** | サッカー映像AI解析(選手トラッキング・シュート検出) | Laravel + YOLO + React |
| **OcrMaster** | レシートOCR(AWS/Azure/GCP併用) | Laravel + Inertia/React |

### 開発中・プレローンチ

| プロジェクト | 概要 | スタック |
|---|---|---|
| **posurisu.com** | Instagram自動化SaaS(インサイト分析→企画→画像生成→予約投稿) | Next.js + FastAPI + さくらVPS |
| **思い出マップ** | 写真・動画を地図ピンに紐づけるブック型アルバムPWA | React + Node/Express + Mapbox |

### 個人ツール・検証基盤

| プロジェクト | 概要 | スタック |
|---|---|---|
| **MetaPilot** | 広告実績レポート自動集計ツール | - |
| **R∞PC** | 中古PC販売支援(販売パートナー向け) | - |
| **FX検証基盤** | MT5自動売買のバックテスト・実験管理基盤。600超パターンを検証し統計的優位性を検証する基盤として構築(売買ロジックの提供ではない) | Python |
| **ses-jv.jp** | 自社コーポレートサイト(47ページ超)。GEO/SEO診断・構造化データ統合・AI Lab運用 | 静的サイト + 各種診断ツール |

---

## 📊 実績サマリー

```
総プロジェクト数(直近把握分):   51件
Git管理プロジェクト:            31件
長期運用中(1年以上):             4件
2026年直近3ヶ月の新規:          15件
最大コミット数:               1,596 (eLinks)
PM/PL担当案件(直近3年):          7件以上
最大マネジメント規模:        200名規模PJ
```

---

## 🌏 開発体制

- ベトナムオフショアチームのマネジメント(現地パートナー企業経由)
- フィリピン / アメリカ / カナダ 開発チームとの協業実績
- 日本語・英語・ベトナム語での多言語プロジェクト管理

---

## 💼 ご相談いただける領域

- **業務システム / 基幹システム**: 製造業MES、生産管理、EDI連携、帳票改修(インボイス・電帳法対応含む)
- **SaaS開発**: BtoB / BtoC SaaSの企画 〜 設計 〜 開発 〜 運用
- **AI / 自動化**: Claude / GPT / Gemini を活用した業務自動化、AI-OCR、画像解析、音声処理
- **マネジメント**: PM/PL、要件定義、上流設計、オフショア管理、品質保証(総合テスト・UAT)

---

## 📫 Contact

- 🌐 [KAIテクノウェブデザイン](https://ses-jv.jp)
- 💬 [LINE](https://line.me/ti/p/wnU_HnJJt9)
