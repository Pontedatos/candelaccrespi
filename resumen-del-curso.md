# Resumen de lo aprendido en el curso
## En el presente repositorio haremos un repaso de los conocimientos adquiridos gracias a la asignatura de Periodismo de Datos durante el curso 2021/2022. Para su redacción seguiremos las pautas marcadas por el profesor en Aula Global 
> Advertencia: creo que es importante detallar, antes de entrar de lleno en las explicaciones, mi proceso de aprendizaje con respecto a la asignatura ya que por una serie de circustancias ha sido particular. A diferencia de mis compañeras he cursado la asigantura a distancia por medio de tutorías con el profesor y un sin fín de correos en los que yo le presentaba mis dudas. Por otra parte, a mitad de cuatrimestre tuve que cambiarme de ordenador, pasé de un sistema de Windows a uno de Mac. Me centraré únicamente en detallar mis avances con el sistema de Mac porque a través de él he hecho las últimas tres prácticas. 

### **Instalación de un programa de emulación de la terminal**
En mi anterior ordenador utilicé los programas de GitBash y posteriormente me descargue Cygwin. Al cambiarme a Mac no tuve que instalar otra nuevo programa que emulase una terminal  porque en Apple la terminal, desde la que estoy trabajando ahora mismo, viene ya de por sí isntalada en  el propio dispositivo. 
Lo único que tuve que descargarme fue ´XCode´ a través de la Apple Store. Xcode es [el conunto de herramientas de desarrollo de aplicaciones de Apple](https://ipadizate.com/tecnologia/xcode-93212)
Después de instalarlo desde la terminal ejecuté el comando `xcode-select-install`en la terminal. 

### **Configuración del programa**
Al tener ya disponible la terminal sin la necesidad de descargar ningún otro programa no tuve que llevar a cabo ciertas configuraciones que si que fueron necesarias cuando trabajaba con Cygwin.Debido a un fallo mío tuve que dar acceso a la terminal  a mi repositorio local de manera manual. A partir de los ajustes de permiso se puede determinar quién puede ver y modificar los archivos del ordenador y que aplicaciones pueden acceder a ellos. Para permitir que la terminal pudiera trabajar con mi carpeta de "periodismo-de-datos" seguí la siguiente ruta: ´Archivo>abrir el candado>Acción>"Aplicar a los ítems incluidos"´
Para vincular correctamente la terminal con GitBash se me pidió mi nombre de usuario en la plataforma: "candelaccrespi" y un **token**.[Recientemente en GitHub se ha considerado como obsoleto la autentificación por medio de contraseñas, ahora mismo para poder acreditar tu identidad debes generar un Token de Acceso Personal](https://docs.github.com/es/enterprise-server@3.1/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token). 
Una vez permitido el acceso **clone mi repositorio de Github en esta carpeta** con la función ´git clone´ más la URL de mi repositorio "periodismo-de-datos-2".

### Algunas nociones básicas de la terminal

- `whoami`:  imprime el nombre del usuario actual en el momento en que se invoca
- `pwd`: devuelve la ruta en la que estamos situados

*Otro instrumento que puede ser muy útil a la hora de empelar la Terminal es la tecla tabuladora*

### Github
Una vez permitido el acceso de la terminal a mi carpeta de la asignatura  **cloné mi repositorio de GiHhub en ella a tavés de la terminal  para que estuvieran vinculadas**.
Lo primero que tenemos que hacer es conocer la ruta en la que estamos situados por medio del comando `pwd`. A mi siempre me imprime mi ruta de inicio que coincide con mi nombre de usuario del ordenador: Candela Crespi. Pero yo donde quiero estar es en mi carpeta de "periodismo de datos" a la que me traslado por medio del comando `cd`. La ruta es la siguiente `Desktop>Universidad>5º/curso>Periodismo de datos>periodismo-de-datos-2. 
Una vez nos encontremos en la careta correcta, copiamos el enlace de nuestro repositorio y volvemos a la terminal donde los clonamos por medio de la función ´git clone´. En mi caso: https://github.com/candelaccrespi/periodismo-de-datos-2.git 
Antes de nada, tenemos que configurar nuestro usuario de GitHub en la terminal para vincular los cambios. Para ello, tenemos que escribir `git config --global user.name nuestrousuario`, y luego `git config --global user.email correogithub`. En mi caso: `git config --global user.name candelaccrespi` y `git config --global user.email 100386117@alumnos.uc3m.es`, con el correo de la universidad.
Para vincular correctamente la terminal con GitBash se me pidió mi nombre de usuario en la plataf>
Una vez vinculada la terminal con GitHub y viceversa pudimos empezar a hacer nuestras prácticas y trasladarlas a GitHub. A contonuación expondré una serie de comandos por los que actualziaba y acompasaba el trabajo ejecutado en la terminal/GitBash.

- `git status`: muestra el estado del directorio de trabajo, señalando los cambios realizados. En caso de que alguno de ellos no esté sellado o actualizado en el repositorio remoto, nos indica cuáles son los pasos que debemos seguir para solucionarlo. 
- `git add nombre-archico`o en el caso de haber realizado diversos cambios que queremos añadir `git add .`
- `git commit`para sellar nuestro cambios. La opción mas utilizada del git commit es la de -m (mensaje) la cual guardará las modificaciones junto con una breve descripción de los mismos entre comillas.
- `git push` para trasladar nuestros cambios ejecutados en la terminal al GitHub. En el caso de que queramos realizar la acción a la inversa, es decir, trasladar cambios cometidos en el repositorio remoto al local utilizaremos `git pull`

### Configuración de un programa de edición de texto
El programa de edición de texto que se ha utilizado en la asignatura es nano. Al trabajar desde Mac hemos tenido que instalar el gestor de paquetes más común de Mac OS X `Homebrew` desde su página web  [Brew](https://brew.sh)
El programa de edición de texto que he instalado es nano. Para ello, reiterándome en que trabajo con Mac, lo hago ejecutando en la terminal `brew install nano`
x¡
