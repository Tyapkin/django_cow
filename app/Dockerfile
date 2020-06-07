FROM python:3.7-alpine

WORKDIR /usr/src/app

RUN apk add --no-cache python3-dev \
    gcc libc-dev mariadb-connector-c-dev

COPY requirements.txt ./

RUN pip install --no-cache-dir -r requirements.txt

COPY . .

EXPOSE 7080

CMD ["python", "manage.py", "runserver", "0.0.0.0:7080"]
