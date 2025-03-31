# 🚀 FastAPI MongoDB Project

A minimal FastAPI application connected to MongoDB, with basic CRUD APIs and test coverage.

## 📁 Project Structure

```
.
├── __pycache__/           # Compiled Python bytecode
├── venv/                  # Virtual environment (excluded by .gitignore)
├── .gitignore             # Git ignore file
├── db.py                  # MongoDB connection configuration
├── main.py                # FastAPI routes and app setup
├── requirements.txt       # Python dependencies
├── test_api.py            # Basic API tests using requests
```

## 🧰 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

### Dependencies:

- `fastapi` – Web framework for building APIs
- `uvicorn` – ASGI server for FastAPI
- `pymongo` – MongoDB Python driver

## ⚙️ How to Run

Start the development server using:

```bash
uvicorn main:app --reload
```

Visit the interactive docs at:  
👉 http://127.0.0.1:8000/docs

## 🧠 MongoDB Setup

- Edit `db.py` to configure your MongoDB URI and database name.
- Ensure MongoDB is running locally or provide a valid cloud connection string.

## ✅ Running Tests

Tests are written in `test_api.py` using the `requests` library.

Run tests with:

```bash
python test_api.py
```

## 📄 .gitignore

This project excludes the following from version control:

```
__pycache__/
venv/
```
