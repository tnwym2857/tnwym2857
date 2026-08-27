Shota — AI × Web Engineering Portfolio

製造業で培った課題発見力と、Python・Web開発・データ分析のスキルを掛け合わせ、
"現場で使われるAI機能・Webプロダクト" を開発することを目指しています。

## 📌 About Me

- 滋賀在住／製造オペレーション10年、生産管理3年
- 業務改善・データ管理・VBA自動化の経験
- 独学でPython・Djangoを用いたWebアプリ開発に取り組み、現在はFastAPIを学習中
  （Djangoで作成したECサイトのFastAPI移植に取り組んでいます）
- 英語学習にも取り組み、海外の技術情報を自力で読み取れるレベルを目指しています
- 目標：AI × Web × DX の領域で、課題発見〜実装〜改善まで一気通貫で価値提供できるエンジニアへ

## 🔧 Skills

**Languages / Tools**

- Python（pandas / matplotlib / seaborn / scipy）
- Django（Webアプリケーション開発）
- FastAPI（学習中）
- SQL（BigQuery / PostgreSQL）
- Excel VBA（業務自動化）
- Tableau / Looker（学習中）
- Git / GitHub
- 英語学習（A1→A2→B1を目標）

## 💪 Strengths

- 現場理解 × データ活用の掛け合わせ
- 課題発見力（製造業での改善経験）
- 数字で考える習慣
- 継続学習（毎日インプット＆アウトプット）

## 📊 Projects

### 業務SNSアプリ開発（Django）
🔗 https://github.com/tnwym2857/sns-app-tiktok-style

目的：Webアプリケーション開発の基礎力習得、業務ツールへの応用を見据えた技術検証

内容：
- Django によるフルスタック開発（ユーザー認証・画像投稿・いいね/既読機能）
- ユーザーごとの権限制御（自分の投稿のみ削除できる認可ロジックをテンプレート側・ビュー側の両方で実装）
- CSSをフレームワークに頼らず素の状態から実装し、TikTok風の3カラムレイアウトを再現
- DevToolsのNetworkタブを用いた実践的なデバッグ（テンプレート継承漏れによるCSS未読み込みの原因調査）

### ECサイト開発（Django + Stripe決済連携）
🔗 https://github.com/tnwym2857/vegeket-ec-site

目的：実務レベルのWebアプリケーション開発（モデル設計・認証・決済連携）の実践、環境構築時のトラブルシューティング力の向上

内容：
- Django によるECサイト構築（商品管理・カート機能・注文履歴・ユーザー認証）
- Stripe API を用いたオンライン決済機能の実装
- 講座教材（Django 4.0系）と実行環境（最新版）とのバージョン差分から生じる多数のエラーを、ログを1つずつ読み解きながら自力で解決（ライブラリのビルド依存関係、環境変数管理、フレームワークの仕様変更への対応など）
- Django admin を用いたデータ管理（商品・カテゴリ・タグ）

### Django Todo List App
🔗 https://github.com/tnwym2857/django-todo-app

目的：Django の基本構造とCRUD処理の理解

内容：
- Class-Based Views による CRUD（作成・閲覧・編集・削除）の実装
- Bootstrap 5 を用いたUI整形、カードUIと優先度バッジによる視認性向上
- 削除前に確認画面を挟む誤操作防止設計

### 製造ラインKPI可視化・分析（Python）
🔗 https://github.com/tnwym2857/manufacturing-kpi-analysis

目的：現場データの傾向把握と改善案の示唆出し

内容：
- pandasによる不良率・稼働率・OEE（設備総合効率）の算出
- 不良原因のパレート分析による改善ポイントの特定
- 週次OEEヒートマップによるライン間比較

ポイント：製造現場の知識を活かし、数字の裏側にある"現場の動き"まで踏み込んだ分析。

### 小売店 売上分析＆Excelレポート自動生成（Python）
🔗 https://github.com/tnwym2857/sales-report-automation

目的：日次・週次の定型業務を自動化し、作業時間を削減

内容：
- pandas / matplotlibによる部門別・商品別の売上トレンド分析
- openpyxlによるExcelレポート自動生成（グラフ埋め込み込み）

### 統計的検定による意思決定の検証（Python）
🔗 https://github.com/tnwym2857/statistical-analysis

目的：統計的検定を使い、データに基づいた意思決定につなげる力を養う

内容：
- t検定・効果量（Cohen's d）・信頼区間による2グループ比較
- 検定の前提確認（正規性・等分散性）とノンパラメトリック検定による頑健性チェック
- 検定結果を踏まえた意思決定への提案までを一連の流れとして実施

### ECサイトのFastAPI移植（進行中）
目的：同一要件を異なるフレームワークで実装し、設計の違いを理解する

内容：
- Django版で実装したEC機能（商品管理・カート・決済連携）をFastAPIで再実装
- SQLModelによるDB設計、OAuth2による認証実装に挑戦中
- Django版での学びを踏まえ、設計改善を意識しながら移植を進行中

## 📚 Learning

- Python（分析・前処理・可視化）
- SQL（抽出・加工・集計）
- Django（Webアプリケーション開発）
- FastAPI（Webアプリケーション開発・非同期処理・認証・DB設計）
- 統計学（基礎）
- 英語（海外の分析事例を読めるレベルを目指す）
- AI・SaaSプロダクト開発のケーススタディ

## 🎯 Career Vision

- AI × Web × DX の掛け合わせで価値提供
- 要件定義〜分析〜改善提案まで一気通貫で関わる
- 自社SaaSのAI機能開発に携わる
- 製造業の現場理解を活かし、ドメイン特化AIの開発にも挑戦
- 将来的には、データ基盤整備や予測モデル導入にも関わる

## 🏅 Certifications

- VBAスタンダード
- Python 3 エンジニア認定データ分析試験
- 第1種衛生管理者
- 日商簿記2級

これらの資格を通じて、業務改善・データ分析・現場理解・数値管理の基礎力を体系的に身につけています。

## 📩 Contact

Email: tnwym2857@gmail.com
