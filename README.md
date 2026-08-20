📊 Banele Seko — Data Science & Analytics Portfolio

A modern, responsive personal portfolio website built to showcase my data science, data analytics, software development, projects, certifications, technical skills, and professional experience.

The website uses a dark purple/cyan modern UI with interactive components, responsive layouts, project sections, analytics visualizations, and a contact/location page.

🚀 Project Overview

This portfolio was created to provide a professional online presence where I can showcase my technical capabilities and projects in Data Science, Data Analytics, ICT, and Software Development.

The site includes:

🏠 Home / Hero section
👨🏽‍💻 About Me
💼 Experience
📊 Projects
🛠️ Technical Skills
🎓 Certifications
📍 Location / Interactive Map
📧 Contact section
📄 Downloadable CV
📱 Responsive design
✨ Interactive UI elements
📈 Analytics dashboard-style visualizations
🛠️ Technologies & Tools
💻 Programming
Python
JavaScript
HTML5
CSS3
🌐 Web Development
Flask
Jinja2 Templates
Bootstrap
Bootstrap Icons

Flask is used as the backend framework, while Jinja2 is used to dynamically render HTML pages and data.

🎨 Frontend
HTML5
CSS3
JavaScript
Bootstrap
Bootstrap Icons
Responsive CSS
CSS Grid
Flexbox
CSS animations and transitions
📊 Data & Analytics

The portfolio highlights experience with:

Power BI
Microsoft Fabric
SQL
Python
Excel
Power Query
Azure
Data Analysis
Data Cleaning
Dashboard Development
Data Visualization
🗺️ Maps

The contact page uses:

Leaflet.js
OpenStreetMap

to display an interactive map showing my location in Amanzimtoti, KwaZulu-Natal, South Africa.

🏗️ Project Structure
Banele-Portfolio/
│
├── app.py
│
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── about.html
│   ├── experience.html
│   ├── projects.html
│   ├── skills.html
│   ├── certifications.html
│   └── contact.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   │
│   ├── js/
│   │   └── javascript.js
│   │
│   ├── images/
│   │   └── img.png
│   │
│   └── Banele_Seko_CV.pdf
│
├── requirements.txt
│
└── README.md
⚙️ Features
🖥️ Modern Dashboard-Inspired Homepage

The homepage uses a modern analytics-inspired design containing:

Profile introduction
Data science tagline
Technology highlights
Project CTA buttons
Analytics overview
KPI cards
Activity visualization
User engagement visualization
Dashboard-style UI

The visual design uses a combination of:

Purple
+
Cyan
+
Dark navy
+
Gradient effects
📊 Analytics Dashboard

The homepage contains a dashboard-style visualization designed to represent real-world data analytics work.

Example metrics include:

Total Users       1.02K
Total Logins      27.6K
Applications      97
Projects         10+
Certifications    6

These elements help connect the portfolio's visual design with my background in data analytics and dashboard development.

📍 Interactive Location Map

The contact page includes an interactive Leaflet map.

The map is centered around:

Amanzimtoti
KwaZulu-Natal
South Africa

The implementation uses:

Leaflet.js
OpenStreetMap
JavaScript
HTML
CSS

The map includes:

Zoom controls
Location marker
Popup information
Responsive sizing
Custom dark-themed popup styling
📄 CV Download


📧 Contact Page

The contact page provides visitors with information about:

Email
Location
GitHub
LinkedIn

It also includes a contact form allowing visitors to submit:

Name
Email
Message

The form is processed through the Flask backend.

📱 Responsive Design

The website was designed to work across different screen sizes.

Responsive layouts are implemented using CSS media queries.

Supported layouts include:

🖥️ Desktop
💻 Laptop
📱 Tablet
📱 Mobile

The navigation, cards, grids, dashboard and map automatically adapt to smaller screens.

🎨 Design

The portfolio uses a modern dark technology aesthetic.

Primary colors
Background:     #020812
Dark Purple:    #10051C
Cyan:           #00D9FF
Purple:         #7C3AED
Pink:           #EC4899
White:          #F5F7FA
Muted Text:     #91A4B8

The interface uses:

Gradient backgrounds
Glass-style cards
Glowing borders
Cyan highlights
Purple accents
Responsive grids
Hover effects
Dashboard components
🐍 Flask Backend

The application is powered by Flask, providing routing between the different portfolio pages.

Example routes:

@app.route("/")
def home():
    return render_template("index.html")




@app.route("/about")
def about():
    return render_template("about.html")




@app.route("/projects")
def projects():
    return render_template("projects.html")




@app.route("/contact", methods=["GET", "POST"])
def contact():
    ...

Jinja2 template inheritance is used to maintain a common layout.

For example:

{% extends "base.html" %}


{% block content %}


<!-- Page content -->


{% endblock %}

This allows the navbar, footer and other shared components to remain consistent across the website.

📦 Installation

Clone the project:

git clone https://github.com/BaneleSeko/your-repository-name.git

Navigate into the project:

cd your-repository-name

Create a virtual environment:

python -m venv venv

Activate it on Windows:

venv\Scripts\activate

Install the required packages:

pip install -r requirements.txt

Run the application:

python app.py

Then open:

http://127.0.0.1:5000
📋 Requirements

Example requirements.txt:

Flask

Additional frontend libraries are loaded through CDN where required, including:

Bootstrap
Bootstrap Icons
Leaflet.js
📊 Data & Analytics Projects

The portfolio showcases projects involving technologies such as:

Power BI
Dashboard development
KPI reporting
Data visualization
Business intelligence
Interactive reports
Microsoft Fabric
Lakehouse architecture
Data analytics
Data engineering concepts
Bronze / Silver / Gold architecture
Fabric analytics
Python
Data analysis
Data cleaning
Data processing
Visualization
Analytics automation
SQL
Data querying
Aggregations
Filtering
Data analysis
Database management
🎓 Certifications

The portfolio also showcases Microsoft and other professional certifications related to:

Microsoft Fabric
Power BI
Azure
Data Analytics
Data Science
🔐 Security & Data Considerations

The portfolio does not expose confidential organizational data.

Projects and dashboard examples are presented for demonstration and portfolio purposes while respecting organizational data and information-security requirements.

🎯 Purpose

The main purpose of this project is to demonstrate my ability to combine:

Software Development
        +
Data Analytics
        +
Data Science
        +
Business Intelligence
        +
Modern Web Development

into a professional technology portfolio.

👨🏽‍💻 About Me

I am an ICT Graduate specializing in Data Science and Data Analytics, with a background in Application Development and experience working with data, analytics, dashboards and Microsoft technologies.

My technical interests include:

Python
SQL
Power BI
Microsoft Fabric
Azure
Data Analytics
Data Science
Software Development

I enjoy using technology and data to transform raw information into meaningful insights and practical solutions.

📌 Future Improvements

Planned improvements may include:

 Blog section
 Project filtering
 GitHub API integration
 Live Power BI embeds
 More data visualizations
 Dark/light theme switcher
 Improved contact form backend
 Email notifications
 Admin dashboard
 Database integration
 Deployment to a cloud platform
📜 License

This project is primarily a personal portfolio and is intended to showcase my skills, experience and projects.

© 2026 Banele Seko. All rights reserved.

⭐ Built With
Python
Flask
Jinja2
HTML5
CSS3
JavaScript
Bootstrap
Bootstrap Icons
Leaflet.js
OpenStreetMap
Power BI
Microsoft Fabric
SQL
Azure

Built with Python, data, analytics and a lot of curiosity. 🚀
