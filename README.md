# Little Code Teacher

## Run all in containers

```bash
OLLAMA_BASE_URL=http://ollama-service:11434 docker compose --profile container up
# or OLLAMA_BASE_URL=http://ollama-service:11434 docker compose --profile container watch
```

## Use the native Ollama install

> To do for the first time only
```bash
ollama pull deepseek-coder
```

```bash
 docker compose --profile webapp up
 # or docker compose --profile webapp watch
```

## Open the Web UI

http://localhost:8080