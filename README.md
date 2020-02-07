# ruby on railsでブログを作成!

ポートフォリオ用にruby on railsを使用し、ブログを作っています！
現在、制作中で今後、機能を追加していく予定です。
## 新規ユーザー登録機能
現在実装中です！

## blogconfigテーブル

|Column|Type|Options|
|------|----|-------|
|title|text|null :false|
|subtitle|text|null :false|
|stylename|text|null: false|

## bloggenreテーブル

|Column|Type|Options|
|------|----|-------|
|name|text|null :false|
|memo|text|null :false|

has_many:blogpost

## blogpostテーブル

|Column|Type|Options|
|------|----|-------|
|title|text|null :false|
|read|text|null :false|
|content|text|null: false|
|bloggenre_id|integer|null :false|

belongs_to:bloggenre

https://github.com/oosawa2070/my-app/issues/4#issue-561578147
