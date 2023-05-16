# GLAB-370.4.1-The-Enchanting-Premiere-of-FlaskMagic

## Objective:
Embark on a magical adventure as we install Flask and enter the mystical world of FlaskMagic.

## Instructions:

### Step 1: Create a Project Folder
Choose a location on your computer for your Flask project.
Create a new folder and name it "FlaskMagic."

### Step 2: Set up a Virtual Environment
- Open the command prompt or terminal on your computer.
- Navigate to the "FlaskMagic" project folder.
- Create a virtual environment by running this command:

```
python -m venv venv
```

### Step 4: Activate the Virtual Environment
Activate the virtual environment. Use the appropriate command

_powershell_
```
venv\Scripts\Activate.ps1
```

You will see the virtual environment activated.

### Step 5: Install Flask
Make sure the virtual environment is activated.
Install Flask by running this command:

```
pip install Flask
```

### Step 6: Create a Simple Flask Application
Create a new file inside the "FlaskMagic" project folder and name it "app.py."
Open "app.py" in a text editor.
Copy and paste the following code into "app.py":

```
from flask import Flask

app = Flask(__name__)

@app.route('/')
def hello_world():
    return 'Welcome to FlaskMagic!'

if __name__ == '__main__':
    app.run()
```

### Step 7: Run the Flask Application
Save the "app.py" file.
Make sure the virtual environment is still activated.
In the command prompt or terminal, run this command:

```
python app.py
```

The Flask development server will start running.

### Step 8: Submit Your FlaskMagic
- Take a screenshot or provide a description of the Flask application running on your computer.
- Submit the screenshot or description as instructed by your instructor.


Congratulations! You have successfully installed Flask, set up a virtual environment, and created a magical Flask application. Enjoy the journey into the world of FlaskMagic!
