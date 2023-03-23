# Описание  
Приложение Todo - список дел.  
Написано на  3-х разных фреймворках (Django, Flask, Fastapi).  
Данный проект создан для ознакомления с данными фреймворками на python.  

# Установка:  
```
git clone https://github.com/shmyrev/python_mix_frameworks.git   
```
## Django:  
```
cd django_todo/  
python3 -m venv venv && . venv/bin/activate  
pip install -r requirements.txt   
cd todo/  
python3 manage.py migrate  
python3 manage.py createsuperuser  
python3 manage.py runserver  
```
## Flask:  
```
cd flask_todo/  
python3 -m venv venv && . venv/bin/activate  
pip install -r requirements.txt   
export FLASK_APP=app.py  
export FLASK_ENV=development  
flask run  
```
## FastApi:  
```
cd fastapi_todo/  
python3 -m venv venv && . venv/bin/activate  
pip install -r requirements.txt   
uvicorn app:app --reload  
```

