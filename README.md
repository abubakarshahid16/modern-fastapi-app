# My Full Stack Project

This is a modern full-stack web application built with FastAPI (Backend) and React (Frontend).

## 🚀 Tech Stack

- **Backend:** FastAPI, PostgreSQL, SQLModel, Pydantic
- **Frontend:** React, Vite, TypeScript, Tailwind CSS, TanStack Router
- **Database:** PostgreSQL
- **DevOps:** Docker Compose

## 🛠️ Getting Started

To get the project running locally, follow these steps.

### Prerequisites

- Docker & Docker Compose
- Node.js (for frontend local dev without Docker)
- Python 3.10+ (for backend local dev without Docker)

### Running with Docker (Recommended)

1. Clone the repository.
2. Create `.env` file from the example (if applicable) or use provided scripts.
3. Run the development environment:

```bash
docker compose up -d
```

Access the frontend at `http://localhost:5173` and the backend docs at `http://localhost:8000/docs`.

## 📂 Project Structure

- `backend/`: FastAPI application code.
- `frontend/`: React application code.
- `scripts/`: Helper scripts for development and deployment.

## 📄 License

This project is licensed under the MIT License.

---
*Based on [Full Stack FastAPI Template](https://github.com/fastapi/full-stack-fastapi-template)*
