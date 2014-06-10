python ez_setup.py
D:\dev\python\Python27\Scripts;
easy_install pip

pip install django

\Lib\site-packages\django\bin;

https://github.com/jeremyko/dj_board
django-admin.py startproject dj_board

pip install cx_Oracle


dj_board/setting.py
python manage.py syncdb
python manage.py startapp sample_board
python manage.py sqlall sample_board
python manage.py syncdb

dj_board/urls.py
dj_board/settings.py
/sample_board/view.py

python manage.py runserver
python manage.py runserver 8080
