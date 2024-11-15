# Djangoで作成したTodoリスト

このプロジェクトは、Djangoを使用して作成したシンプルなTodoリストアプリケーションです。Dockerを使用してコンテナ化し、簡単に実行できるようにしています。

## 実行手順

### 1. Dockerコンテナを作成し、起動する

まず、`django_todo`ディレクトリに移動して、以下のコマンドを実行します。

```bash
cd django_todo
docker-compose up --build
```

### 2. アクセス

コンテナが起動した後、ブラウザで以下のURLにアクセスします。

```bash
http://localhost:8000/folders/1/tasks
```

