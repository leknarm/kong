# Get started
- Start database
```
docker compose up -d db
```
- Run migration
```
docker compose up migration
```
- Run kong
```
docker compose up -d kong
```
# Launch Kong Manager
- Navigate to http://127.0.0.1:8002