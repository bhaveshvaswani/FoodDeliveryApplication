# EATIN

An online food ordering web application similar to Zomato/UberEats built with React and Django.


---

## Features
- User signup with optional seller onboarding.
- Login through mobile number and OTP.
- Browse restaurants, add food items to the cart, and make test payments.
- Restaurants can list, add, edit, and delete food items.
- Simple admin page for restaurant management.

## Technical Features
- Backend built with Django and Django REST Framework (DRF).
- Frontend developed using ReactJS.
- JWT authentication for secure login and signup.
- AWS S3 for static file storage.
- PostgreSQL used as the production database.

---

## Installation

### Setup Backend
1. **Download Python**: [Python Downloads](https://www.python.org/downloads/)
2. Navigate to the backend directory:
   ```bash
   cd backend
   ```
3. Rename `example.env` to `.env` and add the necessary environment variables.
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Migrate the database:
   ```bash
   python manage.py migrate
   ```
6. Start the server:
   ```bash
   python manage.py runserver
   ```
7. Add a Restaurant Group in the admin panel:
   - Access Django's admin panel.
   - Log in with superuser credentials.
   - Go to Groups -> Add Group and enter the appropriate details.

### Setup Frontend
1. **Download NodeJS**: [NodeJS Downloads](https://nodejs.org/en/download/)
2. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
3. Rename `example.env` to `.env`.
4. Install dependencies:
   ```bash
   npm install
   ```
5. Start the server:
   ```bash
   npm start
   ```
