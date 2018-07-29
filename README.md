# Setting Up Python Interpreter + Flask

* Install Git from https://git-scm.com/downloads. Current version - 2.18.0

* macOS

  * Open Term and run the following commands:
```
git clone git@github.com:miguelgrinberg/flask-pycon2015.git
cd flask-pycon2015
virtualenv -p python3 venv
source venv/bin/activate
pip install -r requirements.txt
```

* Windows

  * Install Python 3 (current version 3.6.5) from https://www.python.org/downloads/release/python-365/
  </br>NOTE: Verify python and pip in your PATH !!!!

  * Open Command Prompt and run the following commands:
```
pip install virtualenv

git clone git@github.com:miguelgrinberg/flask-pycon2015.git

(if you got an error like "Permission denied", try the following statement instead:
git clone https://github.com/miguelgrinberg/flask-pycon2015.git)

cd flask-pycon2015
virtualenv venv
cd venv\Scripts
activate
pip install -r requirements.txt
```

* Workshop video in YouTube "Miguel Grinberg - Flask Workshop - PyCon 2015" https://www.youtube.com/watch?v=DIcpEg77gdE
