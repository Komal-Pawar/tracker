#STEPS
#create new project named tracker

pip install "fastapi[all]"
pip freeze > requirements.txt
pip freeze > requirements.dev.txt
pip freeze > requirements.test.txt
Project structure

# STEP 1

tracker  (project root)
├── README.md
├── api
│   ├── __init__.py
│   └── api.py  (sub-application)
├── main.py
├── requirements.dev.txt
├── requirements.test.txt
├── requirements.txt

# STEP 2


tracker
├── README.md
├── api
│   ├── __init__.py
│   ├── api.py
│   └── handlers
│       ├── __init__.py
│       └── demo.py
├── main.py
├── requirements.dev.txt
├── requirements.test.txt
├── requirements.txt
