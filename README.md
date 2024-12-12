![image](https://github.com/user-attachments/assets/c6bdc139-8988-4846-a7d1-a7d92d481bb1)# HuamaniFigueroaExamen2425

![image](https://github.com/user-attachments/assets/ae311d2d-8493-4d1b-9e4c-f067e8e235c8)

Comprobamos la version instalada de git con el comando

**git --version**

![image](https://github.com/user-attachments/assets/5914c46f-ee81-4820-8dc4-5781eb1dcd1e)

Configuramos git a nuestro sistema y mostramos la configuracion con el comando

**git config --global user.name**
**git config --global user.email**
**git config --list**

![image](https://github.com/user-attachments/assets/6852fa9c-c6f8-4549-a762-a0772be51c8f)

Inicializamos un repositorio en el directorio creado

**git init .**

![image](https://github.com/user-attachments/assets/c5bb472f-6609-4478-b9f8-b2504a3466d7)

Creamos un nuevo archivo README.md y lo agregamos al area de staging, verificamos que se añadio

**git add README.md**
**git st** (alias creado - status)


![image](https://github.com/user-attachments/assets/cc51e546-0ee5-4577-95db-edb4580be43e)

Hacemos el primer commit 

**git commit -m ""**


![image](https://github.com/user-attachments/assets/0573af44-2981-4f2b-899f-9f2e68e708dc)

Creamos 4 archivos index.html testunitari.html style.css main.js

**touch**


![image](https://github.com/user-attachments/assets/0502eb3c-65bf-400e-8c65-5d99e5e1287e)

Agregamos contenido a los ficheros usando el editor de texto de linux nano

**nano index.html**


![image](https://github.com/user-attachments/assets/a8b67ca6-8400-4e4d-b374-097b29fca886)

Agregamos contenido a los ficheros usando el editor de texto de linux nano

  
![image](https://github.com/user-attachments/assets/57a3b7c5-50ee-4ece-b907-aaec075c3e7c)

Añadimos al area de stage solo los archivos .html y .css con el comando

git add *.html
git add *.css

mostramos el estado del repositorio 

**git st**


![image](https://github.com/user-attachments/assets/43767a46-5f44-4336-a286-4fafcdc13db3)

Sacamos el archivo testunitari.html del area de stage y hacemos el segundo commit, finalmente mostramos el historial

**git reset testunitari.html**
**git commit -m "2 - Estructura Basica"**
**git lg** -> (alias creado - git log)


![image](https://github.com/user-attachments/assets/713fc931-1335-461f-9223-6369c2405494)

Creamos una nueva branch y dentro de ella un archivo README.md y modificamos su contenido, finalmente añadimos el archivo y hacemos el tercer commit

**git branch documentacio**
**git change documentacio**
**git add**
**git commit -m ""**


![image](https://github.com/user-attachments/assets/73646ef2-38d3-4e68-93ab-25cfaef63e27)

Cambiamos a la rama principal y hacemos un merge

**git change master**
**git merge documentacio**


![image](https://github.com/user-attachments/assets/1edda467-b405-46ee-a1ca-1d935c89863e)

Configuramos el repositorio


![image](https://github.com/user-attachments/assets/4f009e78-62f0-483c-b5ae-61d188e23111)

Enlazamos el repositorio local con el repositorio remoto 
