# react-template
create-react-appを実行して,reactアプリを作成するための、コンテナテンプレートです。(typescriptを使用)

アプリをコンテナ内に作成する
<サービス名>と<アプリ名>にあたる部分は、Dockerの設定ファイルに書いたものと同一になるように。
```bash
$ docker-compose run --rm <サービス名> sh -c \
"npm install -g create-react-app \
&& create-react-app <アプリ名> --template typescript"
```

自身のNotionも参考にしてみてね
https://www.notion.so/Docker-node-0521c3e0b8af4c7eaac1a475a8367263