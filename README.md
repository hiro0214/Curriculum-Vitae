# 職務経歴書

## 概要
大学を卒業後、ドラッグストアの責任者として5年ほど従事。日頃の業務を進める中でシステムの重要性を大きく実感したことで、自分でもそういった便利なシステムやアプリケーションが作れるようになりたいと思い、エンジニアにキャリアチェンジ。現在はWeb制作の受託を行う会社のフロントエンドエンジニアとして2年半ほど勤務。

## キャリアプラン
1. 3年~5年をかけてフロントエンドのスペシャリストを目指す。　←イマココ
2. バックエンドも出来るようになり、エンジニアとしての専門性をより上げる。
3. 会社を代表出来るようなテックリードを目指す。

## やりたいこと
- Reactをメインにした、ユーザーのニーズに応えられるパフォーマンス性の高いUI/UXに優れたシステムやアプリケーションを開発していきたい。
- 世界にも誇れるようなサービスを企画、設計の段階から出来るエンジニアとして開発していきたい。
- 開発がスムーズに進むような組織作りをしていきたい。

## これから伸ばしていきたいこと
- より専門性の高いフロントエンドのコーディングスキル。
- サービスの規模が大きくなっても破綻しにくい設計力。

## スキルセット
### HTML[Pug]
- 業務と個人開発で3年ほど経験。
- 最近はアクセシビリティやSEO対策をしたコーディングをするように意識している。

### CSS[Scss]
- 業務と個人開発で3年ほど経験。
- CSS設計(FLOCSS)を行い、保守性・拡張性の高い破綻しにくい設計をするのが得意。

### JavaScript[TypeScript]
- 業務と個人開発で3年ほど経験。

#### React[Next]
- 個人開発で1年ほど経験。
- 今後一番力を入れて開発していきたい。

#### Vue[Nuxt]
- 個人開発で半年ほど経験。
- 最近はあまりキャッチアップ出来ていない。

#### Angular
- Angularの案件でコードを読み、少々知見がある程度。

### Ruby[Ruby on Rails]
- 個人開発で半年ほど使用。

### NestJS
- Udemyで勉強して、サンプルアプリを作ってみた程度。
- 時間がある時にもっと勉強していきたい。

## 職務経歴
### 株式会社ワンゴジュウゴ[2020/03~現在]
- 20名ほどの部署のフロントエンドエンジニアとして従事。
- 主な業務としては、担当案件のコーディングや新卒エンジニアの教育。また、部署内にフロントエンドエンジニアが自分と新卒の2人しかいないので、部署内におけるフロントエンドのリードエンジニアを担当。部署内からの相談を受けたり、リソースの管理、見積もり工数の算出など担当。

#### 主な担当した案件
##### BtoC向け某大手化粧品ECサイト 運用保守
###### 期間
- 2021/08~現在
###### 概要
ebisumartを用いたBtoC向け既存ECサイトの運用保守案件を担当しました。（ebisumart・・・ECサイトプラットフォーム）
<br>自社が担当するまでに4社ほどのベンダーを経由されており、どこもebisumartの知見が浅く先方の思うようなスピードでの開発が出来なかった。自社はebisumartのパートナーにもなっており、それに対応することが出来たため、長期的な運用保守を依頼されました。
###### 担当
- 主にフロント領域の全てを担当。
  - ページコーディング、新規機能開発、既存機能改修、ebisumartへの組み込み、テストなど。
- 当プロジェクトにおいてのリードエンジニア。
  - 他のエンジニアからの相談役。
  - Githubを用いてのソース管理
    - Gitルール策定、マージ係、プルリクのコードレビュー。
- 本番環境へのデプロイ。
###### メンバー構成
- 営業1人
- ディレクター2人
- デザイナー1人
- エンジニア6人（基本は自分1人で、リソースが足りない時に他のエンジニアにも入ってもらっていました）
###### 取り組んだ課題
- 前述した通り複数のベンダーを経由していたので、コードの書き方に統一性がなくとても煩雑なものになっていました。また、本来のebisumartに準拠した設計や書き方になっていないところも多く、JSで強引に実装されている機能がありました。
  - 設計の部分に関してはディレクターと綿密な相談を行い、拡張性やメンテナンスのしやすいように変更していきました。
  - 煩雑だったソースは、可能な限りシンプルなソースにリファクタリングしました。
- ebisumartには本番環境とデモ環境があるのですが、各環境にアップされているソースに相違があり、開発環境で改修したソースをアップしても思うような動作がしないことがありました。これは本番環境だけで実装されている機能、デモ環境だけで実装されている機能など様々なソースが入り乱れていたのが原因でした。
  - 自社が当プロジェクトを担当した時に、まず最初に解決するべき問題として取り上げました。
  - 各環境だけで実装されている機能やソースを全てリストアップし、必要なソース、不要なソースを整理後、1つのソースに統合し各環境にアップして、ソースの統一化を行いました。
###### 成果
- シンプルな設計にしたことで、コードの見通しが良くなりその後の開発がしやすくなりました。
- 先方のやりたかったこと、実装したかった機能などを実装したことで、先方からの信頼を得て現在も続く長期的に継続している案件となりました。

<hr>

##### BtoB、BtoC向け某大手スポーツ用品ECサイト 新規開発
###### 期間
- 2021/05~2022/04
###### 概要
某大手スポーツ用品ECサイトのリニューアルを依頼されたので担当しました。
最初にBtoB向けを開発後、当社の手腕を買われBtoC向けも開発依頼を受けました。
###### 担当
- フロント領域の全てを担当。
  - ページコーディング、デザイン調整、ebisumartへの組み込み、新規機能実装、環境構築、テストなど。
###### メンバー構成
- 営業1人
- ディレクター3人
- デザイナー2人
- エンジニア1人
###### 工夫点
- CSS設計(FLOCSS)を行いコーディングを行なったこと。FLOCSSを採用した理由は保守性・拡張性が高くなり、仕様変更や機能改修があってデザインの調整が入った際に、破綻しにくくメンテナンス性に強い設計になるため採用しました。
###### 成果
- BtoBサイトを新規開発しリリースした後、BtoCサイトの新規開発案件受注にも繋がり、部署の売り上げに大きく貢献しました。

<hr>

##### 自社サイト用LP 新規開発
###### 概要
自社のサービスを紹介するLPの新規開発を担当しました。（合計3サイト）
###### 担当
- コーディング、本番へのアップ。
###### メンバー構成
- 営業1人
- ディレクター2人
- デザイナー2人
- エンジニア1人

## 個人開発
### TechBoard
#### 概要
自分がReactを学んだ時に何かアウトプットしたくなり、エンジニア仲間に声をかけチーム開発という形で開発したもの。<br>サイトのコンセプトとしては、エンジニア向けのコミュニティサイトで掲示板機能と記事機能があります。よくある機能ですが、要件定義から設計、コーディングまで全てチームで相談して実装しました。
#### アプリケーション構成
- フロントエンド:React(TypeScript)
- バックエンド:Golang
- インフラ:Netlify、Heroku
#### メンバー構成
- フロントエンド3人
- バックエンド3人
#### 自分が実装した機能(フロント領域)
- 会員登録、ログイン、掲示板機能、デザイン、環境構築
##### 会員登録、ログイン
- ログインID、パスワード、ニックネームで会員登録機能を実装。
  - バリデーションは、ログインIDはユニーク、パスワードは8文字以上で実装。
- 会員登録、ログイン時にアクセストークンを発行して、ブラウザのCookieとサーバーにトークンを保存。ページ再訪問時にアクセストークンがあれば、自動でログインAPIを叩きログイン処理をするように実装。<br>※アクセストークンの保持期間は1時間。
- APIのレスポンスにより、エラー文言やトーストメッセージの表示。
##### 掲示板機能
- スレッド作成、コメント投稿を実装。
  - スレッドの作成はログイン必須。コメントの投稿はログイン不要。
  - コメントを投稿した際にログインIDとニックネームを表示。
  - ログインせずにコメントした際は、他のユーザーと区別をするためにランダムなIDを生成しそれをCookieに保存（初回だけ）。2回目以降コメントした際は、保存したIDを画面に表示させユーザーの紐付けが出来るようにしました。
  - コメントの投稿は1000件まででそれ以上は投稿不可。
  - useSWRを用いて、コメントが投稿された時にリロードをしなくても同期してフロントにコメントを描画させるように実装。
- スレッドの属性としてカテゴリーを持たせ、フィルタリングが出来るように実装。
  - カテゴリー一覧はサーバー側で定義しているものをAPIで取得して表示。
#### リポジトリ
- フロントエンド
  - https://github.com/GrowthOdyssey/TechBoard-FE
- バックエンド(別のエンジニアが担当)
  - https://github.com/GrowthOdyssey/TechBoard-BE
#### 制作期間
- 5ヶ月ほど。

<hr>

### gamehouse
#### 概要
自分でゲームを作るのが楽しくて好きなので、Reactのアウトプットも兼ねて作ってみました。<br>WebSocketを使い他のプレイヤーと同期しながらリアルタイムでゲームが進行するように工夫しました。
#### アプリケーション構成
- フロントエンド:React(TypeScript)
- バックエンド:Node(Express)
- インフラ:Heroku
#### リポジトリ
- https://github.com/hiro0214/gamehouse
