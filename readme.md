# Install
```sh

conda install -n rango python=3.11
conda activate rango
conda install pillow
pip install django
djando-admin --version

django-admin startproject tango_with_django_project

cd tango_with_django_project

python manage.py migrate
python manage.py runserver
#open http://127.0.0.1:8000/
```