pip install virtualenv
virtualenv venv 
source venv/bin/activate 

pip freeze > requirements.txt 

pip install -r requirements.txt

