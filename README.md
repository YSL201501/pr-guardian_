# PR Guardian

AI-powered Pull Request Risk Detection & Code Review Agent.

## Features

- Multi-Agent Workflow
- GitHub PR Review
- Security Scan
- AI Code Review
- RAG Knowledge Base
- FastAPI Webhook
- Docker Support

## Run

```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
```

## Webhook

POST:
http://localhost:8000/github/webhook