<!-- =========================================================
README.md ─ 原文準拠・フル情報版（スタイル保持）
========================================================= -->

<h1 align="center">職務経歴書</h1>

<p align="center">
  <!-- Tech / profile badges (原文にある技術のみ表示) -->
  <a href="https://openjdk.org/"><img src="https://img.shields.io/badge/Java-17-blue?logo=openjdk" alt="Java&nbsp;17"></a>
  <a href="https://kubernetes.io/"><img src="https://img.shields.io/badge/Kubernetes-blue?logo=kubernetes" alt="Kubernetes"></a>
  <a href="https://nodejs.org/"><img src="https://img.shields.io/badge/Node.js-green?logo=node.js" alt="Node.js"></a>
  <a href="https://docs.docker.com/"><img src="https://img.shields.io/badge/Docker-blue?logo=docker" alt="Docker"></a>
  <a href="https://img.shields.io/github/last-commit/toranoko114/resume">
    <img src="https://img.shields.io/github/last-commit/toranoko114/resume?label=Last%20Update" alt="Last&nbsp;Update">
  </a>
</p>

---

## 📝 職務要約
- **法政大学 法学部 法律学科** 卒業後、2016 年 4 月 **TIS株式会社** に入社。独立行政法人向け維持保全システムの Web アプリケーション開発を担当し、要件定義から運用・保守まで一通り経験。  
- 在籍後半 2 年は **プロジェクトリーダー** として顧客調整・進捗／品質管理・レビュー業務を実施し、チームを牽引。  
- 2021 年 9 月 **ヤフー株式会社** に転職（2023 年 10 月 LINE と合併し **LINEヤフー株式会社** へ社名変更）。  
- **Yahoo! 不動産 新築マンション領域** でフロントエンドからバックエンドまで幅広く開発。「物件成約で PayPay プレゼント企画」の開発・運用に加え、**Solr 9 バージョンアップ** や **NGINX Plus への移行** といった技術案件のパイロットを担当し、**四半期 MVP** を受賞。  

---

## 🏢 職務経歴

### LINEヤフー株式会社 (2023-10 – Present)
<details>
<summary><strong>主な業務・実績を表示</strong></summary>

| # | テーマ | 概要・成果 |
|:-:|-------|-----------|
| 1 | 物件数 No.1 奪還<br>公式サイトクロール対応 | - SUUMO へ奪われた物件数首位を奪還するための大規模改修<br>- フロントほぼ全画面（**約 200 ファイル**）を修正<br>- **1 週間前倒し**で無事故リリースし、翌週首位奪還を達成 |
| 2 | 社内プラットフォーム<br>(Kong→NGINX Plus) 移行 | - Internet 公開ドメイン **10 件** を対象に移行<br>- パイロット 1 ドメイン完了後にドキュメント／テスト／CI/CD を整備<br>- すべてのサービスを **無事故** でリリース完遂 |
| 3 | List-Unsubscribe 対応 | - Gmail ガイドライン対応でメールヘッダを追加<br>- **MQ → FaaS** のイベントドリブン構成でオプトアウト自動処理<br>- 個人情報案件として情報セキュリティ責任者レビューを実施 |
| 4 | Solr 7 → 9 バージョンアップ | - 21 コア中 1 コアをパイロットで担当（Solr 未経験からキャッチアップ）<br>- ドキュメント整備で後続コアの工数を **30→9 人日 (約 30% 減)** に短縮<br>- 期限内・無事故リリース |
| 5 | プライベート Kubernetes 移行 | - 新築マンション領域のパイロットを担当し **無事故完遂**<br>- 移行ノウハウを社員／業務委託メンバーへ展開 |
| 6 | E2E テスト導入 &<br>Change Lead Time 改善 | - 資料請求・見学予約フローに自動リグレッションテストを導入<br>- ブランチ戦略を **Git Flow → GitHub Flow** へ変更し、<br>前年同期比 **21%**, 直近 3 か月比 **60%** の CLT 削減を達成 |

</details>

---

### ヤフー株式会社 (2021-09 – 2023-09)
<details>
<summary><strong>主な業務・実績を表示</strong></summary>

| # | テーマ | 概要・成果 |
|:-:|-------|-----------|
| 1 | 物件成約で PayPay<br>プレゼント企画 (第1–4弾) | - **第1弾:** 新規バッチ機能を設計〜運用（排他制御・トランザクション管理を重視）<br>- **第2弾:** ユーザリスト自動抽出機能で通知業務を効率化<br>- **第3弾:** 約 **5 人月** の開発ディレクション／設計／運用を担当<br>- **第4弾:** 要件定義フェーズに早期介入し手戻りゼロ・テスト工数削減 |
| 2 | アプリ誤問合せ事故<br>ポストモーテム | - 本番誤問合せ事故の応急処置・事故レビュー・再発防止を実施<br>- WEB チームとアプリチームの橋渡しを担当し、再発ゼロを継続 |
| 3 | Java 17 + Spring Boot 3<br>バージョンアップ | - 自担当 **2 リポジトリ**＋委託 **8 リポジトリ** を期限内・無事故で移行 |

</details>

---

### TIS株式会社 (2016-04 – 2021-08)
<details>
<summary><strong>主な業務・実績を表示</strong></summary>

| # | テーマ | 概要・成果 |
|:-:|-------|-----------|
| 1 | プロジェクトマネジメント | - 2 億円規模 PJ を対象に **PJ 計画・仕様調整・原価／進捗／品質管理** を実施し完遂 |
| 2 | 要件定義・設計 | - 要件定義、基本設計、詳細設計の作成およびレビュー |
| 3 | 実装・テスト | - 実装／レビュー、テスト計画策定・仕様書作成・試験実施を担当 |

</details>

---

## 📈 キャリア年表

| 期間 | 会社 | 役割 |
|------|------|------|
| 2023-10 – 現在 | LINEヤフー株式会社 | ソフトウェアエンジニア |
| 2021-09 – 2023-09 | ヤフー株式会社 | ソフトウェアエンジニア |
| 2016-04 – 2021-08 | TIS株式会社 | Web アプリエンジニア → プロジェクトリーダー |

---

## 🛠️ 経験技術
| カテゴリ | スタック (原文ベース) |
|---|---|
| **プログラミング言語** | Java / Node.js / JavaScript / TypeScript / Python |
| **ストレージ・DB** | MySQL / Oracle / Redis / Amazon S3 |
| **検索エンジン** | Apache Solr |
| **コンテナ** | Docker / Kubernetes |
| **コンピューティング** | PaaS / FaaS |
| **CDN / Gateway** | API Gateway / NGINX Plus |
| **メッセージング** | Apache Pulsar |
| **CI/CD** | Screwdriver.cd |
| **認証・認可** | Athenz / IAM |
| **監視** | Prometheus / Grafana / 監視システム SaaS (LINEヤフー独自 PF) |
| **分析・モニタリング** | Splunk / Dynatrace |
| **その他** | GitHub / Confluence / Jira / Slack |

---

## 💪 活かせるスキル・経験
- **Java + Spring Boot** を中心とした Web アプリ開発（3 年以上）  
- **RDB (MySQL / Oracle)** の設計・開発・運用（3 年以上）  
- **フルサイクル開発**（要件定義〜運用保守）  
- **中規模トラフィック (~250 RPS)** のバックエンド開発・運用  
- 未経験技術でも主体的にキャッチアップし最後までやり抜く業務遂行力  
- 関係者・チームメンバーとの協業・コミュニケーション能力  

---

## 🏆 受賞歴
- **FY24 Q1 ものづくり部門 MVP**  
  - 「Solr7 EOL に伴う Solr9 へのバージョンアップ対応」(ものづくり 3 部門 55 名中選出)

---

## 🎓 学歴
- **法政大学 法学部 法律学科**（2012-04 – 2016-03）

---
