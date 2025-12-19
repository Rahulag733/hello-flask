# Hello Flask - My First Python Web App

## What's This Project About?

This is my first web application built with Flask! It's a simple project, but it helped me understand how Python can be used to create web applications. Coming from learning Python basics, seeing my code actually run in a browser was pretty exciting!

## Why Flask?

I chose Flask because:
- It's lightweight and beginner-friendly
- Perfect for learning web development concepts
- Popular in the Python community
- Great documentation and lots of tutorials

## What Does It Do?

This is a basic Flask app that:
- Runs a local web server
- Displays a welcome page
- Shows what I'm learning about Flask
- Demonstrates routing and templates

## Technologies I'm Using

- **Python 3.x** - The programming language
- **Flask** - The web framework
- **HTML/CSS** - For the frontend
- **Jinja2** - Flask's templating engine

## Project Structure

```
hello-flask/
├── app.py                 # Main Flask application
├── templates/            # HTML templates
│   └── index.html       # Homepage template
├── static/              # CSS, JS, images (to be added)
│   └── style.css       # Styling
└── README.md           # You're here!
```

## How to Run This

### Prerequisites
You need Python installed on your computer. Check if you have it:
```bash
python --version
```

### Step 1: Clone the Repository
```bash
git clone https://github.com/Rahulag733/hello-flask.git
cd hello-flask
```

### Step 2: Install Flask
```bash
pip install flask
```

### Step 3: Run the App
```bash
python app.py
```

### Step 4: Open in Browser
Go to: `http://127.0.0.1:5000/`

And you should see my Hello Flask page!

## What I Learned

Building this project taught me:
- How Flask routing works (`@app.route`)
- Using templates with Jinja2
- Rendering HTML pages from Python
- Project structure for Flask apps
- Running a local development server

## Challenges I Faced

1. **Understanding routing** - At first, I didn't get how URLs mapped to functions
2. **Template syntax** - Jinja2's `{{ }}` and `{% %}` took some getting used to
3. **Static files** - Learning where to put CSS and how to link it
4. **Debug mode** - Figuring out why things broke (debug mode is awesome!)

## What's Next?

I want to expand this project by:
- Adding more routes and pages
- Creating a contact form
- Connecting to a database
- Adding user authentication
- Deploying it online!
- Learning about Flask blueprints

## Quick Flask Concepts

### Basic Flask App
```python
from flask import Flask, render_template

app = Flask(__name__)

@app.route('/')
def home():
    return render_template('index.html')

if __name__ == '__main__':
    app.run(debug=True)
```

### What This Does:
- `Flask(__name__)` creates the application
- `@app.route('/')` defines the URL
- `render_template()` renders HTML files
- `debug=True` enables auto-reload

## Useful Commands

```bash
# Install Flask
pip install flask

# Run the app
python app.py

# Run with specific host/port
python app.py --host=0.0.0.0 --port=8080
```

## Resources That Helped Me

- [Flask Official Documentation](https://flask.palletsprojects.com/)
- [Flask Mega-Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)
- YouTube tutorials on Flask basics
- Stack Overflow (obviously!)

## About Me

**Rahul A G**  
Final Year B.E. Computer Science Student  
Alvas Institute of Engineering and Technology, Mangalore

I'm exploring web development and learning how to build full-stack applications. This Flask project is one of my first steps into backend development!

Connect with me on [GitHub](https://github.com/Rahulag733)

## Want to Contribute?

Feel free to fork this repo and experiment! If you have suggestions for improvements or find any issues, let me know.

## License

Free to use for learning purposes. This is a beginner project, so use it however you want!

---

*Started learning Flask on [date] - This is just the beginning of my web dev journey!*
