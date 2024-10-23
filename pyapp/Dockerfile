FROM python:3.9-slim

WORKDIR /app

COPY . /app

RUN pip install -r requirement.txt

EXPOSE 8080

CMD ["python", "app.py"]