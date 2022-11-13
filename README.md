## Dockerize Jupyter Notebook

### Build & Run Application
```sh
docker compose -f "docker-compose.yml" up -d --build
```

### Terminating Application
```sh
docker compose -f "docker-compose.yml" down
```

### Access the app
[localhost:8888/lab?token=docker](http://localhost:8888/lab?token=docker)


### Check Stock Data
https://finance.yahoo.com/quote/{SYMBOL}