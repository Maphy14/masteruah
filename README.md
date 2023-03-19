# masteruah
<p>Aviso: no se explicarán los ejercicios en los que queda muy claro el propósito del comando.</p>
<ol>
    <li>
        Crear un repositorio en vuestro GitHub llamado **masteruah**.
    </li>   
        (Véase nombre del repositorio).
    <li>
        Clonar vuestro repositorio en local.
    </li>
        git clone https://github.com/Maphy14/masteruah
    <li>
        Crear (si no lo habéis creado ya) en vuestro repositorio local un documento **README.md**.
    </li>
        git add README.md
    <li>
        Añadir al README.md los comandos utilizados hasta ahora y hacer un coomit inicial con el mensaje **commit inicial**.
    </li>
        git commit -m "Commit inicial"
    <li>
        Subir los cambios al repositorio remoto.
    </li>
        git push
    <li>
        Añadir fichero **1.txt** al repositorio local.
    </li>
        git add 1.txt
    <li>
        Crear un tag **v0.1**.
    </li>
        git tag v0.1
    <li>
        Subir los cambios al repositorio remoto.
    </li>
        <b>Primero, usamos un comando que permita subir directamente los tags al repositorio remoto.</b><br/>
        git push --tags<br/>
        <b>Después, se va a utilizar el siguiente comando para hacerle commit al archivo "1.txt".</b><br/>
        git commit -m "Añadir fichero 1.txt"<br/>
        <b>Por último, hacemos un push al archivo para que se suba al repositorio remoto.</b><br/>
        git push
    <li>
        Crear una rama **v0.2**.
    </li>
        git branch v0.2
    <li>
        Posiciona tu carpeta de trabajo en esta rama.
    </li>
        git checkout v0.2
    <li>
        Añadir un fichero **2.txt** en la rama **v0.2**.
    </li>
        git add 2.txt
    <li>
        Subir los cambios al repositorio remoto.
    </li>
        <b>Primero, hacemos un commit al archivo 2.txt</b><br/>
        git commit -m "Añadir fichero 2.txt a la rama v0.2"</br>
        <b>Segundo, subimos el archivo desde la rama v0.2 al repositorio remoto con un push</b><br/>
        git push -u origin v0.2
    <li>
        Posicionarse en la rama **master** (en mi caso, la rama se llama "main").
    </li>
        git checkout main
    <li>
        Hacer un merge de la rama **v0.2** en la rama **master**.
    </li>
        git merge v0.2
    <li>
        En la rama **master** poner **Hola** en el fichero **1.txt** y hacer commit.
    </li>
        <b>Primero, usamos el comando echo para sobreescribir los datos del fichero y añadirle "Hola".</b><br/>
        echo "Hola" > 1.txt</br>
        <b>Después, añadimos el archivo modificado a la rama main usando add.</b><br/>
        git add 1.txt<br/>
        <b>Para terminar, usamos commit para confirmar los cambios.</b><br/>
        git commit -m "Añadido "Hola" al fichero 1.txt en la rama main"
    <li>
        Posicionarse en la rama **v0.2** y poner **Adios** en el fichero "1.txt" y hacer commit.
    </li>
        <b>Primero, usamos checkout para pasarnos a la rama v0.2</b><br/>
        git checkout v0.2</br>
        <b>Después, usamos el comando echo para sobreescribir los datos del fichero y añadirle "Adios".</b><br/>
        echo "Adios" > 1.txt</br>
        <b>Luego, añadimos el archivo modificado a la rama v0.2 usando add.</b><br/>
        git add 1.txt<br/>
        <b>Para terminar, usamos commit para confirmar los cambios.</b><br/>
        git commit -m "Añadido "Adios" al fichero 1.txt en la rama v0.2"
    <li>
        Posicionarse de nuevo en la rama **master** y hacer un merge con la rama **v0.2**
    </li>
        <b>Primero, usamos checkout para cambiar de rama.</b><br/>
        git checkout main<br/>
        <b>Segundo, usamos merge para combinar los archivos de ambas ramas.</b><br/>
        git merge v0.2
    <li>
        Listar las ramas con merge y las ramas sin merge.
    </li>
        <b>Para las ramas con merge</b></br>
        git branch --merge</br>
        <b>Para las ramas sin merge</b></br>
        git branch --no-merge</br>
    <li>
        Arreglar el conflicto anterior y hacer un commit.
    </li>
        <b>Usamos el comando vin para acceder a ambas versiones del fichero, y una vez dentro, eliminamos una de las dos.</b></br>
        vim 1.txt</br>
        <b>Luego, volvemos a añadir el fichero a la rama.</b></br>
        git add 1.txt</br>
        <b>Hacemos un commit para confirmar los cambios.</b></br>
        git commit -m "Se ha resuelto el conflicto en el fichero 1.txt"</br>
    <li>
        Crear un tag **v0.2**
    </li>
        git tag v0.2
    <li>
        Borrar la rama **v0.2**
    </li>
        git branch -D v0.2
    <li>
        Listar los distintos commits con sus ramas y sus tags.
    </li>
        git log --oneline --decorate --all
    <li>
        Poner una foto en vuestro perfil de GitHub.
    </li>
        Se puede acceder a dicha opción desde el apartado "Editar usuario", en el menú de inicio de la cuenta.
        <img src="Práctica Github 21.png"/>
    <li>
        Poner el doble factor de autentificación en vuestra cuenta de GitHub.
    </li>
        <b>Para activarlo, es necesario acceder a la configuración del usuario, y pinchar en el apartado "Password and <br/>                authentication".<br/>
    <img src="Práctica Github 22.png"/><br/>
    <img src="Práctica Github 23.png"/>
    <li>
        Añadir al README.md los comandos utilizados hasta ahora y hacer un coomit inicial con el mensaje **commit inicial**.
    </li>
        git commit -m "Commit inicial"
    <li>
        Añadir al README.md los comandos utilizados hasta ahora y hacer un coomit inicial con el mensaje **commit inicial**.
    </li>
        git commit -m "Commit inicial"
    <li>
        Añadir al README.md los comandos utilizados hasta ahora y hacer un coomit inicial con el mensaje **commit inicial**.
    </li>
        git commit -m "Commit inicial"
    <li>
        Añadir al README.md los comandos utilizados hasta ahora y hacer un coomit inicial con el mensaje **commit inicial**.
    </li>
        git commit -m "Commit inicial"
    <li>
        Añadir al README.md los comandos utilizados hasta ahora y hacer un coomit inicial con el mensaje **commit inicial**.
    </li>
        git commit -m "Commit inicial"

    
    
    
</ol>

<table>
    <tr>
        <td>
        Nombre
        </td>
        <td>
        Enlace github
        </td>
    </tr>
    <tr>
        <td>
        Nombre
        </td>
        <td>
        Enlace github
        </td>
    </tr>
</table>
