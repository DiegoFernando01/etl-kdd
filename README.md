<p align='center'>
  <img src='https://user-images.githubusercontent.com/62605744/171186764-43f7aae0-81a9-4b6e-b4ce-af963564eafb.png' style='max-width: 25%; height: auto;'>
</p>

# Módulo de extracción, transformación y carga de datos
- Universidad del Valle - Escuela de ingeniería de sistemas y computación
- Asignatura: Introducción a la ciencia de los datos
- Semestre 2024-II
- Profesor: Oswaldo Solarte Pabon

ETL en Python para base de datos de mensajería

## Autores
- Diego Fernando Victoria - 202125877 - diego.victoria@correounivalle.edu.co
- Janiert Sebastián Salas - 201941265 - janiert.salas@correounivalle.edu.co

## Creación y activación de un entorno en Python
```
python3 -m venv my_env
```
```
source my_env/bin/activate  
```

## Instalación de librerías necesarias
```
pip install -r requirements.txt
```

## Creación y configuración del archivo config.yml
```
echo mensajeriaOLTP: {drivername: postgresql, host: localhost, port: 5432, dbname: (Nombre de la bd), user: (Nombre del usuario propietario), password: (Contraseña del usuario propietario)} mensajeriaOLAP: {drivername: postgresql, host: localhost, port: 5432, dbname: (Nombre de la bd), user: (Nombre del usuario propietario), password: (Contraseña del usuario propietario)} > config.yml
```