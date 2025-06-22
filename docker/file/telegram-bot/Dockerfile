FROM python:3.10-slim

WORKDIR /bot

COPY requirements.txt ./

RUM pip install -r requirements.txt

COPY . /bot 

CMD ["python","main.py"]
