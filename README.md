📦 FastAPI MongoDB Project

A simple FastAPI application that connects to MongoDB, provides basic API endpoints, and includes tests.

Project Structure.
├── __pycache__/           # Compiled Python files
├── venv/                  # Python virtual environment
├── .gitignore             # Git ignored files
├── db.py                  # MongoDB connection setup
├── main.py                # FastAPI app and routes
├── requirements.txt       # Project dependencies
├── test_api.py            # Unit tests for API

⚙️ Requirements
Install dependencies from requirements.txt:
pip install -r requirements.txt
Dependencies include:
fastapi – Web framework
uvicorn – ASGI server to run FastAPI
pymongo – MongoDB driver for Python

🚀 Running the App
Run the FastAPI server with:
uvicorn main:app --reload
Open your browser and go to:
http://127.0.0.1:8000/docs – Swagger UI for interactive API testing

🧠 MongoDB Configuration
The MongoDB connection is configured in db.py.
Update your MongoDB URI and database name inside this file as needed.

🧪 Running Tests
To run the test cases:
python test_api.py
Tests are written using Python's requests library and verify core endpoints.

📄 .gitignore
Make sure your virtual environment and compiled files are not tracked by Git:
__pycache__/
venv/
