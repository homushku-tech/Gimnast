
FROM python:3.11

RUN mkdir /booking_app

WORKDIR /booking_app

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . .

CMD [ "python", "manage.py", "runserver", "0.0.0.0:8001"]