# Exámen

## Repositorio masterpidgey-simulacion
- Creo un repositorio vacio en mi perfil de GitHub llamado masterpidgey-examens:
![1](/images/1.png)
- A continuación clonamos este repositorio en local con el comando **"git clone"** seguido del enlace del repositorio remoto:
![2](/images/2.png)

## README
- Nos ubicamos dentro del repositorio que hemos clonado y creamos un archivo README con algun contenido en su interior. Usamos el comando nano para crear y modificar dicho archivo:
![3](/images/3.png)
![4](/images/4.png)

## Commit inicial
- Ahora vamos a hacer el primer commit. Para ello debemos añadir los ficheros modificados con el comando "git add" seguido de los archivos modificados o tambien podemos usar "git add ." para agregar todos los ficheros modificados de una vez. Una vez agregados todos los ficheros podemos proceder a hacer el commit, para ello debemos usar el comando "git  commit -m" seguido del mensaje de dicho commit:
![5](/images/5.png)

## Push inicial
- El siguiente paso consiste en realizar un push del repositorio. Usaremos el comando "git push nombre_de_la_rama". En este caso la rama a la que debemos hacer push el la rama main:
![6](/images/6.png)

- Si vamos a nuestro repositorio de GitHub podemos ver que los cambios se 
han subido correctamente:
![7](/images/7.png)

## Ignorar archivos
- Creamos en el repositorio local un fichero llamado privado.txt con el comando "touch".
![8](/images/8.png)
- Creamos en el repositorio local una carpeta llamada privada con el 
comando "mkdir".
![9](/images/9.png)
- Para que tanto el archivo como la carpeta sean ignorados por git debemos crear un archivo llamado ".gitignore" y dentro de el debemos introducir el nombre del archivo y el nombre de la carpeta.
![11](/images/11.png)
![10](/images/10.png)

## Añadir fichero 1.txt
- Creamos en el repositorio local un fichero llamado 1.txt con el comando "touch".
![12](/images/12.png)

## Visualizar los commits realizados hasta el momento (el historial).
- Para visualizar los commits realizados hasta el momento debemos usar el comando **"git log"**.
![12](/images/history.png)

## Crear el tag v0.1
- Para crear un tag debemos usar el comando "git tag -a nombre-tag -m mensaje-tag". Pero antes debemos hacer commit. De esta manera podemos llevar un mejor seguimiento de las versiones.
![13](/images/13.png)

## Subir el tag v0.1
- Para subir la rama con el tag v0.1 debemos utilizar **"git push"** seguido de **"origin v0.1":**
![14](/images/14.png)

## Visualizar los commits realizados hasta el momento (el historial).
- Para visualizar los commits realizados hasta el momento debemos usar el comando **"git log"**.
![12](/images/history2.png)

## Crear una tabla
- Creamos una tabla en el README.md usando el comando **"nano"**:
![15](/images/15.png)
![15](/images/15-2.png)
- Ahora debemos realizar un push, ya que hemos realiazdo unos cambios.
![15](/images/15-3.png)

## Colaboradores
- Debemos agregar a Máximo como colaborador del repositorio. Debemos entrar en dicho repositorio - Settings - Collaborators - Add people:
![16](/images/16.png)

# Primeras Contribuciones
### Fork
- Realizar un fork del repositorio first-contributions:
![17](/images/17.png)
### Clone
- Clonamos el repositorio en local:
![18](/images/18.png)
### Branch
- Nos ubicamos en el repositorio clonado y creamos una nueva rama con el comando "git checkout -b nombre-rama". Gracia a este comando nos ubicamos dentro de la rama creada.
![19](/images/19.png)
### Cambios y Commit
- Creamos un md con nuestro nombre y después realizamos los pasos necesarios para realizar un commit **(git add, git commit)**:
![20](/images/20.png)
![20](/images/20-2.png)
![20](/images/20-3.png)
### Push
- Realizamos un push del repositorio con el comando "git push origin nombre-rama":
![21](/images/21.png)
### Submit
- Vamos al repositorio de GitHub y clicamos en "Compare and pull request":
![22](/images/22.png)
- Por último clicamos en "Create pull request":
![23](/images/23.png)
- Como podemos ver la rama no entra en conflicto y solo debemos esperar a que se acepte el pull request.
![24](/images/24.png)
- Finalmente Máximo ha realizado el merge.
![25](/images/25.png)
