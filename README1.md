| NOMBRE  | GITHUB |
| ------------- | ------------- |
| Máximo Fernández Riera  |  [Enlace](https://github.com/maximofernandezriera)  |

Echamos un vistazo a los logs (git log) y veremos que hay dos.

Realizamos los pasos anteriores dos veces más y comprobamos los logs.

Realizamos otro cambio en el archivo ACT53.py y guardamos. A continuación 
ejecutamos el comando "git diff", el cual nos permite ver los cambios que 
se han realizado en el archivo.

Realizamos un "git status", y como podemos ver el archivo ha sido 
modificado.
Para deshacer los cambios debemos ejecutar el comando " git checkout 
'archivo' ".


Creamos nuestro propio comando para listar los logs de otra manera. 
Debemos ejecutar lo siguiente: git config --global alias.ll 'log --all 
--decorate --graph --oneline'
En este caso hemos nombrado el comando como "ll" y para llamarlo debemos 
ejecutar lo siguiente: git ll

