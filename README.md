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

### Prerequisites
- Python 3.10+
- Node.js & npm
- MySQL Server

---

### 1. Backend Setup (Django)

Navigate to the `Backend` directory and start the server:

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
