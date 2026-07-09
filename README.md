# 📚 Success Journal – Academic & Lifestyle Planner

## Demo Video
https://github.com/user-attachments/assets/b125cc32-cb68-4de5-9f0c-f74fd1bf8f67

An AI-powered web application that helps students and professionals manage academic tasks while maintaining a healthy lifestyle. The platform combines productivity tools such as assignment tracking and weekly planning with wellness features like sleep, workout, and hydration tracking, all integrated into a single dashboard.

---

## 🚀 Features

### 📖 Academic Management
- Assignment Tracker
- Daily To-Do List
- Notes Management
- Weekly Planner
- CRUD operations for all academic modules

### 💪 Lifestyle Management
- Water Intake Tracker
- Sleep Tracker
- Workout Tracker
- Progress monitoring

### 🤖 AI Assistant
- Integrated Google Gemini AI chatbot
- Answers academic queries
- Provides productivity suggestions
- Offers wellness recommendations

### 🔒 Data Management
- Secure user data storage using MySQL
- CRUD functionality across all modules
- Structured relational database

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Python
- Flask

### Database
- MySQL

### AI Integration
- Google Gemini API

### Tools
- VS Code
- Git

---

## 🏗️ System Architecture

The application follows the **MVC (Model-View-Controller)** architecture.

```
User
   │
Frontend (HTML/CSS/JS)
   │
Flask Backend
   │
Business Logic
   │
MySQL Database
   │
Gemini API
```

---

## 📂 Project Structure

```
Success-Journal/
│
├── static/
│   ├── css/
│   ├── images/
│   └── js/
│
├── templates/
│   ├── index.html
│   ├── assignments.html
│   ├── notes.html
│   ├── planner.html
│   ├── sleep_tracker.html
│   ├── water_tracker.html
│   ├── workout_tracker.html
│   └── chatbot.html
│
├── app.py
├── database.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/success-journal.git

cd success-journal
```

### Create Virtual Environment

```bash
python -m venv venv
```

Activate environment

Windows

```bash
venv\Scripts\activate
```

Linux / macOS

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure MySQL

Create a MySQL database.

Update the database credentials inside the project configuration.

Example:

```python
host="localhost"
user="root"
password="your_password"
database="assignment_tracker"
```

### Add Gemini API Key

Create a `.env` file

```env
GEMINI_API_KEY=YOUR_API_KEY
```

---

## ▶️ Run the Project

```bash
python app.py
```

Open

```
http://127.0.0.1:5000
```

---

## 📊 Database Modules

The project stores data for:

- Assignments
- Notes
- Daily Tasks
- Weekly Planner
- Water Intake
- Sleep Tracker
- Workout Tracker

Each module supports:

- Create
- Read
- Update
- Delete

---

## 💡 Key Highlights

- Full-stack web application
- AI-powered chatbot using Google Gemini
- Modular Flask architecture
- Responsive user interface
- Integrated academic and wellness management
- MySQL-based persistent storage

---

## 🔮 Future Improvements

- User authentication
- Email reminders
- Google Calendar integration
- Mobile application
- Analytics dashboard
- Habit streak tracking
- Personalized AI recommendations
- Cloud deployment

