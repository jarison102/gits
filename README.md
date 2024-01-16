

1. **Cambiar a la rama "master":**
   ```bash
   **git checkout master**
   ```

   Cambia al la rama principal "master".

2. **Guardar temporalmente los cambios en un stash si es necesario:**
   ```bash
   **git stash**
   ```

   Guarda temporalmente los cambios locales en un stash para limpiar el directorio de trabajo.

3. **Fusionar o reorganizar los cambios de la otra rama en "master":**
   - **Utilizando `git merge`:**
     ```bash
     **git merge nombre_de_otra_rama**
     ```
     Fusiona los cambios de "nombre_de_otra_rama" en la rama actual "master".
   - **Utilizando `git rebase`:**
     ```bash
     **git rebase nombre_de_otra_rama**
     ```
     Reorganiza la historia de "master" sobre la base de los cambios en "nombre_de_otra_rama".

     Asegúrate de entender las implicaciones de reescribir la historia antes de usar `rebase`.

4. **Aplicar el stash si guardaste cambios temporalmente:**
   ```bash
   **git stash apply**
   ```

   Aplica los cambios guardados del stash al directorio de trabajo.

5. **Realizar el push de los cambios a la rama "master":**
   ```bash
   **git push origin master**
   ```

   Sube los cambios a la rama "master" en el repositorio remoto.

# Cambiar a la rama "master"
**git checkout master**

# Guardar temporalmente los cambios en un stash si es necesario
**git stash**

# Fusionar o reorganizar los cambios de otra rama en "master"
# Utilizando `git merge`:
**git merge nombre_de_otra_rama**
# Utilizando `git rebase`:
**git rebase nombre_de_otra_rama**
# Asegúrate de entender las implicaciones de reescribir la historia antes de usar `rebase`.

# Aplicar el stash si guardaste cambios temporalmente
**git stash apply**

# Realizar el push de los cambios a la rama "master"
**git push origin master**

# Cambiar a una rama existente
**git switch nombre_de_la_rama**

# Crear una nueva rama y cambiar a ella
**git switch -c nueva_rama**


