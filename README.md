¡Entendido! Aquí está una lista consolidada con todos los comandos y explicaciones:

1. **Cambiar de rama:**
   ```bash
   git checkout nombre_de_la_rama
   ```

   Cambia a la rama especificada.

2. **Crear y cambiar a una nueva rama:**
   ```bash
   git switch -c nueva_rama
   ```

   Crea una nueva rama y cambia a ella.

3. **Guardar temporalmente los cambios en un stash:**
   ```bash
   git stash
   ```

   Guarda temporalmente los cambios locales en un stash para limpiar el directorio de trabajo.

4. **Recuperar los cambios del stash:**
   ```bash
   git stash apply
   ```

   Aplica los cambios guardados del stash al directorio de trabajo.

5. **Fusionar cambios de otra rama en "master":**
   - **Utilizando `git merge`:**
     ```bash
     git merge nombre_de_otra_rama
     ```
     Fusiona los cambios de "nombre_de_otra_rama" en la rama actual "master".
   - **Utilizando `git rebase`:**
     ```bash
     git rebase nombre_de_otra_rama
     ```
     Reorganiza la historia de "master" sobre la base de los cambios en "nombre_de_otra_rama". Asegúrate de entender las implicaciones de reescribir la historia antes de usar `rebase`.

6. **Realizar el push de los cambios a la rama "master":**
   ```bash
   git push origin master
   ```

   Sube los cambios a la rama "master" en el repositorio remoto.

Estos comandos te permitirán realizar diversas operaciones en Git, como cambiar de rama, guardar y aplicar cambios en un stash, fusionar o reorganizar cambios entre ramas y realizar push de cambios a un repositorio remoto. ¡Espero que esta lista consolidada sea útil! Si tienes más preguntas o necesitas más clarificaciones, no dudes en preguntar.
