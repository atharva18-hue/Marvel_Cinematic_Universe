# 🌌 Marvel Cinematic Universe Django Project

A **powerful Django-powered web application** inspired by the **Marvel Cinematic Universe (MCU)**.  
This platform unites **superheroes 🦸‍♂️, movies 🎬, timelines 📅, and fan content** in one interactive system — built for exploration, learning, and data management.

---

## 📝 Project Overview

This project allows you to:

- **Character Management:** Add, view, and manage Marvel superheroes and villains. Full CRUD functionality for complete control.
- **Movie Database:** Track all MCU movies in chronological or release order.
- **Fan Stories & Content:** Users can submit fan stories and interact with existing stories.
- **Search & Explore:** Quickly find movies or superheroes using the smart search bar.
- **Interactive Timelines:** Understand MCU chronology easily through organized timelines.
- **Templates & Views:** Clean HTML templates with responsive pages and smooth UI experience.

---

## 🛠 Tech Stack

| Layer            | Technology                    |
|-----------------|-------------------------------|
| **Backend**      | Python, Django               |
| **Frontend**     | HTML, CSS, Django Templates  |
| **Database**     | SQLite3                       |
| **Version Control** | Git & GitHub                |
| **Deployment**   | Localhost / Django server     |

---

## 📂 Project Structure

MCU_Django_Project/
│
├── Atharva/ # Main Django app
│ ├── init.py
│ ├── settings.py
│ ├── urls.py
│ ├── wsgi.py
│ ├── asgi.py
│ └── pycache/ # Compiled Python files (ignored in Git)
│
├── templates/ # HTML Templates
│ ├── home.html
│ ├── addfanstory.html
│ ├── allmarvelmoviesinsequence.html
│ └── ... other templates
│
├── db.sqlite3 # SQLite Database
├── manage.py # Django management script
└── README.md # Project documentation

yaml
Copy code

---

## ⚡ Installation & Setup

1. **Clone the repository:**
```bash
git clone https://github.com/atharva18-hue/Marvel_Cinematic_Universe.git
cd Marvel_Cinematic_Universe
Create a virtual environment:

bash
Copy code
python -m venv env
Activate environment:

Windows:

bash
Copy code
env\Scripts\activate
Linux/Mac:

bash
Copy code
source env/bin/activate
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run migrations:

bash
Copy code
python manage.py migrate
Start the development server:

bash
Copy code
python manage.py runserver
Open in browser:

cpp
Copy code
http://127.0.0.1:8000/
🎯 Usage
Navigate through the homepage to explore MCU movies and characters.

Use the search bar to find movies or superheroes quickly.

Add new fan stories and explore existing ones.

View MCU chronological timelines with proper movie order.

👤 Author
Atharva Chavhan
GitHub: atharva18-hue
Passionate about Django, Python, and web projects.

🌟 Acknowledgements
Inspired by the Marvel Cinematic Universe (MCU)

Built with Django Framework

Special thanks to the Django community for excellent documentation
