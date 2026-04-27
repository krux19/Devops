Administración Docker
=====================

De igual manera sabemos que la interfaz de CLI no es tan amigable para algunas personas, para ellos podemos usar portainer una herramienta web. Para esto se debe descargar un contenedor con las siguientes instrucciones 

	# docker run -d --name Portainer -p 9000:9000 -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer

*-d: Corre el contenedor en background
*--name: Nombre del contenedor 
*-p: puerto que levanta la maquina : puerto que levanta el contenedor
*-v: volumen asignado para guardar los datos de la aplicación 


luego nos conectamos a la URL si esta la ip se encuentra registrada en un servidor DNS colocamos el nombre registrado si no pues simplemente la ip bastara y el puerto de comunicación que es el 9000 por defecto  

	http://127.0.0.1:9000

 .. figure:: ../images/Administración_Docker/02.png

seleccionamos la opción Docker y presionamos update conexión después de llenar los datos de conexión   

 .. figure:: ../images/Administración_Docker/03.png

 luego de esto podremos visualizar el detalle de los servicios que se encuentran corriendo en el servidor 

  .. figure:: ../images/Administración_Docker/04.png

**Imaguenes**

  .. figure:: ../images/Administración_Docker/05.png


  **Contenedores**

  .. figure:: ../images/Administración_Docker/06.png

**Volumen**

  .. figure:: ../images/Administración_Docker/07.png

