Budget Tracker

A simple and efficient application designed to help you manage your finances effectively. With the Budget Tracker, you can record expenses, categorize them, set budget goals, and track your spending habits over time. Whether you're saving for a big purchase or managing monthly bills, this tool makes budgeting easy and intuitive.

Features

Expense and Income Tracking: Log your transactions with detailed descriptions and amounts.
Category Management: Organize your transactions into categories like food, entertainment, and utilities.
Budget Goals: Define monthly or yearly budgets and track your progress.
Analytics and Insights: Visualize your spending habits with graphs and charts.
User Authentication: Securely log in and manage your personal budget data.

Installation Guide

Prerequisites:

Python (version 3.8 or later)
virtualenv (recommended for isolating dependencies)
A database system (e.g., SQLite, PostgreSQL)

Steps
1.Clone the Repository

Clone the project repository to your local machine:
git clone https://github.com/karanrai13/budget_tracker.git
cd budget-tracker

2.Create a Virtual Environment
python -m venv venv

3.Activate the Virtual Environment

On Windows:
venv\Scripts\activate

On macOS/Linux:
source venv/bin/activate

4.Install Dependencies
pip install -r requirements.txt

5.Apply Migrations
python manage.py makemigrations
python manage.py migrate

6.Create a Superuser
Create an admin account to access the Django Admin interface:

python manage.py createsuperuser

7.Run the Development Server
python manage.py runserver

8.Access the Application

Open your browser and navigate to:
http://127.0.0.1:8000/

for admin panel -> http://127.0.0.1:8000/admin/


