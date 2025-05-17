# 📚 FastAPI for Book Management
A simple FastAPI project for managing books with full CRUD operations using Pydantic for validation.

## 🚀 Features

- Add a new book
- View all books
- Get a book by ID
- Filter books by rating or published year
- Update book details
- Delete a book

## 📦 Tech Stack

- [FastAPI](https://fastapi.tiangolo.com/)
- [Pydantic](https://docs.pydantic.dev/)
- [Uvicorn](https://www.uvicorn.org/) (for running the server)

## ▶️ How to Run

```bash
# Install dependencies
pip install fastapi uvicorn

# Run the app
uvicorn books:app --reload
