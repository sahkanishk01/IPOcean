# IPOcean – IPO Data & Analytics Platform
IPOcean is a web application designed to provide users with real-time IPO listings, analytics, and insights. Built with Django REST Framework for the backend and PostgreSQL for data management, it offers a seamless experience for tracking IPO timelines, company profiles, subscription data, and market statistics.

## 🚀Features
Real-Time IPO Listings – View active, upcoming, and closed IPOs.

Detailed Company Profiles – Access key financials and company background.

Subscription Data & Analytics – Track subscription ratios and investor interest.

Search & Filter – Find IPOs by date, sector, or subscription status.

Optimized Performance – Indexed database queries for faster response times.

## 🛠 Tech Stack
Backend: Django 5.0.6, Django REST Framework 3.15.1
Database: PostgreSQL
Frontend: HTML, CSS, JavaScript
Version Control: Git, GitHub
Deployment: Vercel / Localhost

## 📂 Project Structure
```bash
IPOcean/
│── backend/         # Django backend files & API logic
│── frontend/        # Static HTML, CSS, JS files
│── requirements.txt # Python dependencies
│── README.md        # Project documentation
```

## ⚙ Installation & Setup
Clone the repository

```bash
Copy
Edit
git clone https://github.com/yourusername/IPOcean.git
cd IPOcean
```

## Create a virtual environment & activate it

```bash
Copy
Edit
python -m venv venv  
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

## Install dependencies

```bash
Copy
Edit
pip install -r requirements.txt
```
## Configure database settings in settings.py.

## Run migrations

```bash
Copy
Edit
python manage.py migrate
```
## Start the server

```bash
Copy
Edit
python manage.py runserver
```
## 📊 Usage
Open the application in your browser at http://127.0.0.1:8000/.

Browse IPO listings, filter results, and explore company details.

## 📜 License
This project is licensed under the MIT License.

