# RepoGIT

<hr>

# Descripción

<hr>

## Objetivos

<hr>

1. __Crear un repositorio en local__
<br>
    - Abre tu terminal y navega hasta el directorio donde deseas crear el repositorio.
    - Crea una carpeta con el nombre del repositorio.
    - Ingresa a la carpeta que acabas de crear.
    - Inicializa el repositorio de Git.

<br>

> Comenzamos abriendo el terminal de git, en el cual navegaremos hasta el escritorio y crearemos una carpeta llamada RepoGIT donde crearemos nuestro proyecto, ingresaremos en ella y inicializaremos el repositorio de git.

<img src="/capturas/1. Crear un repositorio en local.png">

<br>
<br>

2. __Subir el repositorio a GitHub__
<br>
    - Crea un nuevo repositorio en GitHub.
<br>
    > Nos conectamos a nuestro github con nuestra cuenta y creamos un nuevo repositorio con el nombre de RepoGIT.
    <img src="/capturas/Crea un nuevo repositorio en GitHub..png">
<br>
    - Copia el URL del repositorio que acabas de crear en GitHub
<br>
    > Copiamos la url del repositorio que acabamos de copiar por medio de SSH.
    <img src="/capturas/Copia el URL del repositorio que acabas de crear en GitHub.png">
<br>
    - Conecta tu repositorio local con el repositorio en GitHub.
<br>
    > Conectamos el repositorio local con el remoto por medio de este comando:
    <img src="/capturas/Conecta tu repositorio local con el repositorio en GitHub..png">
<br>
    - Verifica que la conexión se haya establecido correctamente.
<br>
    > Verificamos la conexion con este comando que muestra las rutas establecidas.
    <img src="/capturas/Verifica que la conexión se haya establecido correctamente..png">
    O con un push:
    <img src="/capturas/push.png">

<br>
<br>

3. __Hacer un commit y un push__
<br>
    - Crea un archivo en la carpeta del repositorio.
<br>
    > Creamos un archivo nuevo llamado imdex.html.    
    <img src="/capturas/1. Crear un repositorio en local.png">
<br>
    - Añade el archivo al staging.
<br>
    > Añadimos el archivo al staging con el siguiente comando de git:
    <img src="/capturas/Añade el archivo al staging..png">
<br>
    - Crea un commit con un mensaje descriptivo.
<br>
    > Creamos un commit con un mensaje descriptivo con el sigueinte comando de git:
    <img src="/capturas/Crea un commit con un mensaje descriptivo..png">
<br>
    - Sube los cambios al repositorio en GitHub.
<br>
    > Subimos los cambios al repositorio de GitHub con un push.
    <img src="/capturas/Sube los cambios al repositorio en GitHub..png">

<br>
<br>

4. __Crear una rama__
<br>
    - Crea una rama nueva llamada "development".
<br>
    > Creamos una nueva rama con el comando:
    <img src="/capturas/Crea una rama nueva llamada development..png">
<br>
    - Cambia a la nueva rama.
<br>
    > Cambiamos a la nueva rama con el comando:
    <img src="/capturas/Cambia a la nueva rama..png">
<br>
    - Realiza algunos cambios en el archivo que creaste.
<br>
    > Realizamos cambios en index.html.
    <img src="/capturas/Realiza algunos cambios en el archivo que creaste..png">
<br>
    - Añade y haz un commit con los cambios en la rama "development".
<br>
    > Añadimos y hacemos un commit con los cambios a la rama development.
    <img src="/capturas/Añade y haz un commit con los cambios en la rama development..png">
<br>
    - Sube los cambios a Github.
<br>
    > Subimos los cambios con push a GitHub.
    <img src="/capturas/Sube los cambios a Github..png">

<br>
<br>

5. __Hacer un merge__
<br>
    - Vuelve a la rama "main".
<br>
    > Volvemos a la rama master.
    <img src="/capturas/Vuelve a la rama main.png">
<br>
    - Haz un merge de la rama "development" a la rama "main".
<br>
    > Realizamos un merge de la rama development a la rama main.
    <img src="/capturas/Haz un merge de la rama development a la rama main..png">
<br>
    - Si no hay conflictos, los cambios realizados en la rama "development" se incorporarán a la rama "main".
<br>
    - Haz un push de los cambios al repositorio en GitHub.
<br>
    > Como no a habido conflicto hacemos un push hacia el repositorio en GitHub.
    <img src="/capturas/Haz un push de los cambios al repositorio en GitHub.png">      