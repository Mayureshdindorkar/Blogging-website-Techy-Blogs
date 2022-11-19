# Blogging Website

Live Website: http://dmayuresh99.pythonanywhere.com/

1)	python -m venv myvenv
2)	>Myvenv\Scripts\activate
3)	(myvenv)> python -m pip install --upgrade pip
4)	requirements.txt	- Django~=2.2.4
5)	pip install -r requirements.txt
6)	django-admin.exe startproject mysite .
7)	TIME_ZONE='Asia/Kolkata'
8)	STATIC_ROOT = os.path.join(BASE_DIR, 'static')
9)	ALLOWED_HOSTS = ['127.0.0.1', '.pythonanywhere.com']
10)	python manage.py runserver
11)	python manage.py startapp blog   (blog is appname)
12)	settings.py - 'blog.apps.BlogConfig',
13)	add classes and functions in the apps models.py
14)	python manage.py makemigrations blog
15)	python manage.py migrate blog
16)	admin.site.register(Post)
17)	python manage.py runserver
18)	python manage.py createsuperuser  (give password)
19)	python manage.py runserver
20)	 http://127.0.0.1:8000/admin/.
21)	pip freeze > requirements.txt

Username - mayuresh                            password - 123

# Tech Stack
Backend: Python Django 2.2

UI: HTML5, CSS, Bootstrap4
