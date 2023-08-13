# Retail Analytics

### Python Virtual Environment Setup

You can use the following instruction from the command line to set up the python virtual environment.  
1. Ensure that you have `python3`
2. Install `pip`
3. upgrade pip by doing `python3 -m pip install --upgrade pip` if necessary
4. Install Python `virtualenv` library
5. Create a Python virtual environment `venv` folder using `python3 -m virtualenv venv`
6. Activate the environment by using `source venv/bin/activate`
7. Install necessary libraries `pip install wheel pandas numpy nltk`
8. Capture all the installed libraries using `pip freeze > requirements.txt`
9. To install libraries from the requirements.txt file at once, `pip install requirements.txt`
10. To deactivate the environment, `deactivate`.
