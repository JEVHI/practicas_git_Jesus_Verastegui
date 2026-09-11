### Nombre completo del estudiante:
- Jesús Emanuel Verástegui Hernández.
### Matrícula:
- 6730324
### Nombre de la práctica:
- Creación y sincronización de repositorios con Git y GitHub.
### Objetivo de la práctica:
- Crear un repositorio local utilizando Git, sincronizarlo con un repositorio remoto en GitHub y comprobar el flujo de trabajo en ambos sentidos:
    - Repositorio local → GitHub.
    - GitHub → Repositorio local.
### Descripción del procedimiento realizado
- La practica se trato de sincronisar un directorio de nuestro equipo a GitHub para despues mandar archivos de texto, modificarlos en GitHub para despues volverlos a descargar para modificarlos en la laptop y volverlos a subir.
### Comandos de Git utilizados
- `git init` lo use para crear un repositorio de la carpeta.
- `git branch`
    - `git branch --show-current` lo use para ver el nombre de la rama.
    - `git branch -M main` lo use para cambiar el nombre de la rama.
- `git status` lo use para ver en que sona estaban los archivos del repositorio.
- `git add`
    - `git add -A` lo use para mover los archivos de ""untraxed files" a la "staging zone".
- `git commit`
    - `git commit -m "README.md y datos.txt, ahi van de ida"`
- `git log` lo use para crear los commit.
- `git push`
    - `git push -u origin main` lo use para subir los commits a GiHub.
- `git pull`
    - `git pull origin main` lo use para descargar los archivos de GitHub.
- `git remote`
    ` git remote add origin git@github.com:JEVHI/practicas_git_Jesus_Verastegui.git` lo use para vincular mi repositorio con GitHub.
### Explicación de cómo se creó el repositorio local:
1. Primero cree la carpeta con `mkdir`.
2. Me movi a ella con `cd`. 
3. Por ultimo use `git init` para crear el repositorio.
### Explicación de cómo se vinculó el repositorio local con GitHub:
1. Entre a mi perfi de GitHub al apartaado de repositorios y para despues hacer clic en crear un nuevo repositorio y lo cree.
2. Ya creado me arojo el codigo SSH para vincular asi que lo copie.
3. Lo pegue junto con el comando `git remote add origin git@github.com:JEVHI/practicas_git_Jesus_Verastegui.git`
### Explicación de la sincronización Local → GitHub:
1. Use `git push -u origin main` para subir los archivos a GitHub.
2. Ya en mi perfil busque el repositorio, luego mi archivo de texto para editarlo, ya en el archivo hise clic en "view file", luego hise clic en la flecha que mira hacia abajo alado de la pluma y seleccione "On main branch", agregue la linea de texto requerida e hice clic en "commit changes...".
3. Para descargar los cambios me regrese a la termina y escribi `git pull origin main`
### Explicación de la sincronización GitHub → Local:
1. Para descargar un archivo de GitHub debemos regresar a la terminal y poner `git pull origin main` el archivo llegara a untraxed files.
### Descripción de los archivos contenidos en el repositorio:
- datos.txt: contiene una pequeña investigacion del comando `git branch`y tambien las lineas de texto que la practica pedia que se agregaran
- README.md:
    - Nombre completo del estudiante
    - Matrícula
    - Nombre de la práctica
    - Objetivo de la práctica
    - Descripción del procedimiento realizado
    - Comandos de Git utilizados
    - Explicación breve de la función de cada comando
    - Explicación de cómo se creó el repositorio local
    - Explicación de cómo se vinculó el repositorio local con GitHub
    - Explicación de la sincronización Local → GitHub
    - Explicación de la sincronización GitHub → Local
    - Descripción de los archivos contenidos en el repositorio
    - Conclusión personal sobre lo aprendido
### Conclusión personal sobre lo aprendido:
La practica me ayudo a reforzar los comandos vistos durante clase de Git, me siento mas fluido y rapido haciendo un commit pero tampoco crea que lo hago en 3 segundo como usted profe, reforze tambien lo que ya sabia de markdown y tambien aprendi a realizar las listas y los bloques para los comandos, tambien ya estoy un poco mas acostumbrado a GitHub ya incluso personalizando mi perfil, en conclusion me siento mas acostumbrado a la terminal.