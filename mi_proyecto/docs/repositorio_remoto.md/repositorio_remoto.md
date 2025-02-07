# crear repositorio remoto en github
Inicia sesión en tu cuenta de GitHub.

En la esquina superior derecha selecciona "nuevo repositorio".

Elige un nombre para tu repositorio

Selecciona si quieres que el repositorio sea público o privado.

Haz clic en "Crear repositorio".
# conectar el repositorio local con el repositorio remoto 
En la página de tu repositorio en GitHub, copia la URL del repositorio (la encontrarás en la sección "Código".

Abre la terminal y navega a la carpeta raíz de tu repositorio local.

Agrega la URL del repositorio remoto a tu repositorio local (git remote add origin (URL_del_repositorio)
y reemplaza (URL_del_repositorio) con la URL que copiaste de GitHub.
# Sincroniza tu repositorio local con el repositorio remoto
por ultimo Si ya tienes commits en tu repositorio local

envía tus commits al repositorio remoto con el siguiente comando:

git push origin (rama en la que estas trabajando)


