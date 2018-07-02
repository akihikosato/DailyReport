## 作業担当 /  作業時間
10:00~19:00(6月15日)
## 本日の進捗
#### Android Studio
  1. SearchView
    - GridViewからListViewに変えながらSearchViewもなくなった為、今回はActionbarにSearchViewを入れていつでも検索できるように作る。
    - menu.xmlファイルの位置が間違っていたのに気づかず、時間がかかってしまった。
    - SearchViewで右上段の検索アイコンを押せばテキストを入れるようにはなるが、どうやって入力した値を持ってくるのかはまだ調べる最中

  2. Image cacheのbackground task
    - 佐藤さんから聞いた話で、backgroundではなく他の所て処理するのかを調べる。AsyncTask、Picassoなど色んなライブラリーがあるらしいが、まだ詳しくはわからなくてもっと工夫が必要。


#### 本日のスケジュール

|時間  |概要  |詳細  |
|---|---|---|
|10:00 ~| Android Studio | ActionbarにSearchViewの追加 |
|11:00 ~| Android Studio |  |
|12:00 ~| Android Studio |  |
|13:00 ~| 休憩 |  |
|14:00 ~| Android Studio | Image cacheのbackground taskについて調べる |
|15:00 ~| Android Studio |  |
|16:00 ~| 報告会 |  |
|17:00 ~| 書類の準備 | 退職届の準備 |
|18:00 ~| 日報 |  |

## 明日の予定

#### 本日のスケジュール

|時間  |概要  |詳細  |
|---|---|---|
|10:00 ~| 報告会の準備 | 午後の報告会の準備 |
|11:00 ~| 報告会の準備 |  |
|12:00 ~| 報告会の準備 |  |
|13:00 ~| 休憩 |  |
|14:00 ~| Android Studio | Image cacheの処理を工夫 |
|15:00 ~| Android Studio |  |
|16:00 ~| 報告会 |  |
|17:00 ~| 報告会 |  |
|18:00 ~| 日報 |  |

## 連絡・相談・備考

## 時間外勤務
0.0 h

<hr/>

## 作業担当 /  作業時間
10:00~19:00(6月14日)
## 本日の進捗
#### Android Studio
  1. Custom ListView
    - activity_timeline.xmlをListViewにしてその中にカスタムするレイアウトを入れる方式
    - images.ktファイルを作ってカスタムレイアウトに入れる引数を定義、imageDataというObjectを作り、imagesのオブジェクトを使って仮にファイル名を入れる。そのあとObjectを利用してAdapterにつなぐ仕組み

  2. Search
    - homeTimelineを呼び出す形と似ている。Callback<Search>をrequireNoNulls()メソッドを使い、内容を引っ張ってきた。引っ張った値にentities.mediaを利用、イメージのurlのフィルタリングに成功


#### 勤怠システム
  1.個人情報修正画面の修正
    - 個人情報を修正したら権限が消されるのを修正
  
  2. ログイン画面の修正
    - 今まではエンターキーを押してもページが動かなかった為、修正
    - ログインボタンのborderをなくす、モバイル画面のボタンの大きさなど、CSSの修正

#### 本日のスケジュール

|時間  |概要  |詳細  |
|---|---|---|
|10:00 ~| Android Studio | Custom ListView |
|11:00 ~| Android Studio |  |
|12:00 ~| Android Studio | Tweet Search |
|13:00 ~| 休憩 |  |
|14:00 ~| Android Studio |  |
|15:00 ~| Android Studio |  |
|16:00 ~| 勤怠システム | 個人情報修正画面の修正 |
|17:00 ~| 勤怠システム |  |
|18:00 ~| 日報 |  |

## 明日の予定

#### 本日のスケジュール

|時間  |概要  |詳細  |
|---|---|---|
|10:00 ~| Android Studio | Urlからイメージを取り出す |
|11:00 ~| Android Studio |  |
|12:00 ~| Android Studio |  |
|13:00 ~| 休憩 |  |
|14:00 ~| Android Studio |  |
|15:00 ~| Android Studio |  |
|16:00 ~| 報告会 |  |
|17:00 ~| 報告会 |  |
|18:00 ~| 日報 |  |

## 連絡・相談・備考

## 時間外勤務
0.0 h

<hr/>

## 作業担当 /  作業時間
10:00~19:00(6月13日)
## 本日の進捗
#### Android Studio
  1. ListView
    - ListViewは試していなかった為、簡単なListViewを作ってみた。ListViewのGridLayoutの勉強も必要
  2. REST API
    - REST APIの資料を読む。Twitterの認証を得て、後の処理をしてくれるAPIだと理解した。
    - TwitterCore.getInstance().apiClient.searchService.tweetsを利用したが、Call<Search>の形の値が渡されて困っている。
    - 検索クエリに「filter:images」を入れたらイメージのtweetのみに検索できるようだ。

#### 勤怠システム
  1. 新規登録機能の修正
    - 昨日の続きで、新規登録をしたらsessionが変わる問題を解決。既に作られているfirebaseの認証の他に、名前を付けて新しい認証を得て、そこに新しいユーザーの情報を登録する。新しい認証のTokenが変わって、adminのログインは切れない。

#### 本日のスケジュール

|時間  |概要  |詳細  |
|---|---|---|
|10:00 ~|  |  |
|11:00 ~| Android Studio | List View |
|12:00 ~| Android Studio | REST API |
|13:00 ~| 休憩 |  |
|14:00 ~| Android Studio |  |
|15:00 ~| Android Studio | |
|16:00 ~| 勤怠システム | 新規登録機能の修正 |
|17:00 ~| 勤怠システム |  |
|18:00 ~| 日報 |  |

## 明日の予定

#### 本日のスケジュール

|時間  |概要  |詳細  |
|---|---|---|
|10:00 ~| Android Studio | GridLayoutの作成 |
|11:00 ~| Android Studio |  |
|12:00 ~| Android Studio |  |
|13:00 ~| 休憩 |  |
|14:00 ~| Android Studio | REST APIの工夫 |
|15:00 ~| Android Studio |  |
|16:00 ~| Android Studio |  |
|17:00 ~| Android Studio |  |
|18:00 ~| 日報 |  |

## 連絡・相談・備考

## 時間外勤務
0.0 h

<hr/>

## 作業担当 /  作業時間
10:00~19:00(6月12日)
## 本日の進捗
##### Android Studio
  1. 昨日の作業の続き
    - Twitter kitの認証をtutorialを見ながら実装
    - 'transformClassesWithDexBuilderForDebug'のエラーがあったが、解決できなかった。
  2. Twitter認証
    - 佐藤さんから頂いたコードを読む。大体な感じは分かったが、最初書いたコードの問題点はまだ見つけない。
    - companion objectについて調べる。自らのコードではConsumer key, Consumer secretをstring.xmlにだしたが、こんな書き方もあるのに気付いた。

##### 勤怠システム
  1. 新規登録機能の修正
    - 現在、firebaseで提供してくれるcreateUserメソッドを利用しているが、新規登録をしたらその情報で自動的にログインしてくれる問題がある。新規登録は管理者のみになっているので、かなり手間がかかるシステムになる為、解決方法を探す。
    - ログインされていた管理者の情報を変数に入れて、新規登録ユーザーをログアウト、またログインする方法は？と考えたがパスワードをとれる方法がなく、失敗した。
    - 検索結果、firebaseのサブアカウントを作ってそこから登録するとかの方法もあったがもっと工夫が必要。

#### 本日のスケジュール

|時間  |概要  |詳細  |
|---|---|---|
|10:00 ~| Android Studio | Twitterの認証とエラーの探し |
|11:00 ~| Android Studio |  |
|12:00 ~| Android Studio |  |
|13:00 ~| 休憩 |  |
|14:00 ~| Android Studio | 佐藤さんのコードを読む |
|15:00 ~| 勤怠システム | 新規登録機能の修正 |
|16:00 ~| 勤怠システム |  |
|17:00 ~| 勤怠システム |  |
|18:00 ~| 日報 |  |

## 明日の予定

#### 本日のスケジュール

|時間  |概要  |詳細  |
|---|---|---|
|10:00 ~| Android Studio | ListView |
|11:00 ~| Android Studio |  |
|12:00 ~| Android Studio | tweetを画面に出す |
|13:00 ~| 休憩 |  |
|14:00 ~| 勤怠システム | 新規登録機能の修正 |
|15:00 ~| 勤怠システム |  |
|16:00 ~| 勤怠システム |  |
|17:00 ~| 勤怠システム |  |
|18:00 ~| 日報 |  |

## 連絡・相談・備考

## 時間外勤務
0.0 h

<hr/>

## 作業担当 /  作業時間
10:00~19:00(6月11日)
## 本日の進捗
1. Android Studio
 - 個人プロジェクトの実装に苦難があり、使用APIを変えようとした。案として出たのがfabricとtwitter kit。
 - 最初は別々のものだと思ったが、fabricの中にtwitter kitを入れて使う感じだったが、今はfabricの中でtwitter kitを支援してないことを確認した。
 - fabricを使わずにtwitter kitだけでも使えるかを確認中。認証を試してる。

2. 報告会
 - キム、萩原算の報告を聞く

3. 勤怠システム
 - 使用感のチェック、デザイン的なところから機能的な問題を探して会議。管理者画面では修正事項なし。

#### 本日のスケジュール

|時間  |概要  |詳細  |
|---|---|---|
|10:00 ~| Android Studio | Twitter4jのAPIの工夫 |
|11:00 ~| Android Studio | 認証の試し |
|12:00 ~| Android Studio | twitter kit, fabric |
|13:00 ~| 休憩 |  |
|14:00 ~| Android Studio | twitter kitでの認証の試し |
|15:00 ~| Android Studio |  |
|16:00 ~| 報告会 |  |
|17:00 ~| 勤怠システム | 不具合や修正事項の確認 |
|18:00 ~| 勤怠システム |  |

## 明日の予定

#### 本日のスケジュール

|時間  |概要  |詳細  |
|---|---|---|
|10:00 ~| Android Studio | twitter kitの確認 |
|11:00 ~| Android Studio |  |
|12:00 ~| Android Studio |  |
|13:00 ~| 休憩 |  |
|14:00 ~| Android Studio | この後のスケージュールや進み方を決める |
|15:00 ~| Android Studio |  |
|16:00 ~| Android Studio |  |
|17:00 ~| Android Studio |  |
|18:00 ~| 日報 |  |

## 連絡・相談・備考

## 時間外勤務
0.0 h
