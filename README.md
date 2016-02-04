# docker-nginx-cache
Nginx のキャッシュ専用コンテナ
##DockerfileからのDockerイメージの作成方法
自分のマシンでDockerfileからのDockerイメージの作成する方法について説明します。
- Dockerfileの存在するディレクトリに移動します。
- docker build コマンドを実行します。

	`$ docker build -t my-nginx-cache .`
