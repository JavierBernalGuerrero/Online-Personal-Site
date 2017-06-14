# [OPS - Online Personal Site](http://ops.pe.hu)

Este proyecto nació de la necesidad de disponer de un espacio personal para poder trabajar 
desde cualquier dispositivo de una forma cómoda y siempre en el mismo entorno. El proyecto ha sido desarrollado
por Javier Bernal Guerrero utilizando Angular 4 y PHP como tecnologías base.

A continuación os dejo un manual de usuario de la aplicación:
## Gestión de usuarios

### Registrar nuevo usuario
	Para registrar un nuevo usuario, nos dirigimos al enlace “Crear cuenta”.
	Al hacerlo nos saldrá un dialogo con un formulario con los datos necesarios para crear la
	cuenta. Al rellenarlo se inicia automáticamente sesión en la web.

![Crear cuenta](https://github.com/JavierBernalGuerrero/Online-Personal-Site/blob/master/Capturas/Home%20-%20Crear_Cuenta_Formulario.PNG)

### Identificarse en la web para acceder al contenido
	Al rellenar el formulario para crear una nueva cuenta se inicia sesión automáticamente.
	Para después volver a iniciar sesión pulsamos sobre la opción “Login” e introducimos el
	usuario y la contraseña.

![Identificarse en la web](https://github.com/JavierBernalGuerrero/Online-Personal-Site/blob/master/Capturas/Home%20-%20Login.PNG)

### Modificar perfil de usuario
	Para acceder a esta funcionalidad pulsamos sobre el desplegable y seleccionamos:
	“Configuraciones → Perfil”. Este menú ofrece al usuario información sobre el perfil así
	como la opción de modificar algunos de los campos como el nombre del perfil, el correo
	electrónico o la contraseña de la cuenta.

![Modificar datos de la cuenta](https://github.com/JavierBernalGuerrero/Online-Personal-Site/blob/master/Capturas/App%20-%20Perfil.PNG)

### Eliminar perfil de usuario
	Esta función solo la puede realizar un usuario administrador. Por favor, ponte en
	contacto con el equipo de administradores si es tu caso.

### Usuario administrador
	Un usuario administrador tiene los mismos servicios que la web ofrece al resto de
	usuarios con algunos servicios añadidos. Por el momento un usuario administrador solo
	cuenta con la funcionalidad añadida de gestionar las cuentas del resto de usuarios. Este
	control se basa en las siguientes funciones:
	- Modificar el nombre de cuenta de un usuario cualquiera.
	- Modificar la contraseña de una cuenta de un usuario cualquiera.
	- Modificar la fecha de creación de la cuenta de un usuario cualquiera.
	- Borrar un usuario cualquiera.

![Opciones del usuario administrador](https://github.com/JavierBernalGuerrero/Online-Personal-Site/blob/master/Capturas/App%20-%20Cuentas1.PNG)

## Gestor de archivos
Esta es la funcionalidad principal de la web. Permite que un usuario suba cualquier fichero*
y luego pueda descargarlo desde cualquier otro dispositivo. La interfaz es muy sencilla e
intuitiva pero vamos a resumir la explicación a los dos siguientes pasos:


### Subir un archivo
	Para subir un archivo solo tenemos que pulsar sobre el botón “+ Seleccionar”. Esta
	opción hará aparecer una ventana emergente donde podremos seleccionar los archivos
	que queremos subir. Por el momento no existe ningún limite de archivos subidos de
	forma simultanea ni tampoco el tamaño máximo del archivo. Ten en cuenta que si
	durante la subida de archivos existe algún problema, se cancelan todos los archivos y
	tendrás que volver a subirlos.

![Subir archivo](https://github.com/JavierBernalGuerrero/Online-Personal-Site/blob/master/Capturas/App%20-%20Gestor_Archivos_Upload.PNG)

#### Descargar un archivo
	Una vez que has subidos los archivos a nuestros servidores, estos se ordenaran
	automáticamente en un sistema de carpetas divididos en: Documentos, Imágenes,
	Música, Videos y Otros (cualquier tipo de archivo que no coincide con las categorías
	anteriores) para facilitar su gestión. Los datos que puede mostrar esta tabla son: nombre
	del archivo/carpeta, tamaño del archivo/carpeta y el tipo de extensión del archivo.
	Por el momento, las acciones que se pueden realizar con los archivos son:

#### Descargar
	Inicia una descarga del fichero seleccionado. Una vez llegado este punto,
	dependiendo del navegador que utilices se ejecutara la descarga de diferentes formas.

#### Borrar
	Tras un mensaje de aviso y confirmación realiza la eliminación del archivo tanto en
	el servidor como en la base de datos.

![Opciones de archivos](https://github.com/JavierBernalGuerrero/Online-Personal-Site/blob/master/Capturas/App%20-%20Gestor_Archivos_Download.PNG)


## Gestor de archivos
	Esta es la primera funcionalidad adicional desarrollada para el proyecto. Básicamente se
	trata de un editor de texto enriquecido que permite crear documentos simples y luego
	descargártelo, generando un documento html. Se puede configurar el nombre del archivo
	generado modificando el campo de titulo en la parte superior del componente. En versiones
	futura se sustituirá la generación del documento en html por pdf, permitiendo así mayor
	adaptación como documento. Las funciones básicas que soporta el editor son:
	
	- Cambiar el tipo de fuente y su tamaño (Cabecera, subtitulo y cuerpo).
	- Crear listas: numeradas y desordenadas.
	- Formatos simples: negrita, cursiva y subrayado.
	- Cambiar el color de fuente y de fondo.
	- Ajustar la alineación del texto.
	- Insertar una imagen.
	- Insertar un hipervínculo.
	- Insertar una vista para código.
	- Limpiar todo el formato para una selección.

![Editor](https://github.com/JavierBernalGuerrero/Online-Personal-Site/blob/master/Capturas/App%20-%20Editor.PNG)

Para mas información consulta la [documentacion](https://github.com/JavierBernalGuerrero/Online-Personal-Site/blob/master/Proyecto%20Integrado%20-%20Documentacion.pdf)
