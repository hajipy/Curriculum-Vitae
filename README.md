# 職務経歴書

## 基本情報

|key|value|
|---|-----|
|氏名|斎藤 謙一(Kenichi Saito)|
|年齢|45歳|
|GitHub|[https://github.com/hajipy](https://github.com/hajipy)|

## 主なスキル

### 1. プロジェクトマネジメント

- テックリードとして、技術選定、開発プロセス設計、チームビルディング、プロダクトマネージャーとのやりとり、スケジュール管理、タスクアサイン
- エンジニアリングマネージャーとして、メンバーの目標設定、評価、1on1、採用活動

### 2. フロントエンド/バックエンド開発

- React、Next.jsでのフロントエンド開発
- React Nativeでのスマホアプリ開発
- Node.js(Express)、PythonでのREST APIサーバー、GraphQLサーバー、OAuth 2.0認可サーバーなどバックエンド開発

### 3. インフラ構築

- AWS Cloud Development Kit(AWS CloudFormation)でのインフラ構築

### 4. 技術スタック・全般的な技術サポート

- 大規模改修の調査・提案・実施
- 所属プロジェクト以外のライセンス・乱数などの重要機能をレビュー

## 職務要約

### 2001年〜2010年

2001年から、現楽天証券のオンライントレーディングシステムにおける設計、実装、テストなどの開発全般を担当。2002年からは同プロジェクトの市況情報サーバーチームのテックリードを担当。2005年から2010年までは、現ソフトバンクモバイルのデータ分析システムの開発を担当。

### 2011年〜2021年: KLab株式会社

2011年にKLab株式会社に入社。ソーシャルゲームに関連するデータ分析システム(PHP)、データ引き継ぎサービス(Python)、UI基盤(Unity、C#)の開発を担当。2016年から2021年にはUI基盤プロジェクトでテックリードとして、2週間サイクルのスプリントで計100回以上のリリースを実施。高品質なUIコンポーネントを安定的に提供し、全社の開発効率向上に大きく貢献。2015年以降はテックリードおよびエンジニアリングマネージャーとして、チームビルディング、採用・評価、メンバー育成なども担当。

### 2021年〜現在: 株式会社CureApp

2021年に株式会社CureAppに入社。フルスタックTypeScript(React、React Native、Next.js、Express)を用いた治療アプリの新規開発プロジェクトにおいて初代テックリードを担当。プロトタイプ段階からプロダクトマネージャーと協力し、技術選定、チームビルディング、環境構築を行い、リリースを目指してプロジェクトを推進。このプロジェクトはリリースには至らなかったものの、技術基盤の確立やチーム体制の構築に貢献し、将来のプロジェクトに役立つ経験を積む。その後は別プロジェクトにて、大規模改修の調査・提案を担当。

## 職務詳細

### 2021年12月〜現在 株式会社CureApp

#### 2024年07月〜現在 民間向けヘルスケアアプリの開発・運用
 
- **職務概要**: リリース済み民間向けヘルスケアアプリの安全性確保のため、大規模改修を担当しました。1つ目は「LoopBackフレームワークからのリプレース」です。このプロジェクトではLoopBackのサポート終了済みバージョンを使用した自社フレームワークで構築しており、サポート切れによるセキュリティーリスクやLoopBackを扱えるプログラマーの採用が難しいことが課題となっていました。2つ目は「MongoDBドライバーのアップグレード」です。現在使用中のバージョンのサポート終了が来年に迫っており、アップグレードしないとサービス継続ができないという状態でした。関連リポジトリーが10以上あり、そのうちいくつかはTypeScriptへの移行が済んでおらず、影響調査が困難でした。
- **主な成果**: 「LoopBackフレームワークからのリプレース」は結果をプロダクトマネージャー向けの報告ドキュメントにまとめました。リソース不足によりリプレースは見送りとなりましたが、リスク評価の完了により状況の把握と将来への対応が可能になった点が成果です。「MongoDBドライバーのアップグレード」については影響調査およびタスクの洗い出しを完了し、プロダクトマネージャーに引き継ぎました。これに基づき、プロダクトマネージャーが各プログラマーにアップグレードタスクをアサインできるようになりました
- **使用技術**: TypeScript、JavaScript、Flow、CoffeeScript、React、Next.js、React Native、LoopBack、MongoDB、AWS
- **チーム規模**: プログラマー 3名

#### 2024年01月〜2024年06月 治療アプリの開発・運用

- **職務概要**: 治療アプリの開発および運用を担当し、特にチャット機能の不具合解消と拡張に注力しました。このチャット機能は、ユーザーへの応答内容やタイミングを多数のReact Hooks内で複雑な条件式を用いて実装しており、当初はシンプルでしたが、機能追加を重ねるうちに理解が困難で誤動作が発生する状態にまで複雑化していました。そこで、今後のさらなる拡張にも対応できるよう、React Hooksに依存せず、自動テストの実装が容易な新たな設計を提案し、システム全体の保守性向上を図りました。しかし、経営判断によりプロジェクトは着任から半年後に凍結され、実際の改修には着手できませんでしたが、提案は次の段階での基盤として残っています。
- **主な成果**: 日常の運用業務を担当する傍ら、チャット機能の大規模改修に関する調査を行い、その結果を「現在の問題がなぜ発生しているのかをプログラマー向けに説明した技術ドキュメント」および「改修方法の選択肢と、それぞれの工数、メリット、デメリットをプロダクトマネージャーおよびプログラマー向けに説明した提案ドキュメント」にまとめました。 プロジェクトは外部要因によって凍結されましたが、会社にとって重要なプロジェクトであり、問題が解決され次第、再開される見込みです。その際にはこれらのドキュメントが重要な基盤となると考えています。 また、調査の過程でこれまで原因不明として放置されていた既存のバグをいくつか特定し、修正を行い、本番環境へリリースしました。この対応により、サービスの信頼性向上に大きく貢献しました。
- **使用技術**: TypeScript、React、React Native、Next.js、MongoDB、AWS
- **チーム規模**: プログラマー 2名

#### 2021年12月〜2023年12月 治療アプリの開発

- **職務概要**: 薬物治療を行うがん患者を支援するスマートフォンアプリの開発プロジェクトのテックリードを担当しました。プロジェクト参加時点で作成されていたプロトタイプをベースに、プロダクトマネージャーと協議しながらプロダクトとして必要な機能の要件定義を行いました。並行してチームビルディング、環境構築、技術選定などを進めました。テックリードとして特に注意を払った点は、医療という専門性の高いドメインを対象としていることから、設計意図や判断理由をしっかりとドキュメントに残し、メンバーが変わった際のプロジェクト継続性を確保することでした。また、一エンジニアとしては、ドメインエキスパートである医師から専門的な知見を得ながら、このアプリの肝となる複雑なロジックをドメイン駆動設計で設計・実装しました。経営判断により、プロジェクトは2年後に縮小され、しばらくあとに凍結されました。
- **主な成果**: 離任時点でアプリの全機能は完成しており、ステージング環境で最終テストを行いました。また、ブラッシュアップと不具合修正も進めており、プロジェクトは治験(実際の治療に使われる前の最終的な検証段階)直前でした。特に複雑なロジックについても医師による試験の結果、正しく動作していることが確認されていました。離任後に担当したエンジニアからは、設計意図や判断の理由を詳細にドキュメントに記載していたことで、技術的な背景を容易に理解しスムーズに開発を進めることができたと感謝されました。
- **使用技術**: TypeScript、React、React Native、Next.js、Express、MongoDB、PostgreSQL、AWS
- **チーム規模**: リーダー 1名、プログラマー 2名

### 2011年01月〜2021年11月 KLab株式会社

#### リーダー／マネジメントの職務経歴

2011年9月から2021年11月(約10年)、テックリードとしてチームメンバー3〜7名を率いて複数のプロジェクトにおける技術の方向性をリードしました。具体的には、設計レビュー、技術選定、タスクのアサイン、プロダクトマネージャーとの調整などを担当し、プロジェクト全体の技術的な成功を支援しました。特に、UI基盤ライブラリーと共通IDシステムの開発において、技術的な課題の解決を積極的に行いました。

2018年3月から2021年11月(約3年半)まで、エンジニアリングマネージャーとしてチームメンバー3〜7名を管理しチームの人材育成、パフォーマンス評価、採用活動を担当しました。メンバーごとの目標設定と1on1ミーティングを通じて成長をサポートし、チーム拡大にも尽力しました。

#### 社内横断レビュー業務の職務経歴

2015年1月から2021年11月(約7年)、社内横断の重要機能レビュワーとして、各ソーシャルゲームに対するレビューを担当しました。内製ゲームだけでなく外注ゲームのレビューも実施し、幅広い視点でプロジェクトの品質向上に貢献しました。リリースを急ぐ場面でも、品質を重視したレビューが行われ、システムの安定性が確保されていました。ガチャ、ライセンス、チート対策といった重要機能のレビューを行い、堅牢なシステムの構築を支援しました。1回のレビューは2〜4週間を要し、20回以上のレビュー経験を積みました。

#### プロジェクトの職務経歴

#### 2020年04月〜2021年11月 SketchからUnityへの変換ツール

- **職務概要**: Sketchで作成した画面デザインを自動でUnityのPrefabに変換するツールを開発し、手作業の負担を軽減しました。
- **主な成果**: 工数を大幅に削減し、デザイナーとプログラマー間の作業効率を向上させました。
- **使用技術**: Unity、C#
- **チーム規模**: リーダー 1名、プログラマー 2名

#### 2018年03月〜2021年11月 ソーシャルゲーム ストーリー作成支援ツール

- **職務概要**: ソーシャルゲームのストーリーパートをmacOS/Windows上で効率的に動作確認できるツールを開発し、開発プロセスの効率化を図りました。&#x20;
- **主な成果**: ビルド待ち時間の削減により、開発プロセス全体を効率化し、短いサイクルでの改善が可能になりました。
- **使用技術**: Electron、JavaScript、Node.js、React、Unity、C#
- **チーム規模**: リーダー 1名、プログラマー 2名

#### 2016年09月〜2021年11月 UI基盤ライブラリーの開発

- **職務概要**: ソーシャルゲームで共通利用されるUIコンポーネント集のライブラリーを開発しました。全社方針としてゲームエンジンをUnityに統一した際に、標準的なUIコンポーネントの不足を補うためにプロジェクトを発足しました。テックリードとしてスケジュール作成、タスクアサイン、プロジェクト外との調整を担当し、必要に応じて設計や実装にも携わりました。さらに、軽微な修正、CI環境の構築、ユニットテストの増強などでチームメンバーが重要な作業に集中できるようサポートも行いました。
- **主な成果**: UI基盤ライブラリーを標準化し、複数のプロジェクトにおけるUI開発の一貫性と効率を向上させることで、開発工数を削減しました。さらに、プロジェクト全体でパイプラインを整備し、技術的な課題に対処しやすい環境を構築しました。特に、テキストレンダリングパイプラインの導入により、1000行以上の条件分岐を持つ関数を分割し、性能と品質を改善しました。この結果、社内での信頼を得て、2017年以降にリリースされたすべての内製ゲームでこのコンポーネントが採用されました。
- **使用技術**: Unity、C#
- **チーム規模**: リーダー 1名、プログラマー 3〜6名

#### 2014年05月〜2016年08月 共通IDサイトの開発・運用

- **職務概要**: 複数のソーシャルゲームでデータ引き継ぎを行う共通IDサイトをフルスクラッチで開発しました。このサイトはスマートフォン間でプレイデータをスムーズに引き継ぐために設計され、将来的な拡張性と高負荷に耐えられる構成を取り入れました。主にOAuth 2.0認可サーバー、APIサーバー、カスタマーサポート用管理画面を構築し、安定性を確保しました。
- **主な成果**: OAuth 2.0のRFCを読み解き、RFCの仕様に準拠した認可サーバーをフルスクラッチで設計・実装しました。また、リリース前には負荷テストを徹底して実施し、将来の拡張に対応可能な負荷耐性を確保しました。コア部分の設計が完了した後は、若手メンバーの教育にも注力し、コードレビューや1on1で彼らの成長を支援しました。リリース後の別拠点チームへの移管も、ドキュメントの整備が十分に行われていたため、スムーズに完了しました。
- **使用技術**: Python、Flask、MySQL、OAuth 2.0、REST API
- **チーム規模**: リーダー 1名、プログラマー 2名、デザイナー 1名

#### 2011年09月〜2014年04月 ソーシャルゲーム データ集計システムの開発・運用

- **職務概要**: ソーシャルゲームの売上とアクセス数を集計するシステムを開発し、経営判断や監査対応に必要なデータを提供しました。
- **主な成果**: システム引き継ぎ後、安定性と信頼性を向上させ、集計頻度を四半期から日次に変更しました。データ欠損と整合性チェックを導入し、再集計の自動化で運用コストを削減しました。さらに、OAuth認証の導入によりセキュリティと運用コストを改善し、アクセスコントロール機能を実装しました。
- **使用技術**: PHP、Symfony、MySQL
- **チーム規模**: リーダー 1名、プログラマー 1〜2名

### 2005年11月〜2010年06月 フリーランス

- **職務概要**: ボーダフォン(現:ソフトバンクモバイル)の通話・通信ログ集計システムを開発し、日次で何十億件ものログを処理しました。ETLツール(AbInitio)とSQLを活用して集計バッチ処理を実装・運用しました。
- **使用技術**: SQL、PL/SQL、Teradata、Oracle、AbInitio、Solaris、Linux

### 2001年04月〜2005年03月 株式会社シンボリックテクノロジー

- **職務概要**: DLJディレクトSFG証券(現:楽天証券)のオンライントレーディングシステム「マーケットスピード」の開発を行いました。2002年からは同プロジェクトの市況情報サーバーチームでテックリードを務めました。
- **使用技術**: C、SQL、PL/SQL、Pro*C、Oracle、Solaris
