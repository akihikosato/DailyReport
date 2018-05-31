# DailyReport

## 目的
- 各自の日報を git を用いて管理することで、git の基本的な操作方法を習得
- Markdown 記法を覚える

## 運用方法
### Pull Request までの運用
 各自自身の github アカウントを開設し、ssh 認証を済ませて下さい。
 repositry は fork せず、直接 remote して下さい。
 
 1. 担当者は最新の report branch から daily branch を作成（ feature/05_28 と命名する ）
 2. 各自この daily branch から自身の branch を作成（ daily/kamitate0528 ）
 3. 日報を記載するファイルは、2018_5_w4/【name】日報.md に格納（週ごとに作成）
 4. 日報は .md 形式で記載、直近の日付が上に来るように記載する
 5. 日報記載後は、自身の branch を push
 6. github 上で Pull Request を作成（feature/05_28 <= daily/kamitate0528）
 7. 担当者が 個々の daily branch を merge する
 8. 担当者は report <= feature/**_** の Pull Request を作成し merge する
 
### commit でのコメント運用
該当する項目は、次の prefix をコメントに記載して下さい。
- 追加項目 Add: （Add: ファイルの追加）
- 編集 or 修正項目 Modify: （Edit: 誤字の修正）
- 削除行項目 Delete: （Delete: ファイルの削除）

### Pull Request でのタイトルの記載方法
【name】 日報 5月30日
 
 終業時には PR の作成まで必ず行うこと。
