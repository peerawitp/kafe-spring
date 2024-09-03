# Kafe Web Spring

### Setup Database using Docker
```bash
docker run --name=postgres_kafe -e POSTGRES_PASSWORD=kafepwd -p 6543:5432 -d postgres:alpine
```