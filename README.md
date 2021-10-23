# Git
Aprendiendo a usar Git

 # GIT
  Aprendiendo a usar bien GIT

  Aquí subiré progresivamente un proyecto usando git.

  ## git init
  Se hace dentro del proyecto que se desea controlar, y sirve para hacer que git reconozca dicho proyecto como a ser controlado y   cree el Working Space

  ## git status
  Sirve para saber el estado del work space; es decir, cuales <files> estan o no siendo gestionados por git (que se encuentren en   Work Space).
  
  ## git add <file>
  Se usa para añadir los archivos del proyecto que aun no están siendo gestionados por git (se añaden al Work Space).
  
  ## git add .
  Se usa para agregar todo lo modificado en el entorno de trabajo
  
  ## git config --global user.email "<email del GITHUB, de quien va a administrar el proyecto>"
  Se usa para configurar  el EMAIL de quien va realizar la administración de las versiones del proyecto. Se debe crear una cuenta   en github en caso de que no la tenga ya.
  
  ## git config --global user.name "<Nombre de quien va a administrar el proyecto>"
  Se usa para configurar  el nombre de quien va realizar la administración de las versiones del proyecto.
  
  ## git commit
  ("i" en Linea de Comandos GIT despues de el commit para insertar una descripcion del commit), luego "esc" y ":wq" para salir de   la nueva interfaz de linea de comandos.
 
 ## git reset HEAD~Numero de commits que se desean deshacer
 Sirve para deshacer un numero n de commits.

  # git commit -m "descripción del comit"
  Otra forma de hacer commit
  
  ## git log
  Muestra las caracteristicas y el codigo del ultimo commit
  
  
  
  ## git checkout -- nombre_del_archivo_modificado_al_que_no_se_le_ha_hecho_commit
  Sirve para devolver un archivo que estemos modificando, al estado anterior que haya sido guardado (commit)

  ## git diff NOMBRE_DEL_ARCHIVO
  Sirve para saber la diferencia que se tiene entre un add anterior y la versión actual que no ha sido agregada

  ## Archivo .gitignore
  Se utiliza para hacer que todos los archivos cuyos nombres estén escritos allí, sean ignorados en sus cambios por el CVS. Se       puede hacer add solo al .gitignore para actualizar dicha lista y no cada archivo a ignorar por separado.

  ## git branch
  Sirve para saber las ramas que tiene el proyecto
  
  ## git branch NOMBRE_DE_LA_RAMA
  Sirve para crear una nueva rama del proyecto
 
 ## git checkout -b nueva_rama
 Crea nueva rama y nos lleva automaticamente a ella
  
  ## git checkout NOMBRE_DE_LA_RAMA
  Sirve para pasarnos a la rama "NOMBRE_DE_LA_RAMA"
  
  ## git remote add origin URL_DEL_REPOSITORIO
  Sirve para agregar el origen del repositorio en el cual de va a almacenar el proyecto
  
  ## git push -u origin master
  Sirve para subir todo lo almacenado en nuestro "Staging Area"

  ## git clone URL_REPO_CLONAR
  Sirve para clonar en nuestro pc un repositorio que hay en github
  
  ## o enviar un repositorio existente desde la línea de comandos
- git remote add origin URL_DEL_REPOSITORIO_AL_QUE_VAMOS_A_SUBIR_NUESTRO_PROYECTO
- git branch -M main
- git push -u origin main

