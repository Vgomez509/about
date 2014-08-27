Principales comandos Git
==================


A continuacion se describen las funciones mas habituales


Terminal bash / Git bash
---------------

#### Para descargarse por primera vez el repositorio

* cd a la carpeta donde queremos tener el proyecto: (ej. $HOME/Proyectos/CanHack)

* git clone https://USUARIO@github.com/CanHack/about.git, siendo USUARIO nuestro usuario de GitHub 

#### Para añadir ficheros al proyecto

Por ejemplo: ../CanHack/about

Añadimos las carpetas y ficheros que queramos y trabajamos en ellos,
a continuación:

git add --all

seguidamente: 

git commit -m 'Un mensaje descriptivo de los cambios que hemos hecho' (Es obligatorio poner algo en el mensaje')

Consolidamos los cambios con el resto: 

git pull origin master

Y finalmente subimos nuestros cambios: 

git push origin master 

(Nos pedirá usuario y contraseña: ponemos los de GitHub).



