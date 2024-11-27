## git init
# Inicializa un repositorio Git local en la carpeta actual.
- git init

## git remote add origin <URL_DEL_REPOSITORIO>
# Vincula tu repositorio local con un repositorio remoto en GitHub.
- git remote add origin https://github.com/tu-usuario/nombre-repo.git

## git add .
# Añade TODOS los archivos del proyecto al área de staging, preparándolos para un commit.
- git add .

## git commit -m "Mensaje"
# Crea un commit con los cambios en el área de staging. Incluye un mensaje descriptivo.
- git commit -m "Primer commit"

## git push -u origin main
# Sube los cambios al repositorio remoto en la rama 'main'.
# (Usa 'master' si tu rama principal se llama así).
- git push -u origin master

# Configuración opcional si Git no conoce tu usuario:
# git config --global user.name "TuNombre"
# Establece tu nombre de usuario globalmente para los commits.

# git config --global user.email "tu.email@ejemplo.com"
# Establece tu correo electrónico globalmente para los commits.
