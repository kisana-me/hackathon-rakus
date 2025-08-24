## 作成

```
docker compose run app npm init vite@latest first-vue-app -- -- template vue
```

## 管理

```
docker compose run --build --rm app bash
```

```
docker compose -f 'compose.yaml' up -d --build
```

```
docker exec -it ???-app-1 bash
```
