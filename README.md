# [OPS - Online Personal Site](http://ops.pe.hu)

Este proyecto nació de la necesidad de disponer de un espacio personal para poder trabajar 
desde cualquier dispositivo de una forma cómoda y siempre en el mismo entorno. Ha sido desarrollado
por Javier Bernal Guerrero utilizando Angular 4 y PHP.

A continuación os dejo un manual de usuario de la aplicación:
## Gestión de usuarios

- Registrar nuevo usuario
Para registrar un nuevo usuario, nos dirigimos al enlace “Crear cuenta”.
Al hacerlo nos saldrá un dialogo con un formulario con los datos necesarios para crear la
cuenta. Al rellenarlo se inicia automáticamente sesión en la web.


- Identificarse en la web para acceder al contenido
	Al rellenar el formulario para crear una nueva cuenta se inicia sesión automáticamente.
	Para después volver a iniciar sesión pulsamos sobre la opción “Login” e introducimos el
	usuario y la contraseña.


- Modificar perfil de usuario
	Para acceder a esta funcionalidad pulsamos sobre el desplegable y seleccionamos:
	“Configuraciones → Perfil”. Este menú ofrece al usuario información sobre el perfil así
	como la opción de modificar algunos de los campos como el nombre del perfil, el correo
	electrónico o la contraseña de la cuenta.


- Eliminar perfil de usuario
	Esta función solo la puede realizar un usuario administrador. Por favor, ponte en
	contacto con el equipo de administradores si es tu caso.


- Usuario administrador
	Un usuario administrador tiene los mismos servicios que la web ofrece al resto de
	usuarios con algunos servicios añadidos. Por el momento un usuario administrador solo
	cuenta con la funcionalidad añadida de gestionar las cuentas del resto de usuarios. Este
	control se basa en las siguientes funciones:
	- Modificar el nombre de cuenta de un usuario cualquiera.
	- Modificar la contraseña de una cuenta de un usuario cualquiera.
	- Modificar la fecha de creación de la cuenta de un usuario cualquiera.
	- Borrar un usuario cualquiera.


## Gestor de archivos
Esta es la funcionalidad principal de la web. Permite que un usuario suba cualquier fichero*
y luego pueda descargarlo desde cualquier otro dispositivo. La interfaz es muy sencilla e
intuitiva pero vamos a resumir la explicación a los dos siguientes pasos:


- Subir un archivo
	Para subir un archivo solo tenemos que pulsar sobre el botón “+ Seleccionar”. Esta
	opción hará aparecer una ventana emergente donde podremos seleccionar los archivos
	que queremos subir. Por el momento no existe ningún limite de archivos subidos de
	forma simultanea ni tampoco el tamaño máximo del archivo. Ten en cuenta que si
	durante la subida de archivos existe algún problema, se cancelan todos los archivos y
	tendrás que volver a subirlos.


- Descargar un archivo
	Una vez que has subidos los archivos a nuestros servidores, estos se ordenaran
	automáticamente en un sistema de carpetas divididos en: Documentos, Imágenes,
	Música, Videos y Otros (cualquier tipo de archivo que no coincide con las categorías
	anteriores) para facilitar su gestión. Los datos que puede mostrar esta tabla son: nombre
	del archivo/carpeta, tamaño del archivo/carpeta y el tipo de extensión del archivo.
	Por el momento, las acciones que se pueden realizar con los archivos son:

- Descargar
	Inicia una descarga del fichero seleccionado. Una vez llegado este punto,
	dependiendo del navegador que utilices se ejecutara la descarga de diferentes formas.

- Borrar
	Tras un mensaje de aviso y confirmación realiza la eliminación del archivo tanto en
	el servidor como en la base de datos.

Para mas información consulta la [documentacion](https://github.com/JavierBernalGuerrero/Online-Personal-Site/blob/master/Proyecto%20Integrado%20-%20Documentacion.pdf)
