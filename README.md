# GLAB-370.4.2-Setup-BasicApp-in-Flask

## Welcome to the "Flask Magician: Setting Up a Basic Flask App" Guided Lab! 🚀

In this 30-minute guided lab, we'll embark on an exciting coding adventure to set up a **basic Flask application** and get it running. Get ready to unleash the power of Flask and witness your application come to life!

### Prerequisites

Before we begin, make sure you have the following:

- Flask installed (if not, run `pip install flask` in your terminal).
- Basic knowledge of Python syntax.
- A Python interpreter or an integrated development environment (IDE) installed on your machine.

### Table of Contents

- [Step 1: Introduction](#step-1-introduction)
- [Step 2: Setting Up the Flask App](#step-2-setting-up-the-flask-app)
- [Step 3: Defining Routes and Views](#step-3-defining-routes-and-views)
- [Step 4: Running the Flask App](#step-4-running-the-flask-app)
- [Step 5: Challenge](#step-5-challenge)
- [Step 6: Conclusion](#step-6-conclusion)

### Step 1: Introduction

Let's begin our adventure into the world of Flask by setting up a **basic Flask application**. Flask is a lightweight web framework that allows us to build web applications in Python. In this lab, we'll set up a simple Flask app and get it up and running.

### Step 2: Setting Up the Flask App

To start, create a new directory for your Flask app. Navigate to the directory using your terminal or IDE.

### Step 3: Defining Routes and Views

In Flask, routes define the URLs that our application will respond to, and views are the functions that handle the requests and generate the responses. Let's create a basic Flask app with a single route and view.

Create a Python file, e.g., `app.py`, and add the following code:

```python
from flask import Flask

app = Flask(__name__)

@app.route("/")
def home():
    return "Welcome to my Flask app!"

if __name__ == "__main__":
    app.run()
```

In this code, we import Flask, create an instance of the Flask app, and define a route `/` with a corresponding view function `home()` that returns a simple greeting message.

### Step 4: Running the Flask App

To run your Flask app, open your terminal or command prompt, navigate to the directory where `app.py` is located, and run the following command:

```
python app.py
```

You should see output similar to the following:

```
* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```

This means your Flask app is now running! Open your web browser and navigate to `http://127.0.0.1:5000/` or `http://localhost:5000/`, and you should see the welcome message from your Flask app.

### Step 5: Challenge

Now it's time for an exciting challenge! Customize your Flask app by adding additional routes and view functions. Experiment with different Flask features, such as rendering HTML templates, handling form submissions, or connecting to a database. Make your Flask app come alive with your creativity!

### Step 6: Conclusion

Congratulations on completing the "Flask Magician: Setting Up a Basic Flask App" Guided Lab! You've successfully set up a basic Flask application and learned how to define routes, views, and run the app.

Remember to keep exploring Flask's documentation and experimenting with different features and functionalities. Flask offers a rich ecosystem of extensions and libraries that can enhance

 your web application development experience.

Feel free to reach out if you have any questions. Happy coding, and may your Flask apps bring joy to the web! 🎉
