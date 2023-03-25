## Scenario
在多個 Docker 容器環境裡，若想要將不同的網域路徑 (URL path) 對應到不同的 Docker 容器中的 Nginx，
可以透過 Docker Compose 中的 nginx 服務以反向代理 (Reverse Proxy) 的方式實現。

## How to use
```
# docker compose up
```

就能連到 yml 裡面設定的兩個 container
* http://localhost/feature-1
* http://localhost/feauure-2