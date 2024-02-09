He creado una carpeta donde realizar cambios con el comando mkdir(Crea un directorio) y me he metido dentro con cd y he iniciado con git init
Cree dos archivos con echo aunque se puede crear con nano y añadir texto. Añadimos el documento al workspace con git add
Validamos lor archivos con git commit -m "Texto de validacion" y realice cambios y los valide nuevamente con git commit
Para revertir los cambios utilize git log para ver el ultimo commit y con git reset --hard y el codigo del commit
Abrimos el documento para comprobar que se ha revertido el cambio con nanoç
Creamos un nuevo documento, lo añadimos con git add y lo validamos con git commit
Hacemos un git reset --hard HEAD y se reviert el ultimo commit. Hacemos un ls para comprobar que el documento recien creado no existe
Creamos un repositorio en github y lo conectamos con el repositorio con git remote add origin (enlace)
Creamos una rama con git checkout -b mirama, creamos dos archivos dentro de la rama y los validamos.
Fusionamos las dos ramas desde la principal con el comando git merge mirama y con git branch -d mirama eliminamos la otra rama
Sincronizamos los cambios con el repositorio remoto con git push origin master
Para crear una etiqueta utilizamos git tag (nombre) y con git push --tags lo sincronizamos con el remoto
Para realizar un clonado del repositorio hacemos git clone (repositorio) (copia)
Creamos una rama con git checkout -b mirama, creamos un archivo dentro de la rama lo validamos 
Lo subimos al repositorio remoto con git push origin mirama
Realizamos cambios en la rama main en un documento distinto lo validamos y lo subimos al repositorio remoto
Mostramos los commits realizados con git log --oneline
Fusionamos las dos ramas con gti merge, borramos la rama mirama lo sincronizamos con el remoto y mostramos las ramas con git branch -a
Creamos otra vez la rama mirama y realizamos cambios diferentes con nano al documento modificado en la rama principal
Las fusionamos con git merge pero no da error el documento se queda con el ultimo cambio realizado en la rama secundaria
Añadimos el README al remoto con una descripcion con comandos
