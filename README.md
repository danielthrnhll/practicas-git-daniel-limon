Daniel Martin Limon Garcia
2630427
Creación y sincronización de repositorios con Git y GitHub
Crear un repositorio local utilizando Git, sincronizarlo con un repositorio remoto en GitHub y comprobar el flujo de trabajo en ambos sentidos
lo que hice fue crear los archivos solicitados, crear un repositorio local con el nombre solicitado, añadir los archivos al staging area y liego commitearlos, crear un repositorio en git y copiar la url, vincular los repositorios, despues modificar el archivo datos.txt desde git y descargarlo en el dispositivo, para luego modificar el archivo desde el dispositivo y subirlo a github, para por ultimo, añadir la informacion requerida al markdown desde github y subir la url a classroom

se utulizaron los siguientes comandos de git:
git init . se usa para iniciar un repositorio de git en la ubicacion actual
git branch -m "main" . se usa para asignarle un nombre a la rama principal
git status . se usa para ver el estatus de los archivos en el repositorio
git add . se usa para añadir los archivos del repositorio a la zona de staging
git commit -m "nombre" se usa para commitear los archivos que estan en la zona de staging y le da un nombre al commit y una id unica
git remote add origin url . se usa para vincular el repositorio local con el repositorio de github
git remote -v , se usa para ver si el repositorio local esta conectado con el repositorio de git
git push -u origin main . se usa para pasar los archivos del repositorio local al repositorio en git por primera vez
git pull origin main se usa para descargar los cambios del repositorio de git al repositorio local

el repositorio local se creo primero con un mkdir "nombre" y luego ya dentro de la carpeta se uso un git init y se configuro el nimbre de la rama principal con git branch -M main

primero se creo el repositorio en github y se copio su url, luego en el repositorio local se uso git remote add origin "url" y se verifico que estuvieran vinculados con git remote -v

se modifico el archivo datos.txt y se uso el comando git status para despues usar el git add . para pasarlo a la zona de staging y se creo un nuevo commit con git commit -m "commit" para por ultimo usar un git push

se modifico el archivo datos.txt y se realiza un commt desde github para despues descargarlo en el repositorio local con git pull

en el repositorio tenemos tanto el archivo datos.txt el cual es al que modificamos desde github para descargarlo local y modificamos local para volver a subirlo a gihub y el README.md el caul es este mismo archivo el cuak tiene toda esta informacion que el profesor nos pidio en classroom que es parte de la practica de git y github

mi conclusion sobre esta practica es que es de vital importancia ya que el control de versiones y el saber usar estas herramientas es fundamental para poder empezar a trabajar y poder empezar a programar. Ademas estas herramientas son basicamente obligatorias en multiples entornos de trabajo y te abren las puertas por que sin de mucha importancia
