# Task App (Flask + PostgreSQL + OpenRouter)

This project is a Flask task manager with:
- PostgreSQL for task storage
- OpenRouter for AI task insights

## 1. Environment Variables

Create a `.env` file in the project root and fill in real values.

Required values:

```dotenv
OPENROUTER_API_KEY=your_openrouter_key
POSTGRES_DB=taskdb
POSTGRES_USER=postgres
POSTGRES_PASSWORD=your_postgres_password
POSTGRES_PORT=5432
```

Notes:
- `POSTGRES_HOST` is optional; default is `localhost`.
- You can also pass `POSTGRES_URI` directly if needed.

OpenRouter key:
- https://openrouter.ai/workspaces/default/keys

## 2. Install Dependencies

```bash
pip install -r requirements.txt
```

## 3. Run Application

```bash
python app.py
```


# Week3
