# 🚀 Social Media (Basic) - FastAPI

A **Social Media** built from scratch using **FastAPI**, featuring a scalable and secure backend with Github Actions CI/CD pipeline integration.

## 📌 Features
- **🔗 RESTful API** with FastAPI
- **💾 Database**: PostgreSQL with SQLModel ORM
- **✅ Data Validation**: Pydantic
- **🔄 Database Migrations**: Alembic
- **🔐 Secure Endpoints**: JWT Authentication
- **🐳 Dockerized Application**
- **🛠️ Continuous Integration**: GitLab CI/CD Pipeline
- **🧪 Automated Testing**: Pytest

## 🏗️ Tech Stack
- **FastAPI** - High-performance web framework
- **SQLModel** - ORM for database interactions
- **Pydantic** - Data validation and settings management
- **Alembic** - Database migration tool
- **JWT Tokens** - Secure authentication & authorization
- **PostgreSQL** - Relational database
- **Docker** - Containerized deployment
- **Pytest** - Automated API testing
- **Github Actions CI/CD** - Continuous integration and deployment

## 🚀 Getting Started
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/RathQd/python_fastapi.git
cd python_fastapi
```

### 2️⃣ Setup Environment Variables
Create a `.env` file in the root directory and configure your database & JWT settings.
```env
DATABASE_URL= $URL$
SECRET_KEY= $KEY$
ALGORITHM= $ALGO$
ACCESS_TOKEN_EXPIRE_MINUTES= $TIME_IN_MINs$
```

#### 🖥️ Without Docker (Local Environment)
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
```

### 4️⃣ Run Migrations
```bash
alembic upgrade head
```

### 5️⃣ Run Tests
```bash
pytest already integrated with github actions CI/CD. 
```

## 📡 API Documentation
FastAPI provides interactive API docs:
- **Swagger UI**: `http://localhost:8000/docs`
- **ReDoc**: `http://localhost:8000/redoc`

## 📦 Deployment with Github actions CI/CD
This project integrates a **Github actions CI/CD pipeline** for automated testing and deployment.

## 🤝 Contributing
Contributions are welcome! Feel free to open issues or submit PRs.

---
**Star ⭐ the repo if you found it useful!**

