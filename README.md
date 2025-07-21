# TaskBridge

### Overview

TaskBridge is a full-stack task management application developed with a Django REST Framework (DRF) backend and an Angular frontend. The application allows users to create, update, delete, and track their to-do items efficiently, providing a smooth and responsive user experience.

# Features
 ### Backend (Django REST Framework)
- *RESTful API*: Provides secure and scalable APIs for managing tasks, users, and authentication.
- *Modular Structure*: Built with reusable Django apps and clean separation of concerns.
- *Database Integration*:  Connects with a relational database (e.g., PostgreSQL or SQLite) to persist task data and user accounts.
- *Token-Based Authentication*: Implements JWT or session-based login for secure access.
- *Admin Interface*: Django admin panel available for managing data and users easily.
 ### Frontend (React.js)
- *Modern UI*: Developed with Angular to provide a responsive, single-page experience.
- *Form Handling*: Users can add, edit, and delete tasks using reactive Angular forms.
- *API Integration*: Communicates with the backend using Angular’s HttpClient to fetch, create, and manage tasks.
- *Routing & Navigation*: Built-in Angular Router for smooth navigation across different app views.
- *Authentication Support*: Frontend includes user login and token-based session handling.

#  Installation

 ### Backend
# Clone the repository
git clone https://github.com/lbibired/TaskBridge.git

# Navigate to backend directory
cd taskbridge/backend

# Create virtual environment and activate it
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start the development server
python manage.py runserver


 ### Frontend
# Navigate to frontend directory
cd ../frontend

# Install dependencies
npm install

# Start the development server
npm start
