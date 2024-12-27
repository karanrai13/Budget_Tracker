
# **Budget Tracker**

A simple and efficient application designed to help you manage your finances effectively. With the **Budget Tracker**, you can easily log expenses, categorize them, set budget goals, and track your spending habits over time. Whether you're saving for a big purchase or managing monthly bills, this tool simplifies budgeting and gives you complete control over your finances.

---

## **Features**

- **Expense and Income Tracking**: Log your transactions with detailed descriptions and amounts.
- **Category Management**: Organize your transactions into categories like food, entertainment, and utilities.
- **Budget Goals**: Define monthly or yearly budgets and track your progress.
- **Analytics and Insights**: Visualize your spending habits with graphs and charts.
- **User Authentication**: Securely log in and manage your personal budget data.

---

## **Installation Guide**

### **Prerequisites**

- Python (version 3.8 or later)
- `virtualenv` (recommended for isolating dependencies)
- A database system (e.g., SQLite, PostgreSQL)

---

### **Steps**

1. **Clone the Repository**  
   Clone the project repository to your local machine:
   ```bash
   git clone https://github.com/karanrai13/budget_tracker.git
   cd budget_tracker
   ```

2. **Create a Virtual Environment**  
   Create a virtual environment for the project:
   ```bash
   python -m venv venv
   ```

3. **Activate the Virtual Environment**  
   Activate the virtual environment:
   - On **Windows**:
     ```bash
     venv\Scripts\activate
     ```
   - On **macOS/Linux**:
     ```bash
     source venv/bin/activate
     ```

4. **Install Dependencies**  
   Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

5. **Apply Migrations**  
   Run migrations to set up the database:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

6. **Create a Superuser**  
   Create an admin account to access the Django Admin interface:
   ```bash
   python manage.py createsuperuser
   ```

7. **Run the Development Server**  
   Start the Django development server:
   ```bash
   python manage.py runserver
   ```

8. **Access the Application**  
   Open your browser and navigate to:
   - For the main application:  
     [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
   - For the admin panel:  
     [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)

---


### **Contributions**

Feel free to fork the repository, create issues, or submit pull requests. Contributions are welcome!

---

Enjoy managing your budget effectively with the **Budget Tracker**!
