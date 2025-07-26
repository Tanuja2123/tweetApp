# 🐦 TweetApp

A Django-based web application that allows users to register, log in, and perform full CRUD operations on tweets. The project utilizes Django ORM for database operations and Jinja2 templating for dynamic frontend rendering.

## 🚀 Features

- ✅ User Registration & Login (Authentication)
- 📝 Create, Read, Update, and Delete Tweets
- 🔒 Secure user-specific tweet access and modifications
- 🎨 Responsive UI using HTML, CSS, and Bootstrap
- 🔧 Server-side form validation with Django Forms
- 🗂️ Structured using Django’s Models, Views, and Templates (MVT architecture)

## 🛠️ Tech Stack

- **Backend**: Django, Python
- **Frontend**: HTML5, CSS3, Bootstrap, Jinja2 templates
- **Database**: SQLite (default with Django)
- **Other**: Django ORM for querying and database abstraction


## 🧰 Installation

### Prerequisites

- Python 3.x
- pip
- virtualenv (optional but recommended)

### Setup

```bash
# Clone the repo
git clone https://github.com/yourusername/TweetApp.git
cd TweetApp

# Set up a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Run the development server
python manage.py runserver
