# Social Media Website

## Features
- User authentication (login, logout)
- Profile management
- Post creation, editing, and deletion
- Like and comment functionality

## Running locally
0. Make sure python is installed locally
1. Clone the repository
   ```bash
    git clone https://github.com/Avirat2211/Social-Media-Website.git
    cd social-media-website
   ```

2. Create a virtual environment and activate it
   ```bash
   python -m venv venv
   source venv/bin/activate
   ```
3. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```
4. Apply Migrations
   ```bash
   python manage.py migrate
   ```

5. Create a superuser
   ```bash
   python manage.py createsuperuser
   ```
6. Run the server
   ```bash
   python manage.py runserver
   ```
7. Open in Browser


   
