# qiita-express-middleware

Qiitaへの投稿のソースまとめRepository

その投稿は、[Expressはミドルウェアで開発しよう！](https://qiita.com/walk8243/items/29a337381635b77ff25b)です！

## サブモジュールの更新方法

```.sh
git submodule init && git submodule update
cd ./express-middleware-router && git merge origin/master && cd ../
cd ./express-middleware-server && git merge origin/master && cd ../
```
