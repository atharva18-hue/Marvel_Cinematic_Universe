
#  Marvel Cinematic Universe Django Project  


Dive into an immersive Marvel Cinematic Universe (MCU) experience with this Django-powered web application!
This project unifies every superhero , blockbuster movie , chronological timeline , and fan-created story  into one dynamic platform.
Designed for MCU enthusiasts and developers alike, it delivers a seamless, interactive journey through the Marvel Universe — combining powerful backend logic with a sleek, responsive UI.

------------------------------------------------------------------------------------------------

##  Project Overview

This project allows you to:

- **Character Management:** Add, view, and manage Marvel superheroes and villains. Full CRUD functionality for complete control.
- **Movie Database:** Track all MCU movies in chronological or release order.
- **Fan Stories & Content:** Users can submit fan stories and interact with existing stories.
- **Search & Explore:** Quickly find movies or superheroes using the smart search bar.
- **Interactive Timelines:** Understand MCU chronology easily through organized timelines.
- **Templates & Views:** Clean HTML templates with responsive pages and smooth UI experience.

------------------------------------------------------------------------------------------------
## Project Video

https://github.com/user-attachments/assets/3ce0565a-925d-4475-a0c4-faec1a705532

------------------------------

##  Tech Stack

| Layer            | Technology                    |
|-----------------|-------------------------------|
| **Backend**      | Python, Django               |
| **Frontend**     | HTML, CSS, Django Templates  |
| **Database**     | SQLite3                       |
| **Version Control** | Git & GitHub                |
| **Deployment**   | Localhost / Django server     |

-------------------------------------------------------------------------------------------

##  Project Structure

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

------------------------------------------------------------------------------------------------

##  Installation & Setup

1. **Clone the repository:**
git clone https://github.com/atharva18-hue/Marvel_Cinematic_Universe.git
cd Marvel_Cinematic_Universe

------------------------------------------------------------------------------------------------

## Create a virtual environment:
python -m venv env

------------------------------------------------------------------------------------------------

## Activate environment:
env\Scripts\activate

------------------------------------------------------------------------------------------------

## Install dependencies:
pip install -r requirements.txt

------------------------------------------------------------------------------------------------

## Run migrations:
python manage.py migrate

------------------------------------------------------------------------------------------------

## Start the development server:
python manage.py runserver

------------------------------------------------------------------------------------------------

## Open in browser:
http://127.0.0.1:8000/

------------------------------------------------------------------------------------------------
## Usage
Navigate through the homepage to explore MCU movies and characters.

Use the search bar to find movies or superheroes quickly.

Add new fan stories and explore existing ones.

View MCU chronological timelines with proper movie order.

------------------------------------------------------------------------------------------------

 ## Author
Atharva Chavhan
GitHub: atharva18-hue
Passionate about Django, Python, and web projects.

------------------------------------------------------------------------------------------------

##  Acknowledgements
Inspired by the Marvel Cinematic Universe (MCU)

Built with Django Framework

Special thanks to the Django community for excellent documentation

------------------------------------------------------------------------------------------------
