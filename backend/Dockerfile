FROM python:3.11-slim

COPY requirements.txt /usr/share/app/
COPY app /usr/share/app

WORKDIR /usr/share/app

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 5000

CMD ["python", "app.py"]
