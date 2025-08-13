# Portfolio Website with Flask
## Overview
This is a personal portfolio website built using Python, Flask, HTML, and CSS. It showcases personal information, skills, and projects, and includes a Contact Me form.
## Features
- Homepage with profile picture, about section, and list of projects.
- Contact form for visitors to send messages.
- Responsive design with custom CSS styling.
- Uses Flask templates (Jinja2) for rendering HTML pages.
## Tech Stack
- Backend: Python (Flask)
- Frontend: HTML, CSS (Custom Styling)
- Templating: Jinja2
- Routing: Flask Routes
## Project Structure
portfolio_flask/
│
├── app.py
├── requirements.txt
├── templates/
│   ├── index.html
│   ├── contact.html
│   └── success.html
├── static/
│   ├── style.css
│   └── profile.jpg
## Installation & Setup
1. Clone the Repository  
git clone <your-repo-url>  
cd portfolio_flask  
2. Install Dependencies  
pip install -r requirements.txt  
3. Run the Application  
python app.py  
4. Open in Browser  
http://127.0.0.1:5000  
## Usage
- Go to the homepage to view profile and projects.
- Click Contact Me to send a message (messages are printed in the terminal for now).
## Customization
- Profile Picture: Replace static/profile.jpg with your own image.
- Name & Info: Edit templates/index.html.
- Colors & Styles: Modify static/style.css.
## Future Improvements
- Store contact form submissions in a database (SQLite).
- Add email notifications using Flask-Mail.
- Make site fully responsive with Bootstrap or Tailwind CSS.
## License
This project is open source under the MIT License.
