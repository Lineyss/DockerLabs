FROM python:latest

WORKDIR /django

COPY  Test /django

RUN pip install -r req.txt
RUN pip install django-guardian
RUN pip install psycopg2

RUN python manage.py makemigrations

CMD ["./start.sh"]