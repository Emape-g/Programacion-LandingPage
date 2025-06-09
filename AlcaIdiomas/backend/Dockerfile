FROM python:3.11-slim

# Crear el directorio de trabajo
WORKDIR /app

# Copiar los archivos
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

#Variable de entorno para Flask
ENV FLASK_APP=run.py
ENV FLASK_ENV=development

# Expone el puerto del servidor Flask
EXPOSE 5000

# Comando para correr la app
CMD ["gunicorn", "--bind", "0.0.0.0:5000", "run:app"]