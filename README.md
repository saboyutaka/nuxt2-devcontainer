# nuxt-devcontainer

Nuxt.js(Node.js)の開発環境をdevcontainerで構築するテンプレート


## 利用方法

1. devcontainerを立ち上げる
リポジトリをクローンしたディレクトリでVS Codeを開いて `Reopen in Container` を実行する。

2. サーバーを立ち上げる
ターミナルを開き以下のコマンドでNuxt.jsを起動する。

```
$ yarn dev
```

## devcontainerを既存のNuxt.js(Node.js)のプロジェクトで利用する場合
以下のファイルをコピーする

- [docker-compose.yml](docker-compose.yml)
- [.devcontainer/devcontainer.json](.devcontainer/devcontainer.json)
- [.devcontainer/docker-compose.yml](.devcontainer/docker-compose.yml)


## 技術スタック
- Node 16.x
- Nuxt.js 2.x
- TypeScript@~4.2
