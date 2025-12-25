# Backend API

Minimal Express.js backend for project-4.

## Quick Start

```bash
npm install
npm start
```

Server runs at `http://localhost:3000`

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/health` | Health check |

## Deploy to VPS

```bash
npm install -g pm2
pm2 start src/index.js --name project-4-api
pm2 save
```

## Expand

| Need | Add to |
|------|--------|
| New endpoints | `src/routes/` |
| Business logic | `src/controllers/` |
| Database/APIs | `src/services/` |
| Auth/logging | `src/middleware/` |
