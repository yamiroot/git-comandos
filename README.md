<p align="center"><a href="https://ugeek.github.io/blog/images-blog/git.png"><img src="./public/logo.png" width=80px></a></p>
<h1 align="center">Comandos Git</h1>


# Git
Sistema de control de versiones.


## Sistema de control de versiones (VSC)
Es un sistema que registra los cambios de uno o más archivos, con la finalidad de poder 
recuperar a futuro alguna de sus versiones.

### Repositorio Local
Son los archivos y sus respectivas versiones que se encuentran en nuestro equipo.

Posee dos partes:

- Working Directory: 
Es nuestro directorio de trabajo.

- Staging area:
Es el espacio en donde se encuentran los archivos a los que Git les debe hacer seguimiento y 
que en el algún momento se convertirán en una nueva versión del proyecto

### Repositorio remoto
Es nuestro repositorio en alguna plataforma de almacenanmiento de proyectos. Por ejemplo: Github, 
Gitlab, etc.


## Instalación

### En Linux:
La distribución de Kali linux viene por defecto con `git` instalado. Si alguna distribución basada 
en debian no lo tiene se debería seguir los siguientes comandos:

```
$apt-get update
$apt-get install git
```

Para verificar si la instalación fue correcta:

```
$git --version
```

Pero la versión descargada puede que sea anterior a la versión más reciente de Git. Para [descargar 
la versión más reciente de Git](https://openwebinars.net/blog/como-instalar-git-en-ubuntu/), puede 
hacerlo desde el código fuente.

##### Nota:
Kali Linux es la versión mejorada y renovada de la distro BackTrack, creada por Offensive Segurity.
La distro se basa en Debian, mientras que Backtrack se fijó en Ubuntu para la creación de su programación.

### En MAC OS X:
Si usas una versión de Mac OS X como Mavericks (10.9) o anterior a esa, puedes abrir la terminal y
escribir simplemente `git`. Si te da alguna respuesta, quiere decir que ya lo tienes instalado.

En caso no lo tengas instalado, puedes ingresar a este [link](https://git-scm.com/download/mac). Esto 
descargará un instalador al cual deberás seguir las instrucciones que te indique (muy similar a Windows
pero con muchos menos pasos).

Para verificar si la instalación fue correcta puede utilizar el comando `git --version`.

### En Windows:
Para la instalación de [Git](https://git-scm.com/) deberá descargar una herramienta llamada `Git Bash`.

#### Git Bash:
Es una herramienta de Git para el sistema de Windows, que nos permite ejecutar comandos como si 
estuviéramos en Linux o MAC OS X. El uso de Git Bash se debe a que el Command Prompt (o terminal 
de Windows) no soporta comandos UNIX.


## Configuración

Debemos establecer nuestro username y dirección de correo electrónico de nuestra cuenta de Githu, ya que
Git utilizará estos datos para la confirmación de cambios (commits).

- Configura tu nombre de usuario con el siguiente comando:

```
git config --global user.name miUserName
```

- Configura tu correo electrónico con el siguiente comando:

```
git config --global user.email miemail@domain.com
```

Para visualizar nuestra lista de configuraciones podemos hacerlo con el siguiente comando:

```
git config --list
```







