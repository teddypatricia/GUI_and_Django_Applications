# ProjectFolder

**Student Name:** Nabyonga Theresa   
**Date:** 08. November 2025  

This folder contains two completed projects:  

1. **django-chat-call** – A Django-based chat and call app with room management.  
2. **LoanCalculator** – A Python Tkinter-based loan calculator GUI application.  

## Features Added

### django-chat-call
- Home page listing all chat rooms.
- Room-specific pages showing messages.
- Basic user authentication (login/logout).
- Templates for index and room pages.
- Styled HTML/CSS for better UI presentation.

### LoanCalculator
- Input fields for loan amount, interest rate, and duration.
- Monthly payment calculation.
- Clear fields functionality.
- Simple, user-friendly GUI interface.

## How to Run the Django Chat & Call App

1. Open terminal/PowerShell and navigate to the `django-chat-call` folder:  
   ```bash
   cd ProjectFolder/django-chat-call
Activate the virtual environment:

powershell
Copy code
.\venv\Scripts\Activate.ps1   # PowerShell
# or
.\venv\Scripts\activate.bat   # CMD
Install dependencies (if not already installed):

bash
Copy code
pip install django
Apply database migrations:

bash
Copy code
python manage.py makemigrations
python manage.py migrate
Run the development server:

bash
Copy code
python manage.py runserver
Open your browser and go to:

cpp
Copy code
http://127.0.0.1:8000/
Login using your superuser account to access chat functionality.

How to Run the Loan Calculator
Navigate to the LoanCalculator folder:

bash
Copy code
cd ProjectFolder/LoanCalculator
Run the Python script:

bash
Copy code
python LoanCalculator.py
Enter loan details and click buttons to calculate or clear.

Notes
Make sure the virtual environment is activated before running Django.

For static files in Django, run python manage.py collectstatic if needed.

Both apps are standalone but included in the same folder for submission.

All features are tested in a local development environment.


