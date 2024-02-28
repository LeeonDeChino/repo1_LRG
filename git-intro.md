# Pasos para configurar repositorios de Git en VS Code

  1.  Verificar la versión en la que te encuentras con el comando "_**git --version**_"

  2. Inicializar git con el comando "_**git init**_" (solo la primera vez)

  3. Realizar la configuración adecuada con los siguientes comandos:

    git config --global user.name "Leonardo Ramírez G"

    git config --global user.email leoragut @gmail.com

    git config --global user.ui true

    git config --global init.defaultBranch main

    git config --list

    git config --global core.editor "code --wait"

    git config --global -e

    git config --global core.autocrlf true

  4.  Escribir los siguientes comandos:

    git add . 
    
    git commit -m "Primer commit"

    git branch -M main

    git remote add origin https://github.com/usuario/repositorio.git

    git push -u origin main

5. Para los cambios que realicemos posterior a eso, repetiremos el mismo proceso "add, commit, push" a diferencia de que en el comando de push no será necesario escribirlo todo, solamente escribiremos "git push".

![Flujo Git](https://jonmircha.com/img/blog/git-flow.png)