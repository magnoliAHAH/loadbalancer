from python:3.9-slim
workdir /app
copy . .
run pip install -r requirements.txt

cmd gunicorn --bind 0.0.0.0:5000 flaskApp:app