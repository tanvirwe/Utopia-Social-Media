# Local setup

1. Clone the repository: `git clone https://github.com/tanvirwe/Utopia-Social-Media.git`
2. Create a virtual environment: `python -m venv venv`
3. Activate it:
   - Git Bash: `source venv/Scripts/activate`
   - Command Prompt: `venv\Scripts\activate`
4. Install dependencies: `pip install -r requirements.txt`
5. Apply migrations: `python manage.py migrate`
6. Create an admin account: `python manage.py createsuperuser`
7. Start the server: `python manage.py runserver`
8. Open http://127.0.0.1:8000

The project uses SQLite, so no database server is needed.