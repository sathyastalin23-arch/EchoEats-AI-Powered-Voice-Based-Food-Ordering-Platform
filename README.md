# EchoEats - AI-Powered Voice-Based Food Ordering System

EchoEats is a full-stack food ordering platform featuring a voice recognition assistant. Users can seamlessly browse menus, manage their cart, and place food orders using voice commands or traditional web interaction.

---

## 🚀 Tech Stack

- **Frontend:** React.js, HTML5, CSS3, JavaScript (ES6+)
- **Backend:** Django, Python 3.x
- **Database:** MySQL
- **Integrations:** Voice Recognition API, Razorpay Payment Gateway, OpenAI

---

## 🛠️ Getting Started

Follow these instructions to set up and run the application on your local machine.

### C0MMANDS TO RUN BACKEND

- python -m venv venv (to  create virtual environment)
- venv\Scripts\activate (to active virtual environment)
- pip install django
- pip install razorpay
- pip install openai
- pip install django-cors-header
- pip install mysqlclient
- python manage.py runserver

### Prerequisites
- Python 3.10+
- Node.js & npm
- MySQL Server

---

### 1. Backend Setup (Django)


```bash
# Navigate to Backend directory
cd Backend

# Activate virtual environment (Windows)
venv\Scripts\activate

# Install dependencies (if needed)
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start the Django development server
python manage.py runserver


### 2. Frontend Setup (React)

# Navigate to FrontEnd directory
cd FrontEnd

# Install dependencies
npm install

# Start React development server
npm run dev

# Plaintext

ECHO_EATS_VOICE_ASSISTANT_DJANGO/

├── Backend/          # Django server, models, views, & API endpoints
├── FrontEnd/         # React application, components, & styles
├── .gitignore        # Git ignore rules
└── README.md         # Project documentation