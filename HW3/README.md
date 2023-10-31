This project is a homework assignment for CSCI3700. Its purpose is to use Flask, PostgreSQL, and HTML to access a database and display it as a website. It will also update a table when opening the "/api/update_basket_a" route, and will display unique entries when opening the "/api/unique" route. 

## Quick Start
### Local Test Setup
First, we need to install a Python 3 virtual environment with:
```
sudo apt-get install python3-venv
```

Create a virtual environment:
```
python3 -m venv python_venv
```

You need to activate the virtual environment when you want to use it:
```
source python_venv/bin/activate
```

To fufil all the requirements for the python server, you need to run:
```
pip3 install -r requirements.txt
```

Because we are now inside a virtual environment. We do not need sudo.

Then you can start the server with:
```
python3 main.py
```
