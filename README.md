Autores:
  Diego Arbeloa
  Diego Guerrero

Preguntas
1) Url del proyecto
  https://github.com/GesProDiego2024-25/GESPRO_Practica_3_Curso_2024_2025

2)
 - Guía de cómo se realiza toda la secuencia de acciones desde que nos posicionamos en un nuevo commit del repositorio Go Bees hasta que pasa a estar visible en nuestra rama master local. (25%)
    * posicionarte en el commit para subir cambios
    En el repositorio de go-bees te posiciones en la lista de commits en el deseado, puedes buscarlo mediante el mensaje del commit o por
    el id. Cuando ya lo tengas posicionado pulsas en "reset master to this commit">"hard-discard all changes".
    -->foto 7


    * tener master al dia y estar posicionado en master
    Tienes que estar posicionado en la rama master en gitkraken, para comprobar si hay cambios pulsas "fech all", esta herramienta nos dirá si hay
    cambios con respecto a la rama remota. Si hubiera cambios pulsamos push para sincronizar ambas ramas.
    -->foto 10

    * Crear rama a partir de tarea con nombre = a Gobees

    * posicionarse en rama en local
    --> foto 1
    Una vez creada la rama en el github, hacemos fetch en gitkraken para ver la rama, nos aparecerá en el cuadro de "remote",
    tendremos que pulsar dos veces sobre esa rama y nos aparecerá en el cuadro de local, ahí es cuando tendremos la rama en el
    repositorio local y podremos subir los cambios.

    * Añadir cambios de carpeta gobees a la carpeta P3
    Copias todos los archivos del repositorio de go-bees al repositorio local de la práctica 3.
    (no hay que copiar la carpta .git)
    -->foto 8

    * Git Stage all * Git commit
    --> foto 2
    Cuando guardemos los cambios en algún fichero del proyecto en atom, dicho fichero aparecerá	sobresaltado en naranja, esto querrá decir
    que no se ha sincronizado con el repositorio local, para ellos vamos a gitkraken y hacemos fetch para comprobar si ha habido cambios.
    Nos saldrá a la derecha que ha habido cambios entonces añadimos los cambios y hacemos el commit.

    * Create PRQ (de nuestro proyecto a nuestro proyecto) master
    Cuando ya tienes todos los commits de la rama hechos, subes todos los cambios de tu rama a github y alli creas la pull request para sincronizar tu rama con la rama master, estonces la pull request necesita la aprovacion de otras personas,y se debe de confirmar por al menos un miembro.

    * Merge PRQ y actualizar Master en local
    Una vez creada la pull request, otro miembro del equipo la confirmara, por lo que se sincronizara automaticamente la rama creada y la rama master. Para actualizar la master en local primero se hace un fetch, y luego pulsas pull para traer los cambios del repositorio remoto al local.
    IMPORTANTE: Cuando hagas el pull para sincronizar ambas ramas master(local y remoto) en gitkraken tienes que tener la rama master seleccionada.
