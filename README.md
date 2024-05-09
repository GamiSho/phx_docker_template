# Docker の雛形的なやつ(Phoenix, PostgreSQL)


### プロジェクト作成

```
# アプリ名は任意
docker compose run --rm app mix phx.new . --app アプリ名
docker compose run --rm app mix --version
docker compose run --rm db psql --version
docker compose up -d
docker compose run --rm app mix ecto.create
```

### Local 

[`localhost:4000`](http://localhost:4000)
