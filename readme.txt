Для работы проекта необходимо импортировать:
1. Установить django_filters
# pip install django-filter
2. Установить библиотеку bootstrap4
# pip install django-bootstrap4
3. Установить пакет allauth
# pip install django-allauth
4. Установить библиотеку django-apscheduler
# pip install django-apscheduler
5. Установить библиотеку celery
# pip install celery
6. Установить библиотеку redis
# pip install redis
7. Установить сервер redis на локальную машину (Windows без докера)
https://github.com/microsoftarchive/redis/releases/tag/win-3.2.100
Запустить файл redis-server.exe
8. Установить поддержку Redis в Celery
# pip install -U "celery[redis]"
# celery -A NewsPortal worker -l INFO -B # - команда запуска Celery
