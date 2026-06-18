# Enterprise CRM System

React and Node CRM for lead tracking, sales pipelines, customer conversion, activity logs, dashboards, and role-based access.

## Run

```bash
cp .env.example .env
docker compose up -d
npm install
npm run dev
```

Frontend: `http://127.0.0.1:5173`

API: `http://127.0.0.1:4200`

## Demo Accounts

```text
admin@crm.test / 1234
manager@crm.test / 1234
rep@crm.test / 1234
```

The app uses MongoDB when `MONGODB_URI` is reachable. If MongoDB is not running, it keeps data in `.data/crm.json` so the project is still fully usable.
