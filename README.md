## pasos para levantar el servicio 

## 1. Generar el binario de la imagen usando maven
      mvn clean package --DskipTest 

## 2. Generar el contenedor del de myapp
     docker build -t myapp .

## 3. Generar todos los contenedores 
      docker compose up 
