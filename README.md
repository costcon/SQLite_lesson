# SQLite_lesson

#【動画】キノコード　 SQL 超入門講座

##　この Git について

##　目的
ほぼ全てのプログラミングに用いられるデータベースへの理解度を高め、
エンジニアとしての基礎力をあげる

勉強開始　 8 月 10 日〜

09.PostgreSQL の環境構築まで

Postgresql 基本コマンド説明

Postgres 起動
ターミナルユーザー直下にて下記コマンド

postgres -D /opt/homebrew/var/postgres
※その後アプリ起動しパスワード入力

データベースの切断

\q

postgresql の停止

contrl + C

## PGadmin の操作

バックアップ

Pgadmin を起動した状態のターミナル上で
pg_dump postgres > /Users/kamiyamatakuto/Desktop/SQLite.test_db

格納先とファイル名を指定して新規作成される

復元

Pgadmin の復元したい Database を選択 Create→Database をクリックしデータベース名を決める

その後ターミナルで

Psql database 名 < ファイル名

と入力する

PGadomin 停止

