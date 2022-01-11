Python version 3.9.9
Django version 4.0.1 (Начиная с ЗАДАНИЯ D 13.4 (HW-03))

Для работы проекта необходимо импортировать:
1. Установить django_filters
# pip install django-filter
2. Установить библиотеку bootstrap4
# pip install django-bootstrap4
3. Установить пакет allauth
# pip install django-allauth
4. Установить библиотеку django-apscheduler   ## в этой версии проекта не нужно (закомментировано)
# pip install django-apscheduler
5. Установить библиотеку celery   ## в этой версии проекта не нужно (закомментировано)
# pip install celery
6. Установить библиотеку redis   ## в этой версии проекта не нужно (закомментировано)
# pip install redis
7. Установить сервер redis   ## в этой версии проекта не нужно (закомментировано)
7.1 на локальную машину (Windows без докера)
https://github.com/microsoftarchive/redis/releases/tag/win-3.2.100
Запустить файл redis-server.exe
7.2 на MacOs
Запустить в терминале MacOs (Homebrew) установку сервера
brew install redis
Запустить сервер:
redis-server /usr/local/etc/redis.conf
8. Установить поддержку Redis в Celery   ## в этой версии проекта не нужно (закомментировано)
# pip install -U "celery[redis]"
# celery -A NewsPortal worker -l INFO -B # - команда запуска Celery

!!! ВНИМАНИЕ !!!
LOGGING для Django version 4.0.1
