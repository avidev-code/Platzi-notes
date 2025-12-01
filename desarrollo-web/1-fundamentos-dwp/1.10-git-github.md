# <img width="32px" src="https://static.platzi.com/media/achievements/badge-8-738d990a-87e0-488a-b069-6ac164a2790c.png"/> 🎓 Curso de Git y GitHub

  <br/>

  👉🏻 [Ve al Curso de Fundamentos de JavaScript](https://platzi.com/cursos/gitgithub)
  
  <br/>

  | Nombre del profesor | Perfil profesional | Fecha publicación del Curso |
  | :--- | :--- | :--- |
  | **Amin Espinoza** | **Sr. Software Development Engineer** <br/> Senior Software Engineer en Microsoft | 📅 Publicado el **26 de octubre de 2024** |
  <br/>

> Gestiona versiones, colabora en equipo y publica proyectos usando Git y GitHub. Controla ramas, pull requests, releases, seguridad y automatizaciones con herramientas clave de la industria.

---

## Clases del curso

### 🔰 Fundamentos de Git y control de Versiones
<details>
  <summary>01/42 - Control de Versiones con Git y GitHub: De Básico a Avanzado</summary>
  <br/>

  ### Antes de GIT: el desorden absoluto

  Antes de **GIT**, los desarrolladores gestionaban versiones manualmente, lo que era ineficiente y propenso a errores. Su llegada revolucionó la industria gracias a su simplicidad, convirtiéndose en el estándar para la programación.
  <br/>

  ### ¿Quién creó GIT?
  El creador de **GIT** es **Linus Torvalds**, el mismo que desarrolló el kernel de **Linux**. Diseñó **GIT** para resolver sus propios problemas de control de versiones, y su impacto ha sido tan grande que hoy en día es una herramienta esencial en el desarrollo de software.
  <br/>

  ### ¿Por qué deberías aprender GIT?
  Desde que escribes tu primer **"Hola, mundo"**, necesitas gestionar tu código de manera eficiente. Aprender **GIT** es fundamental para:

  - **Trabajar en equipo** dentro de una empresa.
  - **Publicar tu trabajo** individual y colaborar en proyectos de otros desarrolladores.
  - **Mantener un historial de cambios** y revertir errores sin perder el progreso.

  Hoy en día, casi ningún producto de software es creado por una sola persona. Siempre hay equipos detrás, y **GIT** es la clave para que todo funcione sin problemas.
  <br/>

  ### GIT y GITHUB: aliados del desarrollo
  - **GIT** funciona en tu máquina local mediante la terminal o editores como **Visual Studio Code**.
  - Sus comandos principales incluyen: **merge, pull, commit, push**, entre otros.
  - Si deseas colaborar con otros, usarás plataformas como **GITHUB**, donde podrás almacenar y gestionar versiones de código en la nube.

  **GITHUB** ha crecido enormemente en los últimos años, añadiendo herramientas que aumentan la productividad y facilitan el trabajo en equipo.
  <br/>

  ### ¿Qué aprenderás en este curso?
  En este curso, aprenderás a:

  ✔ Configurar **GIT** en tu computadora.

  ✔ Crear repositorios locales y modificar archivos.

  ✔ Trabajar con ramas y fusionarlas correctamente.

  ✔ Gestionar un flujo de trabajo profesional con **GIT y GITHUB**.

  ✔ Integrar colaboradores, revisar cambios y resolver conflictos.

  ✔ Utilizar herramientas avanzadas como **Codespaces** y automatizaciones.


  ### Tu ventaja sobre otros desarrolladores
  Muchos dicen que saben **GIT**, pero solo manejan lo básico. En este curso, irás más allá: no solo aprenderás a hacer **commit, pull y push**, sino que también dominarás herramientas avanzadas que te harán destacar en la industria.
  <br/>

  ### ¿Qué necesitas para empezar?
  Solo conocimientos básicos de la terminal, como:
  - Crear y mover archivos y directorios.
  - Entender lo esencial de cualquier lenguaje de programación.

  Si quieres destacar en la industria del software, la próxima clase es tu siguiente paso. ¡Nos vemos allá! 🚀
  <br/><br/>

</details>

<details>
  <summary>02/42 - Fundamentos de Git: Configuración y Comandos Básicos</summary>
  <br/>

  > Resumen  Trabajar con Git en la terminal permite a los desarrolladores gestionar sus proyectos de manera eficiente. A continuación, revisamos cómo instalar, configurar y utilizar Git en Linux, Mac y WSL de Windows, junto con algunas recomendaciones prácticas para dominar los comandos iniciales de esta herramienta.

  ## ¿Cómo confirmar que Git está instalado en tu sistema?
  Para verificar la instalación de Git:

  1. Abre la terminal y escribe el comando `git --version`.
  2. Si el comando devuelve un número de versión, Git está listo para usarse.
  3. Si no aparece la versión, revisa los recursos adjuntos donde se explican las instalaciones para cada sistema operativo.

  ## ¿Cómo crear y preparar el primer proyecto con Git?
  El primer paso para crear un proyecto en Git es:

  1. Limpia la terminal para evitar confusión visual.
  2. Crea una carpeta para el proyecto con `mkdir nombre_del_proyecto`.
  3. Navega a la carpeta con `cd nombre_del_proyecto`.

  ## ¿Cómo inicializar un repositorio en Git?
  Al estar dentro de la carpeta de tu proyecto, inicia el repositorio con:

  - `git init`: Esto crea la rama inicial “master” por defecto.

  Si prefieres la rama principal como “main”:

  1. Cambia la configuración global escribiendo `git config --global init.defaultBranch main`.
  2. Actualiza la rama en el proyecto actual con `git branch -m main`.

  ## ¿Cómo personalizar tu configuración de usuario en Git?
  Configura el nombre de usuario y correo electrónico de Git, que identificará todas tus contribuciones:

  1. Usa `git config --global user.name "Tu Nombre o Apodo"`.
  2. Configura el correo electrónico con `git config --global user.email "tu.email@example.com"`.

  **Tip:** Si necesitas corregir algún error en el comando, puedes usar la tecla de flecha hacia arriba para recuperar y editar el último comando escrito.

  ## ¿Cómo confirmar la configuración de Git?

  Para revisar tu configuración, ejecuta:

  - `git config --list`: Aquí verás los datos de usuario y el nombre de la rama principal.

  Esta configuración se aplicará a todos los repositorios que crees en adelante.

  ## ¿Qué hacer si olvidas un comando?

  Git incluye un recurso rápido y útil para recordar la sintaxis de comandos:

  1. Escribe `git help` en la terminal.
  2. Navega la lista de comandos disponibles y consulta la documentación oficial de cada uno cuando sea necesario.

  ---

  - `git config` > Configura a nivel repositorio
  - `-global` > Especifica que esta configuración es a nivel global afectando a todos los repositorios usados en el usuario actual
  - `init.defaultBranch main` > esto cambia la configuracion global al aplicar el comando `git init` para que cambie de master a main, ya que actualmente se conoce de esa manera
      
      AYUDA DE GIT MEDIO LA TERMINAL
      
  - `git --help` Esto despliga en la terminal todas la ayudas o manuales que tiene git en inglés
      
      COMANDO QUE DIFINE NOMBRE DE USUARIO ASOCIADO A LOS COMMITS
      
  - `git config` > utiliza la configuración del git
  - `-global` > indica que se aplica a nivel global
  - `user.name “pablordata”` > asocia el nombre de usuario que es el autor de los commits
      
      COMNADO QUE DEFINE EL CORREO ASOCIADO A LOS COMMITS
      
  - `git config` > utiliza la configuraciones del git
  - `-global` > indica que se aplica a nivel global
  - `user.email “pablor.data@gmail.com”` > asocia el correo del usuario que es el autor de los
      
      COMANDO QUE MUESTRA LA CONFIGURACIÓN DEL ENTORNO DEL GIT
      
  - `git config --list` > Muestra la configuración completa y activa en el entrono de git esto es a nivel del sistema, global y local### EJEMPLO DE SALIDA TIPICA`user.name=pablordata [user.email=pablor.data@gmail.com](mailto:user.email=pablor.data@gmail.com) core.editor=vim init.defaultBranch=main core.autocrlf=true`

</details>

<details>
  <summary>03/42 - Control de Versiones con Git: Comandos Básicos y Flujo de Trabajo</summary>
  <br/>

 > 💡 Aprender a utilizar Git desde los primeros pasos puede parecer desafiante, pero es esencial para registrar cambios y manejar versiones de cualquier proyecto. Siguiendo un flujo de trabajo sencillo y utilizando los comandos adecuados, puedes dominar el control de versiones y llevar un seguimiento preciso de tus archivos.

## ¿Cómo inicia el control de versiones con Git?

El primer paso es iniciar un repositorio con el comando `git init`, que crea una carpeta oculta llamada `.git` en el directorio de trabajo. Esta carpeta actúa como una bitácora, almacenando cada cambio y movimiento de los archivos que se manejan en el proyecto.

## ¿Cómo se crean y agregan archivos a Git?

Para crear un archivo desde la terminal, utiliza un editor como `nano`. Una vez creado, puedes verificar su existencia y estado con `git status`, que te mostrará el archivo como no registrado. Para incluirlo en el área de staging, donde estará listo para el commit, usa `git add nombre_del_archivo.txt`. Esta área de staging es un “limbo” donde decides qué archivos entrarán en el control de versiones.

- **Ejemplo de comandos**:
    - `nano testing.txt` para crear el archivo.
    - `git add testing.txt` para agregarlo al área de staging.

## ¿Qué es el área de staging y cómo funciona?

El área de staging permite revisar los cambios antes de que se registren oficialmente en el repositorio. Los archivos en staging aún no forman parte del historial de versiones; están en espera de que se realice un commit o de ser devueltos a su estado original con `git rm --cached nombre_del_archivo.txt`.

![image.png](attachment:5f64a1e4-46d1-4d02-beec-acf6c6c6d659:image.png)

![image.png](attachment:697d5dfa-e156-416a-8aac-c15da679fec1:image.png)

## ¿Cómo realizar el commit de los archivos en Git?

Una vez en staging, se ejecuta `git commit -m "mensaje descriptivo"` para registrar los cambios en el repositorio. El mensaje en el commit es crucial porque indica la acción realizada, como “nuevo archivo de testing”. Este mensaje permite identificar los cambios de forma clara y ordenada en el historial del proyecto.

- **Ejemplo de commit**:
    - `git commit -m "nuevo archivo de testing"`

## ¿Cómo gestionar múltiples archivos en Git?

Para trabajar con varios archivos a la vez, utiliza `git add .` que agrega todos los archivos sin registrar en el área de staging. Puedes decidir entre realizar commits individuales o múltiples en función de la cantidad de archivos y los cambios realizados en cada uno.

## ¿Cómo visualizar el historial de cambios en Git?

El comando `git log` muestra el historial de commits, proporcionando una vista completa de cada cambio realizado en el proyecto. Esta bitácora permite ver el estado de cada archivo y la información de cada commit.

## ¿Qué sucede al modificar un archivo en Git?

Cuando un archivo se edita, Git lo detecta como “modificado”. El flujo de trabajo para registrar este cambio es el mismo que para un archivo nuevo: `git add` para llevarlo a staging y `git commit` para guardar la modificación. Esto asegura que Git mantenga un registro detallado de cada cambio, actualización o eliminación en el proyecto.

## ¿Cómo maneja Git diferentes tipos de archivos?

Git trata cualquier archivo de igual manera, sin importar su extensión o tipo, ya sea de texto, código o imagen. Con `git add` y `git commit`, cualquier cambio en estos archivos se registra, facilitando el control de versiones sin importar el tipo de contenido.

---

**Terminos basicos**

- cd → cambiar directorio y/o regresar al directorio raiz
    - cd .. → retroceder 1 carpeta dentro del directorio
- mkdir → crear directorio
- rmdir → remover directorio
- ls → contenido de un directorio
- .. → volver 1 carpeta atrás
- mkdir repo → crear repo
- rmdir repo → eliminar repo
- git init → iniciar repositorio
- git add → añadir archivos
- git status → estado del repo
- git rm —cached → eliminar archivo añadido al repositorio
- git commit → subir todo al repositorio

</details>

<details>
  <summary>04/42 - Gestión de ramas en Git: creación, fusión y eliminación eficiente</summary>
  <br/>

 > 💡 El uso de ramas en Git permite trabajar en un entorno aislado sin interferir con otros, facilitando la organización y el control del proyecto. Aprender a crear, gestionar y fusionar ramas optimiza la colaboración y ayuda a mantener la limpieza en el historial de cambios.**

## ¿Por qué son útiles las ramas en Git?
Las ramas son una herramienta que permite trabajar en tareas específicas sin alterar la rama principal. Entre sus ventajas se encuentran:

- Aislamiento de cambios individuales.
- Posibilidad de desechar una rama sin afectar la principal.
- Organización de actividades múltiples en diferentes ramas.

## ¿Cómo verificar la rama actual?
Para saber en qué rama estás trabajando, ejecuta:

```bash
git branch
```

El asterisco (*) indica la rama activa. Inicialmente, suele ser `main`, pero al crear más ramas, la lista crecerá, permitiéndote ver todas las disponibles y cuál es la actual.

## ¿Cómo crear una nueva rama en Git?
La creación de ramas permite desarrollar sin riesgo en paralelo. Para crear y moverte a una nueva rama, usa:

```bash
git checkout -b
```

Por ejemplo, `git checkout -b Amin` crea y mueve a la rama `Amin`. Puedes verificar que estás en esta rama ejecutando `git branch`.

## ¿Cómo agregar y confirmar cambios en una rama?
Dentro de una nueva rama, los archivos se editan y confirman sin que impacten otras ramas. Sigue estos pasos para agregar y confirmar:

1. Crea o edita un archivo.
2. Añádelo con:
    
    ```bash
    git add .
    ```
    
3. Confirma el cambio:
    
    ```bash
    git commit -m "mensaje de confirmación"
    ```
    

Los cambios ahora son parte de la rama en la que trabajas y no afectan la principal.

## ¿Cómo fusionar cambios de una rama secundaria a la principal?
Para unificar el trabajo en la rama principal:

1. Cambia a la rama principal:*Nota*: Puedes usar también `git checkout main`.
    
    ```bash
    git switch main
    ```
    
2. Fusiona la rama secundaria:
    
    ```bash
    git merge
    ```
    

Git indicará que el proceso fue exitoso y actualizará el contenido en la rama `main` con los cambios de la rama secundaria.

## ¿Por qué es importante eliminar ramas que ya no se usan?
Una vez fusionada una rama, es buena práctica eliminarla para evitar desorden. Hazlo con:

```bash
git branch -d
```

Eliminar ramas que ya cumplieron su propósito previene conflictos y mantiene el entorno de trabajo limpio y organizado.

---

- `git branch:` Saber en qué rama me encuentro.
- `git checkout -b` “nombre rama”: Crea una nueva rama y se mueve a ella.
- `git branch:` Lista, crea o elimina ramas
- `git checkout:` Cambia entre ramas
- `git switch:` Cambia entre ramas
- `git merge:` Fusiona ramas (unifica todas las ramas en main)
- `git branch -D` “nombre rama”: Eliminar rama. El una buena práctica después del merge.
<br/>
git branch git checkout -b "dev" nano testing_dev.txt git add . git commit -m "nuevo archivo creado" git checkout dev git switch main git merge dev git branch ls git log clear git branch -D dev
<br/><br/>
</details>

<details>
  <summary>05/42 - Git Reset vs Git Revert: Manejo de Historial y Corrección de Errores</summary>
  <br/>

 > 💡 Para quienes se inician en el manejo de versiones con Git, comandos como `git reset` y `git revert` se vuelven herramientas indispensables, ya que permiten deshacer errores y ajustar el historial de cambios sin complicaciones. Aunque al avanzar en la experiencia puedan dejarse de lado, dominar su uso resulta clave para un control de versiones eficiente.

## ¿Cuál es la diferencia entre Git Reset y Git Revert?
- **Git Reset**: establece el puntero de los commits a uno anterior, permitiendo “volver en el tiempo” y explorar el historial de cambios. Es útil para deshacer actualizaciones recientes o revisar lo que se hizo en cada commit.
- **Git Revert**: crea un nuevo commit que revierte los cambios de un commit específico, permitiendo conservar el historial original sin eliminaciones. Es ideal para regresar a un estado anterior sin afectar los commits de otros usuarios.

## ¿Cómo se utiliza Git Reset?
1. Ejecuta `git log` para identificar el historial de commits. El commit actual se marca con `HEAD` apuntando a `main`.
2. Si quieres eliminar cambios recientes:
    - Crea un archivo temporal (ejemplo: `error.txt`) y realiza un commit.
    - Verifica el historial con `git log` y localiza el hash del commit que deseas restablecer.
3. Para revertir a un estado anterior:
    - Usa `git reset` con parámetros:
        - `-soft`: solo elimina el archivo del área de staging.
        - `-mixed`: remueve los archivos de staging, manteniendo el historial de commits.
        - `-hard`: elimina los archivos y el historial hasta el commit seleccionado.
    - Este último parámetro debe ser una **última opción** debido a su impacto irreversible en el historial.

## ¿Cómo funciona Git Revert?
1. **Identificación del commit**: usa `git log` para encontrar el commit a revertir.
2. **Ejecuta `git revert`** seguido del hash del commit: crea un nuevo commit inverso, preservando el historial.
3. **Editar el mensaje de commit**: permite dejar claro el motivo de la reversión, ideal en equipos colaborativos para mantener claridad.

## ¿Cuándo es recomendable utilizar Git Reset o Git Revert?
Ambos comandos resultan útiles en diversas situaciones:

- **Corrección de errores**: si has subido un archivo incorrecto, `git revert` es rápido y seguro para deshacer el cambio sin afectar el historial.
- **Limpieza del historial**: en proyectos sólidos, puede que quieras simplificar el historial de commits; `git reset` ayuda a limpiar entradas innecesarias.
- **Manejo de conflictos**: en casos extremos de conflicto de archivos, `git reset` es útil, aunque puede ser mejor optar por resolver conflictos manualmente.

## ¿Cómo aseguras una correcta comunicación en el uso de estos comandos?
- Utiliza estos comandos en sincronización con el equipo.
- Evita el uso de `git reset --hard` sin coordinación para prevenir la pérdida de trabajo ajeno.
- Documenta cada reversión con un mensaje claro para asegurar el seguimiento de cambios.

---

- **git reset:** Este comando devuelve a un commit anterior, eliminando los cambios en el historial como si nunca hubieran ocurrido.
- Permite deshacer cambios y mover el puntero HEAD a un commit específico. Hay tres modos principales:
- `git reset --soft:` Mueve HEAD al commit especificado, pero mantiene los cambios en el área de preparación.
- `git reset --mixed:` (Por defecto) Mueve HEAD y deshace los cambios en el área de preparación, pero mantiene los cambios en el directorio de trabajo.
- `git reset --hard:` Mueve HEAD y descarta todos los cambios, tanto en el área de preparación como en el directorio de trabajo.
- **git revert:** Crea un nuevo commit que deshace los cambios de un commit específico. Es útil para deshacer cambios de forma segura en repositorios compartidos.

Estos comandos son útiles para corregir errores o volver a estados anteriores del proyecto de manera controlada, limpieza de historial y manejo de conflictos.

`nano error.txt clear ls git add . git commit -m "nuevo archivo especial creado" git log clear`

## git revert

git revert"hash commit"

## Crea un nuevo commit que deshace los cambios del último commit

"Revert "nuevo archivo especial creado" por "autor revert""

git log clear ls

nano reset.txt git add . git commit -m "nuevo archivo para reiniciar" git log clear ls

## git reset

git reset --hard "hash"

---

- `-soft`: Deshace el commit pero mantiene los cambios en staging.
- `-mixed`: Deshace el commit y quita los archivos del staging, pero mantiene los cambios en el código.
- `-hard`: Borra todo, incluyendo los cambios en el código.

</details>

<details>
  <summary>06/42 - Uso de Git Tag y Git Checkout para Gestión de Versiones y Revisión</summary>
  <br/>

 > 💡 Git facilita el control de versiones y organización de proyectos, y los comandos `git tag` y `git checkout` son piezas clave para una gestión eficiente y ordenada de los cambios en el código. Ambos comandos ayudan a crear puntos de referencia y explorar cambios sin afectar el desarrollo principal, ofreciendo opciones robustas para pruebas y organización.**

## ¿Cómo se utiliza `git tag` para organizar versiones?

El comando `git tag` permite marcar un commit con una etiqueta descriptiva, ideal para señalar versiones estables o hitos importantes en el proyecto. Esto resulta útil en proyectos donde el equipo necesita identificar fácilmente puntos clave de avance. Al etiquetar, se añade una nota visible en el historial, lo cual facilita encontrar versiones específicas en un flujo de trabajo con muchos commits.

Para crear un tag:

- Escribe `git tag -a v1.0 -m "primera versión estable"` y presiona Enter.
- Al consultar `git log`, se verá el tag junto al commit en el historial.

Además, `git show`  muestra detalles de la etiqueta, quién la creó, el mensaje de la versión y los cambios asociados a ese commit. Esto es especialmente útil cuando el historial es extenso, ya que permite regresar a puntos específicos sin necesidad de revisar cada commit en el log completo.

Para eliminar un tag:

- Usa `git tag -d v1.0` para remover el tag sin afectar el historial ni los archivos. Esto es conveniente si el nombre del tag necesita ser corregido o ajustado.

## ¿Qué permite `git checkout` al explorar el historial?

El comando `git checkout` tiene usos más amplios que solo cambiar entre ramas. También permite revisar commits previos para explorar o probar cambios sin alterar la rama principal. Al usar `git checkout` , puedes regresar a un punto específico en el historial y evaluar cómo afectaban los cambios al proyecto en ese momento.

Por ejemplo:

1. Cambia a un commit específico con `git checkout` .
2. Realiza pruebas o modificaciones. Esto te permite simular cambios o ver el estado del proyecto en esa versión.
3. Para regresar a la rama principal, escribe `git checkout main`. Esto restaura el proyecto al estado actual y evita que los cambios temporales afecten el historial o la estructura del proyecto.

Al navegar entre commits y regresar a `main`, es importante notar que no se crean ramas adicionales, ni se modifican commits previos, lo cual asegura la integridad del historial y la rama principal.

## ¿Cómo integran `git tag` y `git checkout` una experiencia de desarrollo ordenada?

Ambos comandos permiten explorar y organizar sin interferir en el flujo principal del trabajo. `Git tag` marca versiones y puntos importantes, actuando como separadores en el historial, mientras que `git checkout` permite regresar a esos puntos y probar sin comprometer la rama actual. Esto proporciona una estructura en la que el equipo puede trabajar con libertad para realizar pruebas, versionar cambios y retornar al estado actual en cualquier momento sin temor a alterar el trabajo original.

---

La diferencia entre `tag` y `checkout` en Git radica en su funcionalidad:

- **`git tag`**: Se utiliza para crear una etiqueta en un commit específico, lo que permite identificar versiones o hitos importantes en el historial del proyecto. Por ejemplo, `git tag -a v1.0 -m "Primera versión"`.
- **`git checkout`**: Se utiliza para cambiar entre ramas o explorar commits anteriores sin modificar el historial actual. Por ejemplo, `git checkout <hash_del_commit>` te permite revisar el estado de tu proyecto en ese commit.

Ambos comandos son útiles para gestionar versiones, pero tienen propósitos distintos.

---

La diferencia entre `tag` y `checkout` en Git radica en su funcionalidad:

- **`git tag`**: Se utiliza para crear una etiqueta en un commit específico, lo que permite identificar versiones o hitos importantes en el historial del proyecto. Por ejemplo, `git tag -a v1.0 -m "Primera versión"`.
- **`git checkout`**: Se utiliza para cambiar entre ramas o explorar commits anteriores sin modificar el historial actual. Por ejemplo, `git checkout <hash_del_commit>` te permite revisar el estado de tu proyecto en ese commit.

Ambos comandos son útiles para gestionar versiones, pero tienen propósitos distintos.

</details>

<details>
  <summary>07/42 - Resolución de Conflictos de Ramas en Git paso a paso</summary>
  <br/>

 > 💡 Cuando trabajamos en equipo, el manejo de conflictos de ramas en Git es esencial para evitar problemas y asegurar una integración fluida de cambios en los archivos compartidos. Aquí te mostramos cómo se genera un conflicto de ramas y la forma efectiva de resolverlo paso a paso.

## ¿Qué es un conflicto de ramas en Git?

En un entorno colaborativo, es común que varias personas realicen modificaciones en archivos compartidos. Esto puede llevar a conflictos de ramas cuando intentamos fusionar cambios y estos alteran las modificaciones previas realizadas por otro colaborador. En estos casos, se debe elegir qué cambios se mantendrán en la rama principal.

![image.png](attachment:385cde68-9d68-4ab6-8c95-25122b1cf8ab:image.png)

## ¿Cómo crear un conflicto de ramas para aprender a resolverlo?

Para experimentar y entender cómo resolver un conflicto, podemos crear uno intencionalmente. Aquí están los pasos básicos:

- Verifica tu rama actual con `git branch`. Si solo tienes la rama `main`, estás listo para iniciar.
- Crea un archivo, por ejemplo, `conflict.txt`, añade contenido inicial (e.g., “línea original”) y realiza un commit:
    
    ```bash
    git add conflict.txt
    git commit -m "Archivo de conflicto creado"
    ```
    
- Crea una nueva rama con `git checkout -b developer` y modifica el archivo con nuevos cambios, como “cambios desde la rama dev”, realiza un commit.
- Vuelve a la rama `main` con `git checkout main` y modifica el mismo archivo en esta rama, por ejemplo, añadiendo “segundo cambio desde main”, y realiza otro commit.

Al regresar a `main` y realizar la fusión de `developer`, verás el conflicto.

## ¿Cómo resolver un conflicto de ramas en Git?

Cuando Git detecta un conflicto, te indicará las diferencias entre las ramas con etiquetas que facilitan la identificación de cambios:

- Abre el archivo en conflicto. Verás secciones como `<<<<< HEAD` y `>>>>>`, que marcan los cambios en `main` y en la rama que intentas fusionar (`developer`).
- Edita el archivo eliminando las líneas de marcación y decide cuáles cambios deseas conservar, combinar o incluso reescribir.
- Guarda el archivo sin las señalizaciones de conflicto y realiza un commit para registrar la resolución:
    
    ```bash
    git add conflict.txt
    git commit -m "Conflicto resuelto"
    
    ```
    

## ¿Qué hacer después de resolver un conflicto?

Una vez resuelto el conflicto y unificada la versión final en `main`, considera eliminar la rama `developer` para evitar conflictos futuros. Esto ayuda a mantener el historial de cambios limpio y reduce la posibilidad de cometer errores en el futuro.

</details>

<details>
  <summary>08/42 - Uso de Git en Visual Studio Code</summary>
  <br/>

 > 💡 Visual Studio Code ofrece una interfaz visual y eficiente para gestionar versiones con Git, simplificando muchas tareas complejas y ahorrando tiempo a los desarrolladores. Integrar VS Code en nuestro flujo de trabajo diario puede facilitar considerablemente el manejo de ramas, commits y conflictos sin depender tanto de comandos en la terminal.

## ¿Cómo abrir VS Code desde la terminal?

- Inicia VS Code en la ubicación del proyecto con `code .`.
- Esto abre una instancia de VS Code en el directorio actual, incluyendo todos los archivos versionados con Git.

## ¿Cómo visualizar y gestionar ramas en VS Code?

- Dentro de VS Code, identifica tu rama activa en la sección de control de versiones.
- Selecciona la rama para ver las opciones de cambio, como alternar entre ramas o crear nuevas.
- Los cambios en las ramas se presentan en una gráfica visual, diferenciando fusiones y ramas en colores, una ventaja significativa sobre `git log`.

## ¿Cómo hacer un commit de cambios en VS Code?

- Al editar un archivo, el ícono de control de versiones muestra un indicador de cambio.
- En lugar de usar `git commit -m "mensaje"`, puedes simplemente añadir un mensaje y presionar commit en la interfaz de VS Code.

## ¿Cómo crear y alternar entre ramas en VS Code?

1. Haz clic en “Create New Branch” y nómbrala, por ejemplo, “VS Code Dev”.
2. VS Code marca esta nueva rama como activa, heredando los cambios de la rama principal.
3. Al editar archivos en esta rama, puedes realizar commits directamente en la interfaz.

## ¿Cómo resolver conflictos de fusión en VS Code?

- Selecciona la rama con la que deseas fusionar (por ejemplo, VS Code Dev con Main) usando el menú de Branch > Merge.
- Cuando ocurre un conflicto, VS Code despliega opciones de resolución con colores para cada cambio, simplificando la selección entre el cambio actual, el entrante o ambos.
- Puedes optar por “Merge Editor” para una vista más visual y confirmar la fusión con un “Complete Merge” al finalizar.

## ¿Cómo iniciar un nuevo repositorio en VS Code?

1. Crea un nuevo directorio y abre VS Code en esa ubicación.
2. Al no haber archivos, selecciona “Inicializar repositorio” para configurar un nuevo repositorio.
3. Esto ejecuta `git init`, crea la rama principal (main) y permite añadir nuevas ramas y hacer commits sin usar comandos.

---

## Usando Git desde Visual Studio Code

Visual Studio Code (VS Code) tiene integración nativa con Git, lo que facilita el control de versiones sin necesidad de usar la terminal. Aquí te muestro cómo trabajar con Git en VS Code paso a paso. 🚀

### 1. Configurar Git en VS Code

### Verificar si Git está instalado

Abre VS Code y presiona `Ctrl + ñ` para abrir la terminal integrada. Luego, escribe:

git --version

🔹 Si Git no está instalado, descárgalo desde [git-scm.com](https://git-scm.com/).

### Configurar tu usuario y correo

Si es la primera vez que usas Git, configura tu nombre y correo:

git config --global user.name "Tu Nombre" git config --global user.email "[tuemail@example.com](mailto:tuemail@example.com)"

### 2. Inicializar un Repositorio en VS Code

Si estás en un proyecto nuevo y quieres iniciar Git: 1️⃣ Abre VS Code y carga tu proyecto. 2️⃣ Abre la terminal (`Ctrl + ñ`) y ejecuta:

git init

3️⃣ Verás una nueva sección en el panel de control con el icono de **Git**.

### 3. Clonar un Repositorio desde GitHub

Si el proyecto ya está en GitHub: 1️⃣ Copia la URL del repositorio desde GitHub. 2️⃣ En VS Code, abre la terminal y escribe:

git clone <URL_DEL_REPOSITORIO>

3️⃣ Abre la carpeta del proyecto en VS Code (`File > Open Folder`).

### 4. Realizar Commits desde VS Code

### Agregar archivos al control de versiones

1️⃣ En el menú de Git (`Ctrl + Shift + G`), verás una lista de archivos modificados. 2️⃣ Haz clic en `+` junto a cada archivo para agregarlo a staging (equivalente a `git add`). 3️⃣ Escribe un mensaje de commit en la caja de texto y presiona `Ctrl + Enter` o haz clic en ✅ (equivalente a `git commit -m "mensaje"`).

### 5. Subir Cambios a GitHub

### Conectar el repositorio a GitHub

Si el repositorio no está vinculado a GitHub, usa:

git remote add origin <URL_DEL_REPOSITORIO> git branch -M main # Asegura que la rama principal sea "main" git push -u origin main

### Enviar cambios a GitHub

Cada vez que hagas cambios: 1️⃣ Realiza `commit` como en el paso anterior. 2️⃣ Haz clic en el botón `Sync Changes` en la barra de Git. 3️⃣ O usa la terminal:

git push origin main

### 6. Descargar Cambios desde GitHub

Para actualizar tu código con la última versión del repositorio remoto: 1️⃣ Ve a la sección de Git en VS Code. 2️⃣ Haz clic en el botón `Pull` para traer cambios del repositorio. 3️⃣ O usa la terminal:

git pull origin main

### 7. Crear y Cambiar de Ramas en VS Code

### Crear una nueva rama

1️⃣ Abre la barra de comandos (`Ctrl + Shift + P`). 2️⃣ Escribe **"Git: Create Branch"** y selecciona la opción. 3️⃣ Ingresa el nombre de la nueva rama y presiona Enter.

📌 También puedes usar la terminal:

git branch nueva-rama git switch nueva-rama # Para cambiar de rama

### Cambiar entre ramas

1️⃣ Haz clic en el nombre de la rama en la esquina inferior izquierda. 2️⃣ Selecciona la rama a la que quieres cambiar.

### 8. Resolver Conflictos de Fusión en VS Code

Si hay un conflicto, VS Code te mostrará opciones en el archivo afectado: ✅ **Accept Current Change** → Mantener la versión de tu rama actual. ✅ **Accept Incoming Change** → Mantener la versión de la otra rama. ✅ **Accept Both Changes** → Combinar ambas versiones manualmente.

📌 Luego, guarda el archivo y haz `commit` para finalizar.

---

### Conclusión

VS Code hace que trabajar con Git sea mucho más intuitivo. Puedes hacer **commits, push, pull, trabajar con ramas y resolver conflictos** sin salir del editor.

</details>
<br/>

### 👉🏻 Introducción a github
<details>
  <summary>10/42 - Uso de GitHub para Colaboración y Desarrollo Seguro</summary>
  <br/>
</details>

<details>
  <summary>11/42 - Creación y configuración de cuenta GitHub paso a paso</summary>
  <br/>
</details>

<details>
  <summary>12/42 - Proceso de Trabajo con Git y GitHub: Creación y Revisión de Repositorios</summary>
  <br/>
</details>

<details>
  <summary>13/42 - Creación y colaboración en repositorios de GitHub</summary>
  <br/>
</details>

<details>
  <summary>14/42 - Precios y Planes de Productos de Github</summary>
  <br/>
</details>

<details>
  <summary>15/42 - Configuración de SSH en GitHub para Windows, Linux y Mac</summary>
  <br/>
</details>

<details>
  <summary>16/42 - Uso de Forks y Estrellas en Repositorios de GitHub</summary>
  <br/>
</details>

<details>
  <summary>17/42 - Uso de git pull, git push y git fetch en repositorios GitHub</summary>
  <br/>
</details>

<details>
  <summary>18/42 - Creación de Plantillas de Issues en GitHub</summary>
  <br/>
</details>

<details>
  <summary>19/42 - Uso de Pull Requests en GitHub para Colaboración Efectiva</summary>
  <br/>
</details>
<br/>

### 🛠️ Herramientas de colaboración en Github
<details>
  <summary>20/42 - Gestión de Proyectos con GitHub Projects: Planificación Colaborativa</summary>
  <br/>
</details>

<details>
  <summary>21/42 - Automatización de flujos de trabajo en GitHub Projects</summary>
  <br/>
</details>

<details>
  <summary>22/42 - Recursos Esenciales de Markdown para Documentación Efectiva</summary>
  <br/>
</details>

<details>
  <summary>23/42 - Creación de una Portada de Perfil en GitHub con Markdown</summary>
  <br/>
</details>

<details>
  <summary>24/42 - Creación y Gestión de Wikis en GitHub</summary>
  <br/>
</details>

<details>
  <summary>25/42 - Uso de GitHub Gist para Compartir y Revisar Código Colaborativo</summary>
  <br/>
</details>

<details>
  <summary>26/42 - Creación y Publicación de Sitios Web con GitHub Pages</summary>
  <br/>
</details>
<br/>

### 🛰️ Github Codespaces
<details>
  <summary>26/42 - Creación y Gestión de GitHub Codespaces en la Nube</summary>
  <br/>
</details>

<details>
  <summary>27/42 - Uso de Codespaces y plantillas en GitHub para proyectos con Django</summary>
  <br/>
</details>

<details>
  <summary>28/42 - Programación Colaborativa con Live Share en VS Code</summary>
  <br/>
</details>

<details>
  <summary>29/42 - Uso del Editor Web de GitHub para Edición Rápida de Archivos</summary>
  <br/>
</details>
<br/>

### 🔒 Seguridad y Buenas Prácticas en Github
<details>
  <summary>30/42 - Cómo usar Tokens en GitHub para Acceso Seguro a Repositorios Privados</summary>
  <br/>
</details>

<details>
  <summary>31/42 - Mitigación de Brechas de Seguridad en Repositorios GitHub</summary>
  <br/>
</details>

<details>
  <summary>32/42 - Gestión de Seguridad de Paquetes con Dependabot en Proyectos .NET</summary>
  <br/>
</details>

<details>
  <summary>33/42 - Configuración de Repositorios Privados en GitHub</summary>
  <br/>
</details>
<br/>

### 📎 Administración de Github
<details>
  <summary>34/42 - Creación y gestión de repositorios en GitHub</summary>
  <br/>
</details>

<details>
  <summary>35/42 - Automatización de GitHub Actions para Actualizar Perfil</summary>
  <br/>
</details>

<details>
  <summary>36/42 - Uso de GitHub CLI: instalación y comandos básicos</summary>
  <br/>
</details>
<br/>

### 🚼 Gestión de cambios con Pull Requests
<details>
  <summary>37/42 - Configuración de Proyectos de Software con Git y GitHub</summary>
  <br/>
</details>

<details>
  <summary>38/42 - Creación y Gestión de Branches y Pull Requests en GitHub</summary>
  <br/>
</details>

<details>
  <summary>39/42 - Estrategias de Fusión de Ramas en Git</summary>
  <br/>
</details>
<br/>

### 🚀 Github Releases
<details>
  <summary>40/42 - Creación de Releases en Github para Desarrolladores de</summary>
  <br/>
</details>

<details>
  <summary>41/42 - Creación y Uso de Paquetes PIP en Python desde GitHub</summary>
  <br/>
</details>

<details>
  <summary>42/42 - Tips Avanzados para Mejorar tu Flujo de Trabajo en GitHub</summary>
  <br/>
</details>
<br/>