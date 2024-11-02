# Practica 1  (Git y GitHub)

## Descripcion
Este programa creado en Python nos imprime un mensaje en la consola: "Hola Git". Esta practica tiene como objetivo introducirnos y aprender a utilizar Git y GitHub incluyendo la creacion de un repositorio, subida de archivos (y tambien su seguimiento) y el manejo de commits.

## Instrucciones de uso
Para ejecutar el programa "HolaMundo.py" se recomienda tener un entorno de desarrollo (IDE) como Visual Studio Code y tener instalado Python en el equipo, al igual que tener sus extensiones recomendadas y tener una configuracion correcta tanto del IDE como de Python.

Estos son los pasos a seguir:

1. Abrimos Visual Studio Code
2. Seleccionamos la carpeta del proyecto "ProyectoEjemploGit" que contiene el archivo "HolaMundo.py"
3. Hacemos clic en el archivo "HolaMundo.py" en el panel de archivos que tenemos a la izquierda para abrirlo
4. Para ejecutar el programa, tenemos estas opciones para poder hacerlo:
   - Hacemos clic en el boton "Run Python File" o "Ejecutar archivo Python" (el ícono de play) en la esquina superior derecha.
   - Usar el atajo de teclado  F5 para ejecutarlo.

   Finalmente la salida "Hola Git" aparecera en la consola que esta en la parte inferior de Visual Studio Code

## Comandos utilizados 
Este listado de los comandos de Git fueron lo que utilice durante el proceso.

- git config: para asociar los commits con un autor
- git init: inicializamos  un nuevo repositorio
- git add (file): añadimos un archivo 
- git commit -m "(mensaje)": realizamos un commit con un mensaje 
- git status: nos muestra el estado actual del repositorio
- git remote add origin (URL): conectamos el repositorio local a un repositorio remoto en GitHub
- git push -u origin master: subimos los cambios al repositorio remoto

## Notas sobre el archivo .gitignore
1. Creamos un archivo llamado ".gitignore", y la finalidad de este, se creo para evitar que archivos innecesarios sean añadidos al repositorio. En esta ocasion hemos configurado ".gitignore" para ignorar todos los archivos con la extensión ".log" añadiendo la línea " *.log ", esto para asegurarnos que archivos como "debug.log" no se suban al repositorio

2. Al ejecutar el archivo "HolaMundo.py", el programa nos debe mostrar el siguiente mensaje en la terminal de Visual Studio:
Hola Git


Este mensaje confirma que el programa se ejecutó correctamente.

3. Para verificar que debug.log no se subio, podemos hacer lo sigueinte:

    -Ejecutamos el comando "git status" para verificar el estado de los archivos en el repositorio

   En caso de que el archivo "debug.log" no nos aparezca en la lista de archivos rastreados o no rastreados, significa que Git si lo esta ignorando correctamente gracias a la configuracion que hicimos en ".gitignore". Finalmente esto nos puede confirmar que el archivo "debug.log" no se ha subido al repositorio y esta siendo excluido como lo esperabamos

  



