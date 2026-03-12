# Weather API

A weather API that fetches data from OpenWeatherMap with Redis caching.

## Run

```bash
cp .env.example .env
# add your API key to .env
go run ./cmd/server/main.go
```

Open http://localhost:8800/weathers?city=tokyo
