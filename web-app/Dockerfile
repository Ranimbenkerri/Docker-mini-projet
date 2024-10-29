FROM python:3.9-slim 
WORKDIR /app
COPY . /app
RUN command pip install -r requirements.txt
EXPOSE 5000
CMD ["python", "app.py"]
