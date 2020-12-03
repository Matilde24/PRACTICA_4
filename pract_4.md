## Adroid Studio y mi primer aplicación 
* El resultado debe mostrar una captura semejante a esta pantalla siguiente:

<img src="Medio\imagen1.png"/>

## Tarea 1.1: Instalación de Android Studio
* Android Studio proporciona un entorno de desarrollo integrado (IDE) completo, incluido un editor de código avanzado y un conjunto de plantillas de aplicación. Además, contiene herramientas para el desarrollo, depuración, pruebas y rendimiento que hacen que sea más rápido y fácil desarrollar aplicaciones.

## Para instalar Android Studio en Windows, haz lo siguiente:
* Si descargaste un archivo .exe (recomendado), haz doble clic en él para iniciarlo.
Si descargaste un archivo .zip, extráelo y copia la carpeta android-studio en la carpeta Archivos de programa. A continuación, abre la carpeta android-studio > bin y, luego, inicia studio64.exe (para máquinas de 64 bits) o studio.exe(para las de 32 bits).

* Sigue los pasos del asistente de configuración en Android Studio y asegúrate de instalar los paquetes de SDK que recomiende.
Cuando haya nuevas herramientas y otras API disponibles, Android Studio te lo informará por medio de una ventana emergente. También puedes buscar actualizaciones si haces clic en Help > Check for Update.

## Para instalar Android Studio en Linux, haz lo siguiente:
* Extrae el archivo .zip que descargaste en una ubicación apropiada para tus aplicaciones, como dentro de /usr/local/ para tu perfil de usuario o /opt/ para usuarios compartidos.
Si usas una versión de Linux de 64 bits, asegúrate de instalar primero las bibliotecas requeridas para máquinas de 64 bits.

* Para iniciar Android Studio, abre una terminal, navega al directorio android-studio/bin/ y ejecuta studio.sh.

* Selecciona si deseas o no importar configuraciones previas de Android Studio y, luego, haz clic en OK.

* El asistente de configuración de Android Studio te guiará por el resto de la configuración, lo que incluye la descarga de los componentes del SDK de Android que se necesiten para el desarrollo.

## Después de la instalación compruebe lo siguiente, si le falta algo complete lo necesario:
## Verifique que ya cuente con el JDK de Java en cualquier versión

 Para verificar si ya tenemos el JDK instalado, abrimos una terminal de Windows y dentro de ella vamos a ingresar la palabra <java –versión> y le damos ok, mostrando así de esta manera de respuesta que buscamos.

<img src="Medio\imagen2.png/">

## Verifique la ubicación de la instalación del SDK en Android Studio
 Para que podemos verificar la instalación del Android Studio nos ubicamos en la configuración que se nos muestra en la Android Studio, luego nos vamos donde dice <System Settings>, desplegamos la pestañita, y ahí vamos a buscar la opción del <Android SDK>, en donde podemos observar su locación y más. 

<img src="Medio\imagen3.png/">

## Verifique que en Android Studio este seleccionada la versión del JDK instalada en su máquina.
 En esta parte debemos asegurarnos de que en el Android Studio, se encuentre seleccionada la versión del JDK que nosotros hemos instalado en nuestra máquina, la cual en este caso yo instale la versión 8.0 

<img src="Medio\imagen4.png/">

## Creación de un dispositivo virtual
 Como podemos ver para la creación de un dispositivo virtual debemos hacer clic en Tools > AVD Manager para abrir el Administrador de AVD, seguidamente  en Create Virtual Device, en la parte inferior del diálogo del Administrador de AVD, luego Seleccionamos  un perfil de hardware y le damos clic en Next, una vez estando en esta parte simplemente Seleccionamos la imagen del sistema para un nivel de API determinado y hacemos clic en Next, seguidamente modificamos  las propiedades de AVD según sea necesario y hacemos  clic en Finish, si lo deseamos podemos entrar en Show <Advanced Settings> para que se muestren más configuraciones, como la máscara y más  y por ultimo revisamos el nuevo AVD el cual aparecerá en la página Your Virtual Devices o en el diálogo Select Deployment Target.

<img src="Medio\imagen5.png/">

## Tarea 1.2: Crear la aplicación Hello World
## Crea el proyecto de aplicación
 Para crear un proyecto de aplicación, primeramente en la interfaz del programa podemos ver las distintas opciones con las que se puede trabajar, pero en esta ocasión vamos a elegir la opción que se está señalando con el círculo.

<img src="Medio\imagen6.png/">

 Según la versión, es posible que primero seleccione la plantilla, entonces seleccione una plantilla Empty Activity en el panel correspondiente a Phone y Tablet.

<img src="Medio\imagen7.png/">

*Seguidamente lo que debemos hacer es rellenar los campos, en este caso llamé: Hello World para el nombre de la aplicación.

<img src="Medio\imagen8.png/">

 En este paso vamos a comprobar la ubicación predeterminada del proyecto en donde se desea almacenar la aplicación, en el caso de que esa no sea la ubicación preferida, la podemos cambiar.

<img src="Medio\imagen9.png/">
 Si no tiene pensado publicar la aplicación, puede dejar el nombre del paquete predeterminado.

 En las nuevas versiones se elige Kotlin como el lenguaje de programación predeterminado, y en un dado caso de que no aparezca seleccionado, simplemente desplegamos y lo seleccionamos Kotlin.

<img src="Medio\imagen10.png/">

## Indique que porcentaje de dispositivos usan la API nivel 19 y cuáles son sus características que incluye según el apartado Help me choose.

 En la imagen se representan tanto el porcentaje, así como también sus características

<img src="Medio\imagen12.png/">

 De clic en finish, y espere que gradle sincronice todas las librerías necesarias para su aplicación, esto puede tardar un momento, sea paciente.

 <img src="Medio\imagen13.png/">

# Cada vez que inicia un proyecto le lanza un consejo del día, tome una captura del consejo que le salió
<img src="Medio\imagen14.png/">
 
 # Haga clic en la pestaña activity_main.xml para ver el editor de diseño
* Como podemos observar, al hacer clic en la pestaña que se nos indica, podemos observar los diferentes editores de diseño, con los cuales se estarán trabajando cada vez que se necesite la creación de un proyecto.

<img src="Medio\imagen15.png/">

Seguidamente damos clic en la pestaña <Diseño del editor de diseño>, lo cual si aún no está seleccionada, para mostrar una representación gráfica del diseño así como se muestra a continuación.
<img src="Medio\imagen16.png/">

# Haga clic en la pestaña MainActivity.kt o MainActivity.java
En esta pestaña el objetivo es de iniciar una nueva actividad para mostrar un mensaje cuando el usuario presione el botón Enviar.
<img src="Medio\imagen17.png/">

# Explore el proyecto en el panel Android
Como podemos observar, con el panel de Android  es por el cual podemos tanto visualizar las carpetas como realizar modificaciones en las mismas.
<img src="Medio\imagen18.png/">

# Explore la carpeta Gradle Scripts
Este es un paquete de herramientas de compilación avanzadas, para automatizar y administrar el proceso de compilación, y al mismo tiempo definir configuraciones de compilación personalizada y flexible.
<img src="Medio\imagen19.png/">

# 	Busque el archivo build.gradle (Project: Hello_World).
En esta parte como podemos observar, se encuentra guardado el proyecto que ya he creado.
<img src="Medio\imagen20.png/">

# Busque el archivo build.gradle(Module:app).
En cada uno de estos archivos que se van a ir explorando, se va ir señalando para que se puedan reconocer con más facilidad.
<img src="Medio\imagen21.png/">

# Explorar la aplicación y la carpeta res
<img src="Medio\imagen22.png/">

## Expanda la carpeta de la aplicación, la carpeta java y la carpeta com.example.android.helloworld para ver el archivo java MainActivity. Al hacer doble clic en el archivo se abre en el editor de código.
Para poder llegar a los demás archivos, simplemente debemos desplegar la pestaña de la carpeta principal.
<img src="Medio\imagen23.png/">

## Expanda la carpeta res y la carpeta de diseño y haga doble clic en el archivo activity_main.xml para abrirlo en el editor de diseño.
En esta otra carpeta, debemos acceder a la carpeta de diseño y luego debemos hacer doble clic en el archivo activity_main.xml, esto para abrirlo en el editor de diseño.
<img src="Medio\imagen24.png/">

# Explorar la carpeta de manifiestos
Este archivo nos muestra, el nombre del paquete de la aplicación, que normalmente coincide con el espacio de nombres del código; Los componentes de la aplicación, que incluyen todas las actividades, servicios, receptores de emisiones y proveedores de contenido entre otras más.
<img src="Medio\imagen25.png/">

# Abra el archivo AndroidManifest.xml.
Como podemos observar, al entrar en este archivo, se nos muestran líneas de códigos.
<img src="Medio\imagen26.png/">

## Tarea 1.3: Use un AVD (Android Virtual Device)
# Crear un dispositivo virtual de Android (AVD)
En Android Studio, seleccione Herramientas > Android > Administrador de AVD o haga clic en el icono Administrador de AVD en la barra de herramientas. Aparecerá la pantalla Sus dispositivos virtuales. Si ya ha creado dispositivos virtuales, la pantalla los muestra (como se muestra en la figura siguiente); de lo contrario se ve una lista en blanco.
<img src="Medio\imagen27.png/">

Hacemos clic en + Crear dispositivo virtual. Aparece la ventana Seleccionar hardware la cual nos muestra una lista de dispositivos de hardware preconfigurados. Para cada dispositivo, la tabla proporciona una columna para su tamaño de visualización diagonal (Tamaño), resolución de pantalla en píxeles (Resolución) y densidad de píxeles (Densidad).
<img src="Medio\imagen28.png/">

## Haga clic en la pestaña Recomendado si aún no está seleccionada y elija qué versión del sistema Android se ejecutará en el dispositivo virtual (como Pie).
En este caso vamos a seleccionar la que sea conveniente.
<img src="Medio\imagen29.png/">

## Después de elegir una imagen del sistema, haga clic en Siguiente. Aparece la ventana Dispositivo virtual Android (AVD). También puede cambiar el nombre del AVD. Compruebe la configuración y haga clic en Finalizar.
Y aquí elegimos una que no sea tan pesada, para que a la hora de ejecutar la depuración, no se nos dificulte tanto.
<img src="Medio\imagen30.png/">

# Ejecute la aplicación en el dispositivo virtual
Una vez, que se encuentre la API que vamos a usar, la cual hemos descargado vamos a darle run para observar el resultado. 
<img src="Medio\imagen31.png/">

## En Android Studio, elija Run > Ejecutar aplicación o haga clic en el icono Ejecutar de la barra de herramientas.
Como podemos observar, se va señalando cada una de las opciones, las cuales se van describiendo.
<img src="Medio\imagen32.png/">

Y al momento de compilar, pues nos va a quedar algo así, en donde nos presenta el mensaje el cual declaramos. 

<img src="Medio\imagen33.png/">

# Cuando finalice puede observar un resultado semejante al siguiente:
Como dije en el paso anterior, al realizar la ejecución, nos va a mostrar el mensaje que se espera que muestre.
<img src="Medio\imagen33.png/">

# Ejecute la aplicación en un dispositivo físico
# Muestre todos los pasos necesarios para ejecutar su aplicación utilizando su dispositivo físico
Bueno, para ejecutar la aplicación en un dispositivo físico, primeramente debemos de conectar el móvil con la pc, en donde una vez conectado el teléfono nos aparecerá una notificación, le damos permitir, y esperamos a que nos muestre el mensaje.

# Encienda la depuración USB en su dispositivo físico
Con esto nos referimos a realizar la conexión del móvil con la pc, para correr el proyecto en la pantalla de este.

# Ejecute la aplicación en su dispositivo físico
Y de esta manera no debe aparecer, en la parte de arriba se nos muestra el nombre la aplicación y en la parte de en medio se muestra el mensaje.

<img src="Medio\imagen34.png/">

## Cambiar la configuración de Gradle de la aplicación 
# Cambiar la versión mínima del SDK para la aplicación

