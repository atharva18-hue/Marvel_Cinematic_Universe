\# 🌌 Marvel Cinematic Universe Django Project



A \*\*Django-powered web application\*\* inspired by the \*\*Marvel Cinematic Universe (MCU)\*\*.  

This platform unites \*\*Marvel characters 🦸‍♂️, movies 🎬, and timelines 📅\*\* into one interactive system — designed for exploration, learning, and data management.



----------------------------------------------------------------



\## 📝 Overview



\- \*\*Character Management:\*\*  

&nbsp; Add, view, and manage Marvel superheroes and villains.



\- \*\*Movie Database:\*\*  

&nbsp; Track all MCU movies in chronological order or release order.



\- \*\*Fan Stories \& Content:\*\*  

&nbsp; Users can submit fan stories and interact with existing content.



\- \*\*Search \& Explore:\*\*  

&nbsp; Find movies or superheroes quickly using the search system.



\- \*\*Interactive Timelines:\*\*  

&nbsp; Understand MCU chronology easily with organized timelines.



\- \*\*Templates \& Views:\*\*  

&nbsp; Clean HTML templates for smooth navigation and a user-friendly interface.



----------------------------------------------------------------



\## 🛠 Tech Stack



| Layer             | Technology                  |

|------------------|-----------------------------|

| \*\*Backend\*\*       | Python, Django             |

| \*\*Frontend\*\*      | HTML, CSS, Django Templates|

| \*\*Database\*\*      | SQLite3                    |

| \*\*Version Control\*\* | Git \& GitHub             |

| \*\*Deployment\*\*    | Localhost / Django server  |



----------------------------------------------------------------



\## 📂 Project Structure



MCU\_Django\_Project/

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

│ └── ... others

│

├── db.sqlite3 # SQLite Database

├── manage.py # Django management script

└── README.md # Project documentation



----------------------------------------------------------------



\## ⚡ Installation \& Setup



1\. \*\*Clone the repository:\*\*

```bash

git clone https://github.com/atharva18-hue/Marvel\_Cinematic\_Universe.git

cd Marvel\_Cinematic\_Universe

Create a virtual environment:



bash

Copy code

python -m venv env

source env/bin/activate   # Linux / Mac

env\\Scripts\\activate      # Windows

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



----------------------------------------------------------------



🎯 Usage

Navigate through the homepage to explore MCU movies and characters.



Use the search bar to quickly find movies or superheroes.



Add new fan stories and view existing stories.



Explore the MCU timeline with chronological movie order.



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



