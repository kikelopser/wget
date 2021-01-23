# wget Enrique López Serrano
# 1.- Introducción
WGET es una herramienta basada en GNU que permite descargar libremente contenidos desde servidores web de una forma simple. Esta herranienta permite hacer descargas a través de FTP, HTTP, HTTPS y SFTP. Se puede usar en cualquier sistema de Unix, incluso podemos implementarlo en MacOS, Windows, AmigaOS y otros sistemas populares.
# 2.- Instalación
Para instalar este comando es necesario simplemente tener conexión a internet, posteriormente ejecutamos el siguiente comando dentro de la terminal en cualquier sistema de Linux "apt-get install wget", una vez finalizado la instalación podemos hacer uso de la herramienta.
# 3.- Ejemplos
Podemos obtener la última versión de WordPress usando lo siguiente: "wget https://wordpress.org/latest.zip", en este ejemplo, se descargará un archivo llamado latest.zip en el directorio de trabajo actual. También verá información adicional. Usando con wget la opción -S, este muestra todas las peticiones enviadas por la aplicación y las respuestas enviadas por el servidor web. La opción -d activa el modo desarrollador, lo que hace que se vea toda la información disponible. "wget -d -S http://www.insmet.cu/Pronostico/tv06.jpg". Al mismo ejemplo anterior se adiciona la opción: "-c", para lograr que en caso un error en la conexión, al restablecerse esta prosiga en el mismo punto en que se detuvo. "wget -c http://technet.microsoft.com/en-us/sysinternals/bb842062.aspx"
# 4.- Referencias
https://norfipc.com/internet/ejemplos-wget.html y https://www.hostinger.es/tutoriales/usar-comando-wget/#Que-es-el-Comando-Wget
