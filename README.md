# PythonProject

project/
├── app.py               # Main Flask application
├── models.py            # SQLAlchemy database models
├── forms.py             # WTForms classes for input validation
├── templates/           # HTML templates (Jinja2)
│   ├── layout.html
│   ├── login.html
│   ├── dashboard.html
│   ├── group.html
├── static/
│   ├── style.css        # Custom styles
│   ├── script.js        # Frontend JS for alerts and charts
├── helpers.py           # Utility functions
├── requirements.txt     # Required Python packages
├── README.md            # Project documentation
└── database.db          # SQLite database (local)
````

---

## Design Choices

* **SQLite** was chosen for its simplicity during development. It can be replaced with PostgreSQL or MySQL for deployment.
* **Chart.js** was selected for rendering clean and interactive graphs on the frontend.
* **Bootstrap** allows quick creation of a mobile-friendly UI.
* We used **Flask's session management and Flask-Login** to manage user sessions securely.

---

## Future Improvements

* Mobile app version (React Native or Flutter)
* Email reminders for deadlines
* Gamification (badges for task completion streaks)
* Study session timer (Pomodoro method)

---

## Citation

This project uses:

* Flask (MIT License)
* Chart.js (MIT License)
* Bootstrap (MIT License)
* OpenAI's ChatGPT was consulted for brainstorming and code snippets (properly cited in relevant files).

---

## Author

* Name: Muthuswamy
* GitHub: https://github.com/MuthuswamyNadar
* City/Country: Mumbai India
