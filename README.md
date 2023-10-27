# examenDAM
Para utilizarlo en el examen

## Pasos a seguir

    1. Nos situamos en GitHub en el repositorio que vamos a hacer fork

    2. Pulsamos en fork

    3. Renombramos nuestro repositorio

    4.  Nos situamos en la carpeta local donde vamos a clonar, esto lo hacemos con el comando cd
    
    2. Clonamos y nombramos con el comando git clone -o nombre https://repositorio a clonar

    3. Nos colocamos en la carpeta local donde hayamos clonado

    5. Hacemos modificaciones, en este caso en el README.md

    6. Añadimos un proyecto en java en la misma carpeta

    7. Añadimos al .gitignore los archivos que no queremos que se incluyan. Nos situamos en el IntelliJ -> Git -> Add to .gitignore

    8. En el menú que hay en la derecha, los archivos añadidos al .gitignore deberán ponerse en verde en vez de en rojo

    9. Añadimos todos los ficheros a los que queremos hacer un commit. git add src/ README.md/ 

    10. Hacemos el commit. git commit -m "Texto"

    11. Cambiamos la rama a main. git branch -M main

    12. Subimos los cambios al repositorio. git push <nombre que le hayas puesto al clonarlo> main

    13. Añadimos el .gitignore. Para ello nos colocamos en la carpeta .idea y después git add .gitignore

    14. Hacemos un commit para dejar reflejado el añadido del .gitignore y los cambios en el README

    15. Lo subimos al repositorio git push <nombre que le hayas puesto al clonarlo> main



