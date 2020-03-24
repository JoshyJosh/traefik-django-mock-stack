FROM python:3.7
WORKDIR /app
COPY . /app
RUN /bin/bash -c 'pip install -r requirements.txt'
CMD /bin/bash -c 'python manage.py runserver 0.0.0.0:8000'