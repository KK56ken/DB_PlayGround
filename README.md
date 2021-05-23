# DB_PlayGround

## 使い方

リポジトリのクローンとディレクトリ移動
```
git clone https://github.com/KK56ken/DB_PlayGround.git

cd DB_PlayGround
```

データベースコンテナ立ち上げ
```
make up/b/d
```

コンテナ立ち上がっているか確認
```
make ps
```

mysqlのコンテナに入りmysqlを起動
```
make sql
```

### データベースの情報を削除したい場合
```
make down
```

