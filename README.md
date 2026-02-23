## Django ToDo List / (authentication, CRUD, profile management, media handling)

### This is a Django ToDo application created to consolidate practical experience in working with user authentication, CRUD operations through the UI, profile management, and media file uploads

### In this project, the following were implemented:
- User authentication system: registration, login, logout
- User Profile model with avatar upload functionality
- Task model with CRUD operations: (create, read, update, delete)
- Two Django apps: accounts (user management) and todolist (task management)
- Views based on: CBV - (Class-Based Views)
- Templates for displaying: task dashboard, profile editor, authentication pages
- Media file handling for user avatars
- Custom CSS styling for responsive UI
- Static files configuration

### Screenshots
Screenshots of the application are available in the `screenshots/` folder:

| Landing Page | Task Dashboard | Task Management |
|:------------:|:--------------:|:---------------:|
| ![Landing](screenshots/01-landing-page.png) | ![Dashboard](screenshots/02-task-dashboard-empty.png) | ![Task Management](screenshots/03-task-management.png) |

| Profile Editor | User Registration | User Login | User Profile |
|:--------------:|:----------------:|:----------:|:------------:|
| ![Profile Editor](screenshots/04-profile-editor.png) | ![Registration](screenshots/05-user-registration.png) | ![Login](screenshots/06-user-login.png) | ![Profile](screenshots/07-user-profile.png) |

### Start-up instructions

1. **Clone the repository:**
    ```bash
    git clone https://github.com/KravtsovVadym/django-todo-list
    ```
    ```bash
    cd mysite
    ```
    ```bash
    python -m venv .venv
    ```
    ```bash
    source .venv/bin/activate # On Windows: .venv\Scripts\activate
    ```
    ```bash
    pip install -r requirements.txt
    ```
2. **Apply migrations:**
   ```bash
   python manage.py migrate
   ```
3. **Create Superuser(Admin)**
   ```bash
   python manage.py createsuperuser
   ```
4. **Run the development server:**
   ```bash
   python manage.py runserver
   ```
5. **Open in browser: Visit http://127.0.0.1:8000**
