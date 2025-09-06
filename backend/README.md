# Backend


## Current status

The backend is set up as a minimal FastAPI application. It includes:

- A health check endpoint at `/health` (returns `{ "status": "ok" }`)
- Connection to a PostgreSQL database using SQLAlchemy
- Alembic for database migrations (initialised, no migrations yet)
- Environment variable configuration via `.env` (see `.env.example`)

### Running the backend

1. Install dependencies from `requirements.txt` (preferably in a virtual environment).
2. Ensure PostgreSQL is running (see infrastructure/docker-compose.yml).
3. Start the app with:
	```bash
	uvicorn main:app --reload
	```
4. Visit [http://localhost:8000/health](http://localhost:8000/health) to check the health endpoint.

### What it does

- Provides a basic FastAPI server ready for feature development
- Connects to PostgreSQL (connection string in `.env`)
- Alembic is set up for future migrations

---
Further features and endpoints will be added as development progresses.
