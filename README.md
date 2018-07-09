#Chat

My Group chatApp

## Usage

Install dependencies, setup database, and create empty environment config:

```sh
virtualenv --python=python3 venv
. venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
touch .env
```

Run:

```sh
python manage.py runserver
```

Open browser to http://localhost:8000/

