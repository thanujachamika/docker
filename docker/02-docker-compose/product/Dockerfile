FROM python:3.8-slim-buster
WORKDIR /usr/src/app
COPY . .
RUN pip install --upgrade pip -r requirements.txt
CMD ["python", "api.py"]
