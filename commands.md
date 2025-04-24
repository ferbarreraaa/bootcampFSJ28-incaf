**Inicializando nuestro repositorio**
git init

**Verificar el estado de nuestro repositorio**
git status
git status -s

**Agregando los archivos al repositorio**
git add <nombrearchivo>
git add .
git add --all

**Agregando los archivos al repositorio LOCAL y un comentario del cambio**
git commit -m <comentario>

**Subiendo los cambios al repositorio remoto**
git push origin <ramaprincipal>

### Comandos Adicionales
**configuración de usuario**
git config user.name
git config user.email
git config user.name <usuariogithub>
git config user.name <correogithub>

**Verificando repositorio remoto**
git remote -v

**Agregando repositorio remoto**
git remote add origin <enlacerepositoriogithub>