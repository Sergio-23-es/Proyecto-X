
FROM python:3.11-slim

WORKDIR /app

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

# tu app escuchará en el puerto 8081
EXPOSE 8081

CMD ["python", "app.py"]
