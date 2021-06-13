# flask/graphqlによるCRUD機能(API側)

## 環境
python 3.9
mysql 5.7

### ライブラリ
graphql: ariadne

## 構築

~~~shell
$ docker-compose up -d --build
~~~

### db作成
apiのコンテナにアクセスし、ターミナル上で以下を実行

~~~
$ python
>>> from api import db
>>> db.creat_all()
~~~


## アクセス

http://localhost:5000