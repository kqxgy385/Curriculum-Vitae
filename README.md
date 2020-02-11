# 職務経歴書

## 基本情報

|key|value|
|---|-----|
|Name|萩原圭市(Keiichi Hagiwara)|
|Twitter|[@hagyyyy](https://twitter.com/hagyyyy1992)|
|Qiita|[hagyyyy](https://qiita.com/hagyyyy)|
|SlideShare|[Keiichi Hagiwara](https://www.slideshare.net/ssuserde3f3f)|

## スキル
### 言語
- フロントエンド
  - HTML
  - CSS(Scss)
  - JavaScript(Vue.js2系,Vuex,vue-router,atomic design)
- バックエンド
  - PHP7系
  - CakePHP3系
  - MySQL5系
- バージョン管理
  - Git (GitHub)
- CI/CD,インフラ
  - CircleCI
  - Docker, docker-compose
  - AWS EC2, VPC, Route53, S3, RDS, Aurora, CodePipeline, CodeBuild
- その他
  - CodeIgniter(前職)
  - Laravel(趣味)
  - Python,Django(趣味)
  - Golang,Beego(趣味)

### その他

- アジャイル開発
- git flow
- Backlog, Redmine
- TDD

## 言語

- 日本語
  - ネイティブ
- 英語
  - ドキュメントを読める程度

## 強み

- 何事も自分ごととして考える主体性とまずはやってみる行動力
- フロントエンド、バックエンド、インフラなど幅広いレイヤーの経験
- マネジメント,チームビルディング,ビジネスサイドとの調整などの経験
- wantedly,twitter,勉強会などあらゆる経路からの採用実績

- ストレングスファインダー
  - 自我
  - 慎重さ
  - 分析思考
  - 最上志向
  - 調和性

## やったことはないが興味があるもの

- 事業の上流に関わる
  - ビジネス的に何が重要なのか当事者として関わり理解したいです。
  ビジネス的な視座を高めていき提案したり企画できるようになっていきたいです。
  また事業のスピードと技術のバランスに偏りが発生しないように、ビジネスサイドとエンジニアサイドの橋渡しになり両サイドから信頼される存在になります。

- 会社の予と実に関わる
  - 企業のお金の面により深く関わっていきたいです。
  予算に対する実績を見ながらお金の動き方を理解しながら動ける人になりたいです。

- テックリードとしてチームを引っ張れる人になる
  - 自分より優秀なエンジニアに納得感を持ってついてきてもらうためにも常に自分の技術力は高め続けていきたいです。

- 積極的に技術的な挑戦をする
  - もちろん事業のスピードと技術のバランスは意識して適切なフェーズかを判断した上で、
  個人とチームの技術的な知見・モチベーション向上と企業の技術ブランディングを高めていく目的としても新しい技術は積極的に挑戦していきたいです。

## 職務経歴
### 2018/9 - 現在 : GVA TECH株式会社

職務：Webエンジニア、サーバーサイドエンジニア、開発リーダー

サービス内容: 法人登記作成支援サービス「AI-CON登記」

- 新規プロダクト開発時の業務内容
  - プロダクトの企画段階から参画。士業の先生から要件をヒアリングしながら仕様の取りまとめと詳細設計を行う。
様々なレベル間のエンジニアが参画することから「設定より規約」を重視して、言語はPHP、フレームワークはCakePHPを採択。Dockerとdocker-composeを用いてローカル開発環境の構築を行い、デバッガツールXdebugの設定などを行った。環境構築はMakefileを用いて自動化をさせた。
インフラはAWSを用いて、EC2、ALB、VPC、Route53、CloudWatchなどの構築、その他、ドメイン取得のためSSL証明書の設定、決済代行サービスの設定などを行う。
上記作業完了後はサーバーサイドの設計と開発に従事。
2019年1月に無事ローンチすることができた。

- プロダクトローンチ後の業務内容
  - プロジェクト管理ツールBacklogの導入を行いチケット駆動の開発体制を構築。
安定的な運用のためオーガニゼーションを分けてステージング環境の構築を行い、CircleCIを用いてCICDの構築をした。
Githubフローによるバージョン運用を導入し、マイナーバージョンアップではステージングで動作確認後リリースするように運用した。
ローカルとCircleCI上でテスト実行を行えるようにテストコード環境を構築し、TDDで開発できるようにした。
また０→１開発で生まれた技術的負債（多岐にわたるコードの重複など）の解決のため大幅なリファクタリングを行う。

- サーバーサイドエンジニアとしての主要な開発内容
  - 社内用管理画面の開発
    - ログイン機能
    - ログアウト機能
    - ログイン後ダッシュボード（ユーザー数、購入数など確認）
    - ユーザー一覧画面
    - 購入一覧画面
    - 管理ユーザー追加削除機能
  - 書類ダウンロード履歴・編集機能
    - 書類履歴テーブル、書類詳細テーブルの設計開発
    - 購入後画面とマイページからの購入書類の確認画面
    - 購入書類の返金機能（管理画面）
    - 購入書類の編集・保存などのサーバーサイド側の開発

- PMとしての業務内容
  - ビジネスサイドと開発サイドのバランスを取るべく現実的な計画を提示し期待値調整を測りながら、無理なく開発計画を遂行できるよう調整。
  - 開発状況把握や心理的安全性向上のためメンバーとの1on1を週1~月1間隔で実施し、開発進捗の取りまとめ、チームの士気向上に寄与。
  - ビジネスサイド、デザインサイド、リーガルサイドとの新規機能仕様打ち合わせ
  - リファラル、Wantedly、Twitterなども用いながら採用を行い3名のメンバーの採用に成功する
  - チームの状況に応じてフロントエンド側のサポートに回り要望対応したり、DevOps系のタスクを行い開発効率の向上などを行う。

### 2017/4 - 2018/8 : 株式会社ROBOT PAYMENT

職務: Webエンジニア、サーバーサイドエンジニア

サービス内容: 請求管理・請求業務のクラウドシステム(ソフト)「 請求管理ロボ 」

- 業務内容
  - 要件定義書作成
  - 詳細設計
  - コーディング
  - テスト仕様書作成
  - 結合テスト実施
  - 保守運用

- 使用技術、言語、フレームワーク
  - フロントエンド HTML CSS(Sass) JavaScript
  - サーバーサイド PHP(CodeIgniter)
  - データベース MySQL
  - 開発環境 Docker
  - インフラ AWS ECS

- エンジニア採用
  - イベント登壇
  - 面談
  - 紹介
  - 入社後フォロー

### 登壇歴

|Date|Event|Slide|
|---|-----|---|
|2019/06/18|あるあるLT〜サーバーサイドエンジニア〜 Vol.3|https://www.slideshare.net/ssuserde3f3f/hagiwara-ltpresentation-php-and-cakephp-150282990|
|2019/06/08|サービスリリースから安定軌道に乗せるまでに行った開発施策|https://www.slideshare.net/ssuserde3f3f/ss-149813668|
|2018/03/26|【大学生・大学院生限定！】AWS+Dockerハンズオン|https://cloudpayment-sys.connpass.com/event/80092/|
|2017/12/12|【大学生・大学院生限定！】Pythonを使ったWEBアプリケーションの作り方|https://cloudpayment-sys.connpass.com/event/70358/|

### 執筆歴
|Date|Title|Article|
|---|-----|---|
|2018/05|Django x Docker|https://qiita.com/hagyyyy/items/466b5bab67118175be65|
|2018/03|Dockerでローカル開発環境を作り、AWS-ECSにデプロイする|https://qiita.com/hagyyyy/items/959c115e0a5001972604|
|2017/12|Python Djangoでherokuにデプロイしてみた|https://cloudpayment-sys.connpass.com/event/80092/|
