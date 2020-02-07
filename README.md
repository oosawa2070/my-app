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
