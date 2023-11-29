# NOTAS GENERALES

## Front-End Dev

Trabaja en la parte visual de una página web o aplicación, creando elementos interactivos y estéticamente agradables. Utiliza lenguajes de programación como JavaScript, HTML y CSS para diseñar sitios web.

## Back-End Dev

Se encarga de la lógica y la funcionalidad detrás de escena de una página web o aplicación. Trabaja en el servidor, creando operaciones, bases de datos y interfaces de programación de aplicaciones (APIs). Utiliza lenguajes de programación del lado del servidor como Java, Python y Ruby.

## ¿Como funciona Internet?

Internet es una red global de computadoras que se comunican entre sí. Cada computadora en la red tiene una dirección única, conocida como dirección IP (Protocolo de Internet), que permite su ubicación en la red.

Cuando accedes a un sitio web, tu computadora envía una solicitud al servidor que aloja el sitio web. Si el servidor responde positivamente, el contenido del sitio web se envía a tu computadora en paquetes de datos. Estos paquetes pueden tomar diferentes caminos para llegar a tu computadora, y una vez que llegan, se organizan y ordenan para que puedas ver el sitio web como se espera.

Además, para facilitar el acceso a los sitios web, los nombres de los sitios web (como facebook.com o google.com) se traducen a una dirección IP asociada 4.

En resumen, Internet funciona como una red de computadoras que se comunican entre sí, enviando y recibiendo paquetes de datos para compartir información y servicios.

## ¿Que es un Servidor Web?

Un "Servidor" es un ordenador que ejecuta aplicaciones o servicios, propociona un "servicio" a otro ordenador(client).
Normalmente esta alojado en un Data Center. Un "Web Server" es un tipo especifico de servidor, permite almacenar
información, administrar webs, gestionar solicitudes.

## ¿Que son los sitios y paginas webs?

Una pagina web es un documento que permite interactuar con contenido, mientras que un sitio web, es un conjunto de estas paginas web entrelazadas.

## ¿Que tecnologías se usan habitualmente para una pagina web?

* **HTML**:  Hyper Text Makup Language *Estructuracion / Maquetado* Etiquetas de marcado.
* **CSS**:  Cascade Style Sheets * Personalización y colorización.
* **JAVASCRIPT**:  Interactividad.

## ¿Que es el renderizado de pagina?

Es la representacion visual de la estructura del codigo linea a linea de una web gracias a la respuesta del servidor.

## ¿Que es un navegador web?

Es un software que nos permite viajar en el World Wide Web, funciona enviando una solicitud al Web Server y recibe una respuesta de este renderizando el contenido. El navegador se comunica con el Web Server mediante un "Protocolo de Transferencia de Hipertexto"(HTTP). Se basa en un ciclo de Request-Response (Solicitud Respuesta)

## URL

Localizador Uniforme de Recursos. La url esta estructurada por el Protocol-Domain Name-File Path.  

* Ejemplo: <https://www.navegador.com/index.php>

## Hostings

**¿Que es un web hosting?**  
Es un servicio que nos permite alojar o subir nuestro sitio web o archivos.

**Tipos de Hosting**:

* **Shared Hosting (Mas economica)**:
Alquilas una ubicacion en un servidor, compartes la potencia o banda ancha con otros sitios web, esto puede afectar el rendimiento.

* **Virtual Private Server (Mas cara)**:
Alquilas un servidor virtual con recursos dedicados de CPU, memoria y ancho de banda fijos, trabaja en conjunto con otras instancias vps, pero no afecta el rendimiento.

* **Dedicated Hosting (Mas caro que una VPS)**:
Similar a VPS pero dedicado solo para ti, no comparte instancias.

* **Cloud Hosting**:
Almacenamiento en un entorno llamado "la nube", se extiende a traves de multiples servers fisicos y virtuales, si el servidor fisico falla, tu web seguira en linea ya que se pasa a otro servidor, no tiene limitaciones de hardware o banda ancha, pero pagas en funcion del uso de recursos.

## Protocolos de Internet

Actualmente hay 2 estandares (IPV4 con 4 octetos, IPV6 con 8 grupos hexadecimales).

**IPV4**:  
192.45.55.393  

**IPV6**:  
2001:0db8:85a3:0000:0000:8a2e:0370:7334

**TCP (Protocolo de control de transmision)**  
Resuelve perdida de packets o caidas, desordenados, corrupcion de packets, pero a costa de un pequeño retraso en el envio.
USO: Envio de archivos o textos(No tolera perdida)

**UDP (Protocolo de diagrama de usuarios)**  
Resuelve packets corruptos, pero pueden llegar desordenados o no llegar.
USO: Llamadas o transmision de video(Tolera perdida)

**UDCH (Protocolo de Configuracion Dinamica del Host)**  
Sirve para conectarse a una red, se asigna una IP al ordenador.

**DNS (Protocolo del sistema de nombres de dominio)**  
Sirve para resolver o saber con qué direccion IP relacionada a un servidor debemos conectarnos

**IMAP (Protocolo de acceso a mensajes de Internet)**  
Su dispositivo necesita una forma de descargar los correos electrónicos y gestionar su buzón en el servidor que los almacena. Este es el propósito del Protocolo de Acceso a Mensajes de Internet o IMAP.

**SMTP (Protocolo simple de transferencia de correo)**  
Permite a los clientes de correo electrónico enviar correos electrónicos a través de un servidor SMTP. También puede
utilizarlo para recibir correos electrónicos de un cliente de correo electrónico, pero IMAP es más comúnmente utilizado.

**POP (Protocolo de oficina de correos)**  
Es un protocolo más antiguo utilizado para descargar correos electrónicos a un cliente de correo electrónico. La principal diferencia de utilizar POP en lugar de IMAP es que POP borrará los correos electrónicos del servidor una vez que se hayan descargado en su dispositivo local. Aunque ya no se utiliza habitualmente en los clientes de correo electrónico, los desarrolladoressuelen utilizarlo para implementar la automatización del correo electrónico, ya que es un protocolo más sencillo que IMAP.

**FTP (Protocolo de transferencia de archivos)**  
Permite listar, enviar, recibir y borrar archivos en un servidor. Su servidor debe ejecutar un Servidor FTP y usted necesitará un Cliente FTP en su máquina local.

**SSH (Protocolo Secure Shell)**  
Cuando empiece a trabajar con servidores, también necesitará una forma de iniciar sesión e interactuar con el ordenador de forma remota.
El método más común de hacerlo es utilizando el Protocolo Secure Shell, comúnmente conocido como SSH. El uso de un cliente SSH le permite
conectarse a un servidor SSH que se ejecuta en un servidor para realizar comandos en el ordenador remoto.
Todos los datos enviados a través de SSH están encriptados.

**SFTP (Protocolo de transferencia de archivos SSH)**  
Protocolo Seguro de Transferencia de Archivos, para transferir archivos a través del protocolo SSH. Esto garantiza que los datos se
transmiten de forma segura. La mayoría de los clientes FTP también son compatibles con el protocolo SFTP.

## HTTP

Hypertext Transfer Protocol: Basado en Request-Response  

## HTTPS

Hypertext Transfer Protocol Secure (Forma segura de realizar solicitudes con encriptacion)

**Estructura de HTTP**  
Consta de un Metodo (Method), una ruta(Path/Host), una version y encabezados(Headers).

## Metodos HTTP mas usados

* **GET**: Recupera o solicita información de un servidor
* **POST**: Envia datos a un servidor
* **PUT**: Sustituye un recurso en el servidor
* **DELETE**: Elimina un recurso del servidor
* **PATCH**: Modifica parcialmente un recurso en el servidor

## Versiones HTTP mas usadas

1.1 y 2.0

## Codigos de estado HTTP

Una solicitud o respuesta HTTP puede contener tambien un Body y
Status Code, Status Message.
Los codigos de estado estan en un rango de (100 a 599):

**Informational(100-199)**  
Indican respuestas provisionales

* 100 CONTINUE (Informacion adicional o asistencial)

**Successful(200-299)**  
Indican que se proceso la solicitud correctamente  

* 200 OK (Correcto)

**Redirection(300-399)**  
Indican cuando un recurso se ha movido a otra ruta  

* 300 MOVED PERMANENTLY (Se movio el recurso a otra ruta permanentemente)  
* 302 FOUND (Se movio el recurso temporalmente y redirecciona a esa ruta)

**Client Error(400-499)**:  
Indican un error o percance en la sintaxis o en la solicitud

* 400 (Datos incorrectos enviados al servidor)
* 401 (El usuario debe iniciar sesion)
* 403 (El servidor se niega a procesar la solicitud)
* 404 NOT FOUND (Recurso no encontrado)

**Server Error(500-599)**: Indican un error en el servidor

* 500 INTERNAL SERVER ERROR (El servidor no pudo procesar la solicitud)

## Diferencia entre Website y Web Application

* Nivel de interactividad y dinamismo.
* La website es mas informativa.
* La web application es mas interactiva.

## Frameworks

Son marcos o estructuras de trabajo con instrucciones

* Ventajas: Ahorro tiempo, estructura, buenas practicas.
* Desventajas: Restricciones en la estructura, compatibilidad.

## Librerias

 Son trozos de códigos reutilizable con funcionalidades especificas

* Ventajas: Permite reemplazar librerias por otras actuales facilmente.
* Desventajas: Compatibilidad, seleccionar un set de librerias.

## APIS (Interfaz de programacion de aplicaciones)

Tambien se les conoce como middlewares o pasarelas.
Conjunto de funciones y procedimientos para crear aplicaciones que accedan a caracteristicas o datos de un sistema, app o servicio. Sirven como puente entre distintos componentes o sistemas.

## Tipos Principales de API

**Browser API**:  
Proporcionan acceso a los datos del sistema, como la ubicación geográfica del usuario, la orientación del dispositivo, los datos de la cámara, y más. También permiten a los desarrolladores manipular el contenido de la página web, como crear y eliminar elementos HTML, aplicar estilos CSS, y más.

**REST API**:  
Utiliza el protocolo HTTP para comunicarse entre el cliente y el servidor, permitiendo operaciones CRUD (crear, leer, actualizar y eliminar) en los recursos del servidor. Se trabaja con "endpoints" para realizar los procesos.

**Sensor-Based API**  
Permiten a los desarrolladores acceder a los sensores de los dispositivos de los usuarios de manera consistente en toda la aplicación.

## Otros tipos de API

* **Fetch API**
* **Canvas API**
* **History API**
* **Web Storage API**

## IDE (Entorno de desarrollo integrado)

Es un software para crear aplicaciones, mas sofisticado que un editor de texto.

## REFACTORIZACION

Cambiar la estructura del codigo sin afectar la funcionalidad.
