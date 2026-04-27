* [MQ](MQ/README.md)
* [CDC](CDC/README.md)
* [Apache2](Apache/README.md)
* [Nginx](Nginx/README.md)
* [Tomcat](Tomcat/README.md)
* [JBoss](JBoss/README.md)
* [Spoolit](Spoolit/)
* [Edit Package](Edit Package/)
* [MasterFE](MasterFE/)
* [Java](Java/README.md)
* [Certificados](Certificados/README.md)
* [Docker](Docker/README.md)
* [LimeSurvey](LimeSurvey/README.md)
* [Zabbix](Zabbix/README.md)
* [Vlan](VLAN/VLAN.rst)
* [Gitlab](Gitlab/README.md)
* [Exchange](Exchange/README.md)
* [LAMP](LAMP/README.md)
* [Servidor Postfix Relay](Postfix/README.md)

**Correo Gmail** = **soporte.app.ccr@gmail.com**

**Password** = **S0p0rt3.** 

**Object Group** = *Dpto_Soporte_Aplicaciones*

**Instaladores MQ FTE** = https://drive.google.com/drive/folders/1foz1Y3W88JztRbumMNYwVKnz2Qg-NWNG?usp=sharing

**Instaladores MQ 9** = https://drive.google.com/drive/folders/1a3Mn-eYuIBfOpTTPkSuXxjv9bgz4-YE-?usp=sharing

**Instaladores de RevDataFlow** = https://drive.google.com/drive/folders/1jJfwDhrNelElivZNYIzbt3o9le2AX8jI?usp=sharing




**Archivos Formato rst** = http://code.nabla.net/es/rest.html


### Organizacion Directorio 


	/App
	|___/install
    |    |    |____/guias
	|    |           |__guias.rst
    |    |_______/images
	|    |         |___/nombre_guia
    |    |              |____image.png
	|    |___README.md
	|___/manuales
    |    |    |____/guias
	|    |           |__guias.rst
    |    |_______/images
	|    |         |___/nombre_guia
    |    |              |____image.png
	|    |___README.md
	|___/troubleshooting
    |    |    |____/guias
	|    |           |__guias.rst
    |    |_______/images
	|    |         |___/nombre_guia
    |    |              |____image.png
	|    |___README.md
    |
	|_ README.md
	
### Command line instructions
You can also upload existing files from your computer using the instructions below.

**Git global setup**

	git config --global user.name "Soporte"
	git config --global user.email "soporte.aplicaciones@credicard.com.ve"

**Create a new repository**

	git clone http://wiki.credicard.com.ve/kb/prueba.git
	cd prueba
	touch README.md
	git add README.md
	git commit -m "add README"
	git push -u origin master

**Push an existing folder**

	cd existing_folder
	git init
	git remote add origin http://wiki.credicard.com.ve/kb/prueba.git
	git add .
	git commit -m "Initial commit"
	git push -u origin master

**Push an existing Git repository**

	cd existing_repo
	git remote rename origin old-origin
	git remote add origin http://wiki.credicard.com.ve/kb/prueba.git
	git push -u origin --all
	git push -u origin --tags