## How the quiz works

New users must pass a 5-question quiz (60% or more) before registering.
The score decides the profile badge: Gold (90+), Silver (75+), Bronze (60+).

## How to run locally

1. Clone the repository and open the project folder.
2. Create and activate a virtual environment:
   - `python -m venv venv`
   - Windows (Git Bash): `source venv/Scripts/activate`
   - Windows (Command Prompt): `venv\Scripts\activate`
3. Install dependencies: `pip install -r requirements.txt`
4. Apply migrations: `python manage.py migrate`
5. Create an admin account: `python manage.py createsuperuser`
6. Start the server: `python manage.py runserver`, then open http://127.0.0.1:8000