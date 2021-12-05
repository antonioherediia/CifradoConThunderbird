# Práctica Cifrado Con Thunderbird


## Instalando Thunderbird y añadiendo cuentas


Thunderbird es la plataforma de correos que usaremos para gestionar los correos

Enlace de descarga: https://www.thunderbird.net/es-ES/


La versión que usaremos en la práctica es la 78.12.0


La instalación es muy sencilla, ejecutamos y todo siguiente siguiente por defecto.


Una vez instalada vamos a proceder a añadir las cuentas de correo, para ello nos vamos al menú superior derecha, y damos en añadir cuenta existente.


![captura1](https://github.com/antonioherediia/CifradoConThunderbird/blob/main/Captura1.JPG)

Aquí vemos ya nuestras dos cuentas de prueba añadidas


![captura2](https://github.com/antonioherediia/CifradoConThunderbird/blob/main/Captura2.JPG)

## Instalando GPG4win

Una vez añadida la cuenta de correo, procederemos a instalar GPG, vamos a su página oficial y la descargamos, su instalación es muy sencilla con dos clics, enlace de descarga: https://www.gpg4win.org/


## Instalando Enigmail


Por último descargaremos el plugin de thunderbird Enigmail, para ello nos vamos de nuevo al menú de Thunderbird y hacemos clic en add-on, nos aparecerá la ventana de busqueda y añadimos la extensión con un clic.


![captura3](https://github.com/antonioherediia/CifradoConThunderbird/blob/main/3.JPG)


## Creando Claves 

A continuación tendremos que crear las claves de encriptación (secreta y pública), para ello en la página principal de la cuenta de correo nos vamos a la opción "cifrado de extremo a extremo" y luego a "add key", de esta forma se generarán las claves

![captura4](https://github.com/antonioherediia/CifradoConThunderbird/blob/main/Captura4.JPG)
![captura5](https://github.com/antonioherediia/CifradoConThunderbird/blob/main/Captura5.JPG)


## Enviando el correo cifrado

Lo primero que tenemos que hacer para una mayor comodidad es subir la clave pública de la persona a la cual vamos a enviar el correo, para ello nos vamos al menú superior, herramientas y abrimos "OPEN PGP key Manager", luego nos vamnos a "file" y seleccionamos "importar clave pública".

Ya solo tenemos que enviar el correo, escribimos el destinatario, asunto, mensaje y seguidamente nos vamos a la pestaña seguridad (un candado en la parte superior) y seleccionamos las siguientes opciones, en este caso por mayor comodidad le daré a la opción adjuntar mi clave pública.

![captura6](https://github.com/antonioherediia/CifradoConThunderbird/blob/main/Captura6.JPG)

Una vez configuramos si hacemos clic una vez en el candado no dará el ok de la clave pública


![captura7](https://github.com/antonioherediia/CifradoConThunderbird/blob/main/Captura7.JPG)


Como podemos ver el mensaje está correctamente cifrado


![captura8](https://github.com/antonioherediia/CifradoConThunderbird/blob/main/Captura8.JPG)


## Referencias
https://support.mozilla.org/es/kb/firma-digital-y-cifrado-de-mensajes
https://www.youtube.com/watch?v=xAd5poWAXAM
