FROM python:3.10-slim

WORKDIR /app

ADD requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

ADD . .

CMD ["uvicon", "main:app", "--host", "0.0.0.0", "--port", "8000"]