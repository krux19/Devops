Comandos Docker
=====================

Pequeña chuleta con comandos docker

**Comando para conectarte al repo de docker a descargar imágenes**

	# docker pull <image name>

**Listar imágenes que tenemos en nuestro repo local**

	# docker images

	# docker image ls

**Muestra todos los contenedores**

	# docker ps -a

**Eliminar una imagen (No debe estar en uso)**

	# docker rmi ID_IMAGE

**Elimina los volumenes no usados** 

	#docker volume prune

**Iniciar y detener un contenedor**

	# docker start ID_CONTENEDOR
	# docker stop  ID_CONTENEDOR

**Eliminar un contenedor**

	# docker rm ID_CONTENEDOR

**Generacion de imagen atravez de un contenedor**

	# docker commit <ID_CONTENEDOR> <tag image>