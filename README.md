# ETL_docker

Comandos Docker File
-- Crear una imagen:

docker build -t jupyter_notebook .
-- Listar las imagenes:

docker images
-- Crear Contenedor:

docker run -d -p 8000:8888 --name jupyter jupyter_notebook
-- Lista los contenedores:

Docker ps
-- Log de ejecucion segundo plano:

docker logs -f jupyter
-- Eliminar una imagen

docker rmi -f jupyter_notebook
-- Eliminar una contenedor

docker rm -f jupyter
-- Instalar librerias

pip install -r requeriment.txt
-- Levantar servidor MySQL

docker compose up
