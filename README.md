# TodoApp

A simple Todo application built with FastAPI and SQLite.

## Features
- User authentication (login/register)
- Create, read, update, and delete todos
- RESTful API endpoints

## Project Structure
```
├── main.py          # FastAPI app entry point
├── models.py        # SQLAlchemy models
├── database.py      # Database setup
├── routers/         # API routers (auth, todos)
├── requirements.txt # Python dependencies
├── todosapp.db      # SQLite database file
```

## Setup & Installation
1. **Clone the repository**
2. **Install dependencies**
   ```powershell
   pip install -r requirements.txt
   ```
3. **Run the application**
   ```powershell
   uvicorn main:app --reload
   ```
4. **Access the API docs**
   Open [http://localhost:8000/docs](http://localhost:8000/docs) in your browser.

## API Endpoints
- `/auth` - User authentication
- `/todos` - Todo management

## License
MIT
