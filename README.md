<span style="color:black; font-weight:bold; font-size:36px;">🌌 Marvel Cinematic Universe Django Project</span>

A powerful Django-powered web application inspired by the Marvel Cinematic Universe (MCU).
This platform unites Marvel superheroes 🦸‍♂️, movies 🎬, timelines 📅, and fan content in one interactive system—built for exploration, learning, and data management.

----------------------------------------------------------------

📝 Project Overview

This project allows you to:

Character Management:
Add, view, and manage Marvel superheroes and villains. Full CRUD functionality for complete control.

Movie Database:
Track all MCU movies in chronological or release order. Get quick insights into the MCU timeline.

Fan Stories & Content:
Users can submit fan stories and interact with existing stories. Keep the MCU universe lively.

Search & Explore:
Quickly find movies or superheroes using the smart search bar.

Interactive Timelines:
Understand MCU chronology easily through well-organized timelines.

Templates & Views:
Clean HTML templates with intuitive navigation, responsive pages, and smooth UI experience.

----------------------------------------------------------------

🛠 Tech Stack
Layer	Technology
Backend	Python, Django
Frontend	HTML, CSS, Django Templates
Database	SQLite3
Version Control	Git & GitHub
Deployment	Localhost / Django server

----------------------------------------------------------------

📂 Project Structure
MCU_Django_Project/
│
├── Atharva/                  # Main Django app
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   ├── asgi.py
│   └── __pycache__/           # Compiled Python files (ignored in Git)
│
├── templates/                 # HTML Templates
│   ├── home.html
│   ├── addfanstory.html
│   ├── allmarvelmoviesinsequence.html
│   └── ... other templates
│
├── db.sqlite3                 # SQLite Database
├── manage.py                  # Django management script
└── README.md                  # Project documentation

----------------------------------------------------------------

⚡ Installation & Setup

Clone the repository:

git clone https://github.com/atharva18-hue/Marvel_Cinematic_Universe.git
cd Marvel_Cinematic_Universe


Create a virtual environment:

python -m venv env
# Activate environment:
# Windows
env\Scripts\activate
# Linux/Mac
source env/bin/activate


Install dependencies:

pip install -r requirements.txt


Run migrations:

python manage.py migrate


Start the development server:

python manage.py runserver


Open in browser:

http://127.0.0.1:8000/

----------------------------------------------------------------

🎯 Usage

Navigate through the homepage to explore MCU movies and characters.

Use the search bar to find movies or superheroes.

Add new fan stories and explore existing ones.

View MCU chronological timelines with movie order.

----------------------------------------------------------------

👤 Author

Atharva Chavhan
GitHub: atharva18-hue

Passionate about Django, Python, and web projects

----------------------------------------------------------------

🌟 Acknowledgements

Inspired by the Marvel Cinematic Universe (MCU)

Built with Django Framework

Special thanks to the Django community for excellent documentation
----------------------------------------------------------------


