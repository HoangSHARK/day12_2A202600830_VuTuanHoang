# Deployment Information

## Public URL
https://day122a202600830-production.up.railway.app

## Platform
Railway

## Test Commands

### Health Check
```bash
curl https://day122a202600830-production.up.railway.app/health
# Expected: {"status": "ok"}
```

### API Test (with authentication)
```bash
curl -X POST https://day122a202600830-production.up.railway.app/ask \
  -H "X-API-Key: my-secret-key" \
  -H "Content-Type: application/json" \
  -d '{"user_id": "test", "question": "Hello"}'
```

## Environment Variables Set
- PORT: 8000
- AGENT_API_KEY: my-secret-key

## Screenshots
- [Deployment dashboard](image.png)
