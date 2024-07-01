# FastAPI based Todo Application

Todo application built using FastAPI, PostgreSQL for database management, and JWT for authentication.

## Setup

1. **Clone the repository:**
   ```
   git clone https://github.com/tahzeer/fastapi-todo-app.git
   cd fastapi-todo-app
   ```

2. **Install dependencies:**
   ```
   pip install -r requirements.txt
   ```

3. **Database Setup:**
   - Ensure PostgreSQL is installed locally.
   - Update database configuration in `database.py`:
     - Change `POSTGRES_DATABASE_URL` in `database.py` to your local PostgreSQL URL.

     ```python
     # Example:
     # POSTGRES_DATABASE_URL = "postgresql://username:password@localhost/dbname"
     POSTGRES_DATABASE_URL = "postgresql://your_username:your_password@localhost/your_dbname"
     ```

4. **Run the application:**
   ```
   uvicorn main:app --reload
   ```

5. **Access the API:**
   - Open your browser and go to `http://localhost:8000/docs` to view and interact with the API using Swagger UI.

## Usage

- Use Swagger UI (`/docs`) or import the provided Postman collection (`FastAPI_Todo_App.postman_collection.json`) to explore and test the API endpoints.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
