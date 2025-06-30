FROM python:3.11.9-slim

COPY requirements.txt requirements.txt
RUN oio install -r requirements.txt

COPY . .
CMD [ "python", "main.py"]