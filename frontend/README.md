# Stock Management System

A full-stack inventory management system built with React and Django, featuring inventory management, order tracking, and user profile management.

## Features

### Inventory Management
- Complete CRUD operations for products
- Real-time stock updates
- Product filtering and search
- Product categories
- Stock level tracking
- Product details view

### Order Management
- Order creation and tracking
- Order status updates (Pending, Processing, Shipped, Delivered)
- Order filtering by status
- Order history
- Customer information tracking
- Total order value calculation

### User Profile Management
- User authentication and authorization
- Profile viewing and editing
- Personal information management
- Email updates
- Password management
- User role management

### UI/UX Features
- Responsive design
- Animated transitions using Framer Motion
- Interactive tables and forms
- Status color coding
- Real-time updates
- User-friendly interface
- Form validation
- Error handling

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14 or higher)
- Python (v3.8 or higher)
- pip (Python package manager)
- Git

## Installation

### Backend Setup (Django)

after this -> 
git clone <y>
cd <project-directory>
cd <project-directory>
2. Set Up the Back-End (Django)
Install Python Dependencies:

It's recommended to create a virtual environment to isolate your Python dependencies:

bash
Copy code
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install the necessary Python dependencies using requirements.txt:

bash
Copy code
pip install -r backend/requirements.txt
Set Up the Database:

Run the migrations to create the necessary tables in the database:
bash
Copy code
cd backend
python manage.py migrate
Create a Superuser (optional, to access the Django admin interface):

bash
Copy code
python manage.py createsuperuser
Start the Django Server:

bash
Copy code
python manage.py runserver
The back-end will now be running at http://127.0.0.1:8000.

3. Set Up the Front-End (React)
Install Node.js Dependencies:

Navigate to the front-end directory (if it's separate, e.g., frontend/):

bash
Copy code
cd frontend
Install the JavaScript dependencies using either npm or yarn:

Using npm:
bash
Copy code
npm install
Using yarn:
bash
Copy code
yarn install
Start the React Development Server:

bash
Copy code
npm start   # Or if you're using Yarn: yarn start
The front-end will now be running at http://localhost:3000.

4. Ensure Front-End Communicates with Back-End
Make sure the React app is configured to send API requests to the Django back-end running at http://127.0.0.1:8000. If the React app and Django are running on different ports, the API URLs in the React code may need to be updated to point to the back-end server.

5. You're All Set!
The back-end will be available at http://127.0.0.1:8000
The front-end will be available at http://localhost:3000
