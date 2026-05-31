FROM python:3.9-slim

WORKDIR /app

COPY . .

RUN pip install -r lint-files/requirements.txt

CMD ["python", "lint-files/app.py"]
