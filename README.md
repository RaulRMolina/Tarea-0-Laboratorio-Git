# Tarea-0-Laboratorio-Git
## 1. **Crear un repositorio en local**

De primeras he creado la carpeta en local con el nombre "*TAREA 0 LABORATORIO GIT*".

He abieto el programa "*Visual Studio Code*", al apartado ***File*** y despues ***Open Folder ...*** y he seleccionado la carpeta.

Despues me he ido al apartado de ***Terminal*** y he abierto el terminal de GITBash, para iniciar el repositorio de GIT con el comando:

> git init

![alt text](<Captura 1.jpg>)

---

## 2. **Subir el repositorio a GitHub**

He creado un nuevo repositortio en *GitHub* y lo he conectado con el repositorio en local con el comando:

> git remote add origin *(enlace del repositorio de GitHub)*

![alt text](<captura 2a.jpg>)

Y lo siguente a sido verificar si la conexión se habia establecido correctamente mediante el comando:

>git remote -v

![alt text](<captura 2b.jpg>)

---

## 3. **Hacer un commit y un push**

En este apartado hemos creado el archivo *fichero1.js*, lo hemos añadido al staging utilizando el comando:

> git add .

Hemos realizado el commit con el mensaje descriptivo:

>git commit -m "fichero 1 creado"

Y hemos subido los cambios al repositorio de *GitHub*:

>git push --set-upstream origin master

![alt text](<captura 3.jpg>)

![alt text](<captura 3b.jpg>)

---

### 4. **Crear una rama**

Lo siguiente a sido crear una nueva rama llamada "***development***" y cambiarnos a ella:

> git branch development

> git checkout development

He realizado cambios en el *fichero1.js* y lo he añadido y hecho un commit a los cambios para posteriormente subir los cambios a *GitHub*:

> git add.

> git commit -m "cambio fichero 1"

> git push --set-upstream origin development

![alt text](Captura4.jpg)

---

## 5. **Hacer un merge**

Por ultimo he vuelto a la rama "*master*":

> git checkout master

He realizado el merge de la rama "*development*" a la rama "*master*"

> git merge development

Y he finalizado haciendo un push con todos los cambios al repositorio de *GitHub*:

> git push

![alt text](Captura5.jpg)

---