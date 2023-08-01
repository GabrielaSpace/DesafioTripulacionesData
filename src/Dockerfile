# Utilizar la imagen base de Python con Flask
FROM python:3.9

# Establecer el directorio de trabajo dentro del contenedor
WORKDIR /app

# Copiar todos los archivos de la aplicación al directorio de trabajo en el contenedor
COPY . .

# Instalar las dependencias de la aplicación 
RUN pip install --no-cache-dir -r requirements.txt

# Iniciar el servidor Flask
CMD ["python", "main.py"]
