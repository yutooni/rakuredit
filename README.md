# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version
  ruby 2.6.6p146 (2020-03-31 revision 67876) [x86_64-linux]

* Rails version
  6.0.3.2

*初回セットアップ
```
$ docker build
$ docker-compose up
$ docker-compose run web rails db:create
```
* 2回目以降
2つのコマンドラインで操作
```
$ docker-compose up
$ docker-compose run web bin/webpack-dev-server
```


* ...
