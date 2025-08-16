# Social Media App (Django, TailwindCSS)

A responsive and interactive social media platform built using **Django** for backend logic and **TailwindCSS** for modern, utility-first styling. The app allows users to post content, follow others, and interact through likes and comments.

---

## ✨ Features

- 🔐 User authentication (signup, login, logout)
- 📸 Create posts with captions and images
- ❤️ Like/unlike posts in real-time
- 💬 Comment on posts
- 👥 Follow/unfollow users
- 📰 Personalized feed and public explore page
- 🎨 Fully responsive TailwindCSS UI

---

## 🛠 Tech Stack

- **Backend:** Django 5.x, Python 3.x  
- **Frontend:** TailwindCSS, HTML, Django Templates  
- **Database:** SQLite (dev), PostgreSQL (prod)  
- **Media Storage:** Local (dev), optional AWS S3 for production  
- **Auth:** Django built-in auth system  

---

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/<SANK-0311>/<Social-Media-App-Django-TailwindCSS>.git
cd <Social-Media-App-Django-TailwindCSS>

# Create and activate virtual environment
python -m venv env
source env/bin/activate  # or env\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Apply database migrations
python manage.py migrate

# Create a superuser (optional)
python manage.py createsuperuser

# Run Tailwind (in separate terminal)
npm install
npx tailwindcss -i ./static/input.css -o ./static/css/style.css --watch

# Start the development server
python manage.py runserver
