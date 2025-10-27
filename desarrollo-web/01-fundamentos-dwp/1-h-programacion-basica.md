
# <img width="32px" src="https://static.platzi.com/media/achievements/badge-piezas-programacion-basica-ede320eb-b1a9-4f1c-8b61-dd0502bbe4d3.png"/> 🎓 Curso Gratis de Programación Básica

<img src="./banners-cursos/curso01.jpg"/>

  <br/>

  👉🏻 [Ve al Curso de HTML](https://platzi.com/cursos/programacion-basica)
  
  <br/>

  | Nombre de profesores | Perfiles profesionales | Fecha publicación del Curso |
  | :--- | :--- | :--- |
  | **Freddy Vega** | Experto en educación presencial y online |
  | **Estefany Aguilar** | **Desarrolladora Frontend en Platzi** <br/> 👩‍💻 Experta en CSS <br/> 🇨🇴 Organizadora de comunidades como MedellínCSS y CSS Conf Colombia <br/> 🎨 Ama enseñar con ilustraciones divertidas | 📅 Publicado el **19 de junio de 2024** |
  | **Diego De Granda** | **Head of Education en Platzi** <br/> 👨‍🏫 Google Developer Expert <br/> 🖥️ Chief Technology Officer at Besage.ai <br/> 👨‍💻 Experto en JavaScript y Web Components | 📅 Publicado el **19 de junio de 2024** |
  | **Juan David Castro Gallego** | **Software Developer en Platzi** <br/> 👨‍💻 Experto en desarrollo web <br/> 📚 Apasionado por la educación online <br/> 👨‍🎓 Estudiante en Platzi por más de 9 años | 📅 Publicado el **19 de junio de 2024** |
  | **Diana Martínez** | 👩‍💻 Desarrolladora de software <br/> 🔧 Ingeniera en mecatrónica. <br/> 🤖 Fundadora de Robots LatAm | 📅 Publicado el **19 de junio de 2024** |
  | **Estefany Salas** | **Software Developer en Platzi** <br/> ✨ Product Manager <br/> 💻 Amante de React.js <br/> 💚 Platzi Team | 📅 Publicado el **19 de junio de 2024** |
  <br/>


> Domina los fundamentos de programación con JavaScript, HTML y CSS creando un videojuego desde cero. Aprende lógica, estructuras, manipulación del DOM y bases de desarrollo web y backend.

---

## Clases del curso

### 🗿 Fundamentos de Programación
<details>
  <summary>01/84 - ¡Bienvenida a Platzi: ¿Qué necesitas para tomar el curso?</summary>
  <br/>
</details>

<details>
  <summary>02/84 - Programación en Navegadores: Primeros Paso</summary>
  <br/>

  Si nos regalas solo unos minutos, podemos enseñarte a escribir tus primeras líneas de código 💚 Solo necesitas un navegador de Internet y la voluntad para intentarlo 😉 .

  ## **Abriendo la consola del navegador**

  Primero necesitamos un espacio dónde escribir código. Así que ve a tu navegador favorito (Google chrome, Edge, Firefox, Opera, o el que prefieras) y dirígete a la barra de direcciones (ese lugar donde escribes “`Platzi.com`”).

  Ahí, vas a escribir “**about:blank**” (sin las comillas). Eso hará que la pestaña donde lo escribiste quede vacía. Debería quedar un espacio totalmente blanco. Una vez ahí, vas a hacer **clic derecho** en el espacio en blanco y luego vas a hacer clic en un botón que diga “**inspeccionar**” (algunos navegadores lo llaman “inspect element”).

  Eso abrirá el **inspector de elementos**, un menú donde puedes ver la composición del sitio web dónde estás parado (muchos se espantan cuando lo abren por accidente dentro de un sitio web 😆 Más tarde puedes hacerlo por prueba si quieres 👍).

  El inspector se abre por defecto en una pestaña llamada “elementos” en la parte superior. Lo que estamos buscando está justo al lado: una pestaña llamada “**consola”.**

  Ahí es dónde empezarás a programar 😉

  ![Captura de pantalla que muestra cómo llegar a la consola](https://static.platzi.com/media/articlases/Images/Clase%2001%20-%201.png)

  ## **Tus primeras líneas de código**

  Haz clic en la consola y escribe lo mismo que te indico aquí abajo. **Recuerda pulsar [enter] luego de escribir cada línea para ver el resultado** 🙂

  ```jsx
  1 + 1   //[enter]

  9 - 5   //[enter]

  12 * 4  //[enter]

  30 / 5  //[enter]

  ```

  ![Captura de pantalla de cómo se ven estos cálculos en la consola](https://static.platzi.com/media/articlases/Images/Clase%2001%20-%202.png)

  Seguro ya notaste que puedes usar la consola como una especie de calculadora. Realiza algunos experimentos antes de continuar 😉

  ## **Variables**

  Ahora, ¿qué tal si probamos algo diferente? Ingresa el siguiente código en la consola:

  ```jsx
  a = 1       //[enter]

  b = 2       //[enter]

  c = a - b
  ```

  ¿Qué crees que ocurrirá cuando pulses [enter] en ese último comando? ¡Así es! La consola sustituirá “a” y “b” por sus valores numéricos, y los usará para calcular el valor de “c” 😃

  Esto ocurre porque, cuando la consola recibe el comando “a = 1”, tu computadora guarda en su memoria RAM que la letra “a” vale “1”.

  A esto lo llamamos crear una **variable,** y ocurre siempre que empleas el signo igual (=). En este escenario, a, b y c se convirtieron en variables y puedes emplearlas para calcular cosas más interesantes 🙂 De hecho, no tienes que limitarte a letras. Puedes crear variables tan locas como:

  ```jsx
  perros = 4

  gatos = 3

  totalMascotas = perros + gatos
  ```

  Ojo, en la consola, una vez que declaras una variable, basta con escribirla de nuevo para conocer de nuevo su valor. Prueba escribiendo solamente “c” y pulsando [enter] 😉

  Adelante, experimenta un poco antes de seguir leyendo 😁

  ## **Errores**

  Ahora, ¿crees que la consola solo sabe interpretar números? Probemos esta vez con algo de texto 🙂

  ```jsx
  d = texto
  ```

  Si pulsaste `[enter]` al escribir eso, probablemente la consola te arrojó un error 😅 Verás: la consola te permite darle instrucciones a tu computadora de forma directa. Pero si escribes algo que tu computadora no puede entender, entonces te va a arrojar un error.

  Este error que cometiste es un **error de sintaxis**, y ocurre cuando escribes algo que no sigue las reglas del lenguaje de programación que entiende tu computadora.

  En este caso, nos estamos comunicando con ella usando **JavaScript**. Y en JavaScript, el texto se escribe entre comillas (”).

  ## **Strings**

  Tu computadora no puede entender texto sin ayuda de programas o extensiones. Pero si puede entender caracteres, como letras y símbolos, y **secuencias de caracteres**, como palabras o contraseñas.

  A este tipo de datos se les conoce como **string**. Tu computadora los entiende del mismo modo que entiende a los números, y puedes hacer cosas con ellos como:

  ```jsx
  d = "Hola, "

  e = " ¿cómo estás?"

  profesor = "Freddy"

  f = d + profesor + e

  ```

  Realiza algunos experimentos antes de continuar.

  ## **Funciones**

  Las funciones son una herramienta adicional a nuestra disposición. Estas nos permiten decirle a nuestra computadora: “cuando recibas esta señal, por favor haz esto.”

  Por el momento no te explicaremos como crearlas. Pero si te enseñaremos a usarlas 😉

  El navegador tiene algunas funciones por defecto. Una de ellas se llama “alert()”. Para usarla prueba escribiendo este comando en la consola:

  ```jsx
  alert("¡Estoy programando!")
  ```

  En ese ejemplo, lo que hiciste fue ejecutar la función. Eso se hace escribiendo el nombre de la función (”alert”) seguido por paréntesis con una señal dentro. Esta señal se llama **parámetro.**

  Ojo, esos parámetros generalmente modifican el resultado cuando ejecutas una función. Tú decides cómo funciona cuando las creas, pero algunas funciones usan muchos parámetros, y pueden trabajar sin ningún parámetro.

  Por ejemplo, prueba con:

  ```jsx
  alert()

  ```

  Fíjate en que, **a pesar de no tener parámetros, igual tuvimos que usar los paréntesis**. Esto es importante. Si no usas los paréntesis, la computadora no entiende que quieres ejecutar una función. En cambio, se confunde y piensa que le estás hablando de una variable 😅

  ## **¿Cómo funciona la programación?**

  La consola del navegador es un espacio que nos permite comunicarnos directamente con nuestro computador a través de JavaScript. Cuando creas variables, tu computador guarda la información en la memoria RAM *(Random Access Memory)* dónde la guarda para que accedas a ella siempre que lo necesitas, y la borra al apagar la computadora.

  Todo esto de variables, funciones, strings y demás es lo que está detrás de los sitios web, apps para teléfonos, videojuegos, y todo tipo de software 🙂

  Felicidades por escribir tus primeras líneas de código 🤗 Realiza todos los experimentos que quieras, y nos vemos en la próxima clase para que aprendas a [crear tu primer sitio web](https://platzi.com/clases/3208-programacion-basica/51979-crea-tu-primer-sitio-web/) 😉

  ## **Resumiendo la clase**

  Pero antes de irnos, te dejaré este pequeño resumen para que puedas revisarlo en el futuro:

  💡 Puedes entrar a la **consola** siguiendo los siguientes pasos:

  1. Abre el navegador (Google Chrome, Edge, Firefox, Opera, o el que prefieras).
  2. Escribe “**about:blank**” en la barra de direcciones.
  3. Haz clic derecho en el espacio en blanco, y selecciona “**inspeccionar**” (algunos navegadores lo muestran como “inspect element”). Eso abre el **inspector de elementos**.
  4. dentro del inspector de elementos, dirígete a una pestaña llamada “**consola**”.

  💡 La consola del navegador te permite comunicarte directamente con tu computador a través de un lenguaje de programación llamado **JavaScript.**

  En su forma más básica, puedes utilizarlo para realizar operaciones matemáticas.

  💡 Las **variables** permite almacenar valores para usarlos luego en operaciones variadas y más complejas, sin necesidad de repetirlos una y otra vez.

  Más adelante aprenderás sus reglas de uso. Pero, por los momentos, puedes crearlas en la consola usando este formato:

  ```jsx
  [variable] = [valor]
  ```

  Por ejemplo:

  ```jsx
  a = 1
  ```

  💡 Las variables también pueden almacenar texto. Este tipo de datos se llaman **strings**, y puedes emplearlos siempre y cuando encierres el texto entre comillas.

  Por ejemplo:

  ```jsx
  profesor = “Freddy”
  ```

  💡 Las **funciones** nos permiten indicarle a la computadora que ejecute una serie de pasos cuando se le dé la señal. En esta clase no aprendimos a crearlas, pero si a utilizarlas usando la función “alert()” que viene por defecto con el navegador.

  Para usarla, solo tienes que escribir:

  ```jsx
  alert(”mensaje”)
  ```

  Esto funciona aunque el “mensaje esté en blanco. Pero es importante que escribas los paréntesis, o la función no se ejecutará.

  <aside>

  💡 _Los lenguajes de programación tienen reglas de escrituras. Si te equivocas, la computadora no entenderá lo que dices y te avisará mostrándote un error_.

  </aside>

  Los errores que derivan de errores de escritura en el código se llaman **errores de sintaxis** y son bastante comunes, en especial cuando estás aprendiendo a programar.
</details>


<details>
  <summary>03/84 - Crear tu primer sitio web</summary>
  <br/>
  Un **sitio web** funciona correctamente gracias a la participación de diversos tipos de archivos. Por lo tanto, antes de empezar a crear nuestro primer sitio web debemos repasar un concepto fundamental relacionado con **la estructura de los archivos**.

  Aunque en esta clase generaremos un solo archivo para lanzar nuestro primer sitio web, a lo largo del curso necesitarás crear otros tipos de archivos para su correcto funcionamiento.

  ## **Estructura de un archivo**

  Se trata de uno de los conceptos más fáciles de asimilar en el universo de los sistemas operativos. Nada más debes recordar alguno de tantos archivos que has creado desde que usas un computador.

  Es muy probable que hayas pensado que *carta.docx* o *dibujo.jpg* eran, simplemente, nombres de archivos. Resulta que en esa descripción observamos **la estructura de un archivo**.

  ### Nombre

  Debes tener claro que *nombre* es, apenas, una parte de la estructura de un archivo.

  Los nombres son personalizados y descriptivos. Solo **en algunos casos deberás asignar nombres predefinidos** para que sean leídos automáticamente, como, por ejemplo, cuando produces un sitio web. La página principal, por defecto, debe llamarse *index.html*.

  > Al asignar nombres a los archivos, debemos tener en cuenta una recomendación imprescindible como hispanohablantes: no utilizar caracteres especiales como tildes, comas o la eñe. Tampoco se deben emplear símbolos como &, $, %, !, o ". Por ejemplo, si debes crear una presentación en slides para una fecha especial, es mejor que definas el nombre de la siguiente manera: diaDelNino.pptx
  > 

  Tal como puedes darte cuenta en el ejemplo anterior, no uso ni tilde ni la eñe. Además, también debiste haber notado que no he dejado ningún espacio en el medio. En cambio, he utilizado letras mayúsculas.

  ### Punto (.)

  Por más diminuto que nos parezca, **el punto es un elemento importante dentro de la estructura de un archivo**.

  Este carácter **está presente en las estructuras de archivos de todos los sistemas operativos**. Tanto en Windows como en Mac, Linux, incluso, en Android se usa el punto después del nombre y antes de la extensión.

  ### Extensión

  La extensión de un archivo es el componente que nos permite distinguirlo antes de ejecutarlo. Por ejemplo, si la extensión es *pdf* o *mp4*, sabemos que el primero es un documento y que el segundo es un video. Gracias a la **extensión** conocemos anticipadamente qué aplicación ejecutará el archivo.

  Para el propósito del presente curso, tendremos en cuenta que un navegador como Chrome lee, entre otros archivos, aquellos cuya extensión es *html*. Por esta razón, el primer archivo que crearemos para lanzar un sitio web será uno que termine en *.html*. Pero, antes de todo, es necesario conocer acerca de esta tecnología.

  ## **¿Qué es HTML?**

  HTML es un lenguaje de marcado o de **etiquetas**. Gracias a las etiquetas escritas dentro del archivo .html, puedes ver esta página tal y como está. Las etiquetas html son, algo así, como instrucciones que el navegador debe decodificar. Viene del inglés *HyperText Markup Language*.

  Las traducciones al español tienen leves variaciones. Algunos le llaman “*lenguaje de etiquetas*” o “*marcas de hipertexto*”. Otros, simplemente, “*lenguaje de marcado*”. Un archivo con extensión *HTML* contiene texto plano. **HTML no es un archivo de texto enriquecido** como los que producimos en editores como Microsoft Word. Al crear un archivo HTML no podemos formatear su texto con subrayado o con **negrita** o con diferentes colores.

  En este punto ya te habrás preguntado, ¿por qué veo este texto en negrita y en cursiva en el navegador que solo lee archivos HTML, los cuales son archivos de texto plano?. No te preocupes que no se trata de un engaño, es una buena pregunta.

  La versión actual de HTML incorpora más de un centenar de etiquetas. En este curso utilizaremos algunas de las que más se implementan en un sitio web.

  ## **Configurando mi sistema operativo en modo profesional**

  Ahora que ya sabemos lo importante que son las **extensiones**, estas deben estar siempre visibles en nuestro sistema operativo. Además, en el entorno de la programación, **es una buena práctica tener a la vista las extensiones de los archivos que están en nuestro computador**.

  Por eso vamos a proceder a realizar la primera actividad de esta clase: **activar la función de *Mostrar las extensiones de los archivos*** en tu sistema operativo. Esta es una tarea muy sencilla, aunque varía de acuerdo a la versión de tu sistema operativo. Pero si trabajas en una versión reciente, el proceso es, aún, más sencillo.

  ## **Actividad de la clase**

  Después de que hayas realizado la tarea del paso anterior, realiza lo siguiente:

  1. Crea la carpeta *programar* en el escritorio o en la unidad de tu preferencia y ábrela.
  2. Haz clic secundario, selecciona *Nuevo*, luego *Documento de texto*. Borra todo el texto que te aparece por defecto, es decir el nombre del archivo, el punto y la extensión. Escribe pagina.html (recuerda que no se deben usar tildes).
  3. Haz clic secundario sobre el archivo pagina.html, luego en *Abrir con* y selecciona *Bloc de notas*. No debes abrir el archivo haciendo doble clic. Eso lo haremos después. Al hacer doble clic principal, seguramente el archivo lo abra el navegador predeterminado en tu sistema operativo que puede ser Chrome, Edge o Mozilla. En cualquiera de estos solo verás una página en blanco, puesto que todavía no has ingresado contenido al archivo pagina.html.
  4. Después de abrir el archivo en el *Bloc de notas*, escribe las siguientes líneas de código:

  ```html
  <h1>Mi primer sitio web</h1>
  Hola <strong>querida</strong> clase
  ```

  En este ejemplo observa atentamente aquello que está entre los signos de menor que (<) y mayor que (>). Tanto los signos como lo que está dentro de ellos, conforman una etiqueta.

  1. Ahora guarda los cambios, vuelve a la carpeta *programar* y abre el archivo pagina.html haciendo doble clic.

  Así como estás viendo tu archivo, ya no en el *Bloc de notas*, sino en el navegador, es como puedes comprender poco a poco la manera en que funcionan las etiquetas html.

  En el navegador no observas los signos de menor que y mayor que ni lo que está dentro de estos. Lo que sí ves es texto que tiene un mayor tamaño que otro. Esto se debe a que la etiqueta *h1* viene de Header o título o encabezado. El *1* se relaciona con la jerarquía del título. Si deseas ver subtítulos en tu sitio web, debes insertar la etiqueta *h2*. Ten en cuenta que html tiene hasta la etiqueta *h6*.

  Continúa viendo la siguiente clase de este curso para que conozcas muchas más etiquetas html incluyendo las que debes insertar obligatoriamente en tu sitio web.
</details>


<details>
  <summary>04/84 - Sitios web con HTML</summary>
  <br/>

  Seguro ya sabes que un sitio web es, en su forma más básica, un archivo HTML. Ahora, acompáñame a descubrir el funcionamiento de este lenguaje, y cómo puedes usarlo para empezar a crear sitios web 🙂.

  ## **Fundamentos de HTML**

  El **lenguaje de marcas de hipertexto (HTML)** tiene reglas como cualquier otro lenguaje. Y no son tan complicadas cuando te tomas el tiempo para explorarlas poco a poco 😉

  ### 1️⃣ En HTML la información se organiza con etiquetas

  Estas consisten en una palabra o una letra encerradas entre los símbolos “<” y “>”.

  Ej:

  ```html
  <title>
  ```

  ### 2️⃣ Cada pieza contenida en tu sitio web la encierran etiquetas de apertura y de cierre

  Las etiquetas de cierre tienen un “/” antes de la palabra o letra que compone la etiqueta.

  Ej:

  ```html
  <title>Este es el texto que aparece en la pestaña del navegador</title>

  ```

  ### 3️⃣ Las etiquetas se escriben sin espacios internos ni mayúsculas

  Un error de este estilo (de sintaxis) puede causar que el navegador no entienda la etiqueta.

  ### 4️⃣ Existen algunas etiquetas que se cierran a sí mismas

  Estas generalmente **no tienen contenido**, así que empiezan y terminan con la etiqueta de apertura. Sin embargo, son muy útiles para introducir metadatos, organizar elementos de la página, o importar elementos de otras fuentes.

  [Solo hay 14 de estas etiquetas](https://www.tutorialstonight.com/self-closing-tags-in-html#:~:text=%3Carea%3E%20%2D%20HTML,for%20the%20browsers). Pero las más comunes son:

  | **Etiqueta** | **Uso** |
  | --- | --- |
  | `<br>` | Introduce un salto de línea en la página. |
  | `<img>` | Introduce imágenes a tu sitio web. |
  | `<input>` | Introduce elementos para que el usuario te de información (cómo botones, campos de texto, listas desplegables, entre otros). |
  | `<link>` | Se usa mucho para cargar hojas externas de estilos (archivos “.css”) para definir los estilos de tu sitio web. |
  | `<meta>` | Se usa para darle metadata a tu sitio web (para que el navegador y buscadores cómo google puedan trabajar mejor con él). |

  <aside>
  💡Ojo, hay una variante de HTML llamada XHTML que requiere que estas etiquetas terminen en “/>”. Por ese motivo, muchos developers acostumbran a terminar estas etiquetas de esa manera, incluso en el HTML común y corriente.

  </aside>

  Esto no es obligatorio en el HTML que tú estás aprendiendo ahora, pero es bueno que lo tengas en mente para cuando trabajes con otros developers 👍

  Ej:

  ```html
  <meta charset=""utf-8"" />

  <img src=""./assets/img/Logo.svg"" alt=""Logo de Batata Bit"" />
  ```

  ### 5️⃣ Hay etiquetas cuyo trabajo es contener otras etiquetas

  Cuando esto ocurre, se acostumbra usar la “indentación” de código para distinguir la jerarquía de las etiquetas.

  En palabras más simples: Solo tienes que pulsar la tecla “tab” en las etiquetas hijo para que estas se muevan un poquito hacia la derecha. Eso te ayudará a distinguir a los padres de los hijos con mayor facilidad.

  Ej:

  ```html
  <picture class=""logo"">
      <img src=""./assets/img/Logo.svg"" alt=""Logo de Batata Bit"" />
  </picture>

  ```

  ### 6️⃣ Muchas etiquetas HTML utilizan **atributos**

  Estos son información adicional que se agrega en la etiqueta de apertura para personalizar sus propiedades y funcionalidad.

  Estos siguen el siguiente patrón:

  NombreDelAtributo=”ValorDelAtributo”

  Aprenderás más sobre los atributos poco a poco. Por ahora lo importante es que sepas que existen 👍

  Por cierto, en HTML, la combinación de etiquetas, atributos y contenido recibe el nombre de **elemento**.

  ![Partes de un elemento HTML](https://static.platzi.com/media/articlases/Images/Clase%204%20-%201.png)

  ### 7️⃣ Puedes encontrar una lista completa de las etiquetas HTML que puedes usar

  Con explicaciones y ejemplos de uso, en [este sitio web](https://htmlreference.io/).

  También puedes encontrarlas en referencias oficiales como las de [W3Schools](https://www.w3schools.com/tags/) o [Mozilla Developers](https://developer.mozilla.org/en-US/docs/Web/HTML/Element).

  Las más comunes para escribir son:

  | **Etiqueta** | **Uso** |
  | --- | --- |
  | `<p>` | “Paragraph”, te permite introducir párrafos. |
  | `<a>` | “Anchor”, te permite introducir hipervínculos. |
  | `<b>` | “Bold”, te permite escribir en negritas. |
  | `<i>` | “Italics”, te permite escribir en cursiva. |
  | `<u>` | “Underline”, te permite escribir texto subrayado. |
  | `<ul>` | “Unordered list”, te permite crear una lista desordenada (con puntitos) |
  | `<ol>` | “Ordered list”, te permite introducir una lista ordenada (con números o letras). |
  | `<li>` | “List item”, se colocan dentro de un `<ul>` o un `<ol>`, y se convierten en los elementos de la lista. |
  | `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>` | “Heading”, insertan títulos y subtítulos en tu sitio web. El número que acompaña a la “h” representa el nivel del título, dónde h1 tiene la mayor jerarquía. |

  ### 8️⃣ Recuerda, **los archivos HTML cargan de arriba hacia abajo, un elemento tras otro**

  Esto significa que el orden en el que escribas el HTML sí importa. Esos son todos por ahora 😁 Recuerda experimentar un poco con las etiquetas que conociste el día de hoy 😉

  Para profundizar un poco más, no te pierdas de la siguiente clase: [Estructura de árbol en HTML](https://platzi.com/clases/3208-programacion-basica/51981-estructura-arbol-html/).

  </details>

  <details>
    <summary>05/84 - Estructura de árbol en HTML</summary>
    <br/>

    El lenguaje de marcas de hipertexto (HTML) se caracteriza porque su estructura es como la de un árbol 🙂 ¿Te animas a aprender cómo funciona? 😉

  Imagina que cada etiqueta es una rama, y que el contenido son hojas. Por lo tanto, algunas etiquetas nacerán dentro de otras etiquetas, y podrías encontrar contenido en alguna de las etiquetas más pequeñas 😉 Ahora, explorémoslas en orden para que entiendas a qué me refiero.

  ## **La regla: `<!DOCTYPE html>`**

  Primero, cada archivo HTML empieza con una etiqueta que se cierra sola. Esto es una convención y no modifica el contenido del sitio, pero es importante que empieces con ella.

  ```html
  <!DOCTYPE html>
  ```

  ## **El árbol: `<html>`**

  Debajo encontrarás el tronco del árbol: la etiqueta `<html>`. Todo el contenido del sitio va dentro de esta etiqueta, y está viene con un atributo que indica el idioma en que está escrito el sitio web.

  ```html
  <!DOCTYPE html>
  <html lang="es">

  </html>

  ```

  Después, el árbol se abre hacia dos secciones principales: la primera es `<head>`, dónde encontrarás la metadata del sitio web. Esta sección te ayudará a decirle al navegador cómo va a mostrar tu sitio web, y también te permite darle información a buscadores como google para que sepan cómo mostrar tu sitio.

  Y la segunda rama principal es `<body>`, donde introducirás el contenido que los usuarios van a ver cuando visiten tu sitio web.

  ```html
  <!DOCTYPE html>
  <html lang="es">
      <head>

      </head>
      <body>

      </body>
  </html>
  ```

  ## **Las raíces: `<head>`**

  La etiqueta `<head>` se parece mucho a las raíces de un árbol: el usuario no puede verlas, pero son fundamentales para que el sitio web funcione.

  Suele contener muchas etiquetas `<meta>` que revelan información sobre el sitio web al navegador y a buscadores como Google.

  También incluye la etiqueta `<title>` que tiene el título del sitio web (que aparece en la pestaña del navegador), y al menos una etiqueta <link> que carga la hoja de estilos de tu sitio web (el archivo “.css”; esto es lo que organiza los elementos de tu sitio web y les da forma y color).

  Aquí abajo te dejo un ejemplo muy común de lo que puedes encontrar en un `<head>`.

  ```html
  <!DOCTYPE html>
  <html lang="es">
      <head>
          <meta/>
          <meta/>
          <meta/>
          <title></title>
          <meta/>
          <link/>
      </head>
      <body>

      </body>
  </html>
  ```

  ## **Las ramas, hojas y flores: `<body>`**
  Mientras tanto, la etiqueta `<body>` contiene todo lo que el usuario puede ver en el sitio web, y también aquello con lo que puede interactuar. Esta puede ser tan compleja y diversa como las ramas de un arbol.

  Si has visitado un sitio web antes, seguro habrás notado que está construido en diferentes secciones, y las más comunes son `<header>`, `<main>`, `<aside>` y `<footer>`.

  ![Estructura común de un sitio web](https://static.platzi.com/media/articlases/Images/Clase%204%20-%202.png)

  ### La etiqueta `<script>`

  Además de esos 4, se acostumbra agregar una etiqueta `<script>` al final de `<body>`. Esta es la que tiene todo el código en JavaScript que introduces en tu sitio web para que haga cosas divertidas 😉

  Probablemente pensaste que esta etiqueta se coloca en `<head>` debido a que su contenido no se muestra al usuario. Y estás en lo cierto 🙂 En realidad funciona por igual tanto en `<head>` como en `<body>`. Pero, antes de decidir dónde colocarla, quiero que pienses en esto:

  ¿Recuerdas que **los archivos HTML cargan progresivamente de arriba a abajo**? Pues, por lo general, el usuario no interactúa con el sitio web hasta que este termina de cargar. Así que dejar `<script>` al final de `<body>` permite que tu sitio web cargue todo el aspecto visual antes de cargar su programa 😉

  Al final queda de tu parte (o de tu equipo de trabajo) decidir dónde colocar `<script>`. Pero es una práctica común dejarlo al final de `<body>` para que el sitio web se muestre más rápido al usuario 🙂

  ```html
  <!DOCTYPE html>
  <html lang="es">
      <head>

      </head>
      <body>
          <header>

          </header>
          <main>

          </main>
          <footer>

          </footer>
          <script></script>
      </body>
  </html>
  ```

  ### HTML semántico

  En este punto, ya puedes introducir etiquetas comunes de escritura como `<p>` o `<ol>`. Sin embargo, existen otras etiquetas que suelen usarse dentro de `<body>` para ordenar aún más la información, lo que beneficia a la accesibilidad, al posicionamiento de tu sitio web en buscadores, y en ocasiones también a la aplicación de estilos.

  Algunas etiquetas comunes de este estilo son:

  | **Etiqueta** | **Uso** |
  | --- | --- |
  | `<nav>` | Se usa para identificar el panel de navegación del sitio, dónde están los links al resto del contenido de tu sitio web. |
  | `<section>` | Se usa para separar un elemento html en secciones, cada una con un propósito. |
  | `<article>` | Se usa para identificar artículos individuales dentro de un sitio web. Se usa mucho para identificar entradas de un blog. |
  | `<figure>` | Se usa como un contenedor de imágenes, para manipular su tamaño con mayor facilidad en CSS, y para agregar un pie de foto. |
  | `<div>` | Este es un comodín. Es un contenedor que puede tener lo que sea dentro. Pero no beneficia la accesibilidad o el posicionamiento en buscadores. |

  Aquí abajo tienes un ejemplo de una estructura de HTML básica sin contenido. Verás que no es tan compleja luego de que conoces los elementos que la componen 😁

  ```html
  <!DOCTYPE html>
  <html lang="es">
      <head>
          <meta/>
          <meta/>
          <meta/>
          <title>Batata Bit</title>
          <meta/>
          <link/>
      </head>
      <body>
          <header>
              <nav>
              </nav>
          </header>
          <main>
              <section>
                  <article>
                  </article>
              </section>
          </main>
          <footer>
              <figure>
                  <img/>
              </figure>
          </footer>
          <script></script>
      </body>
  </html>

  ```

  Por cierto, abajo te dejé el mismo código, pero con atributos 😁 Como hay más texto, quizás pienses que es más “temible” cuando los tiene. Pero la realidad es que los atributos no cambian la estructura, solo agregan información 🙂

  Dale un vistazo para que te vayas acostumbrando a como se ven. Cuando empieces a usarlos te familiarizarás mucho más con ellos 😉

  ```html
  <!DOCTYPE html>
  <html lang="es">
      <head>
          <meta charset="utf-8" />
          <meta name="description" content="La próxima revolución en el intercambio de criptomonedas, Batatabit te ayuda a navegar entre los diferentes precios y tendencias" />
          <meta name="robots" content="index, follow" />
          <title>Batata Bit</title>
          <meta name="viewport" content="width=device-width, initial-scale=1.0" />
          <link rel="stylesheet" href="./styles/mobile.css" />
      </head>
      <body>
          <header class="header">
              <nav>
              </nav>
          </header>
          <main class="main">
              <section class="added-value">
                  <article class="added-value__cards--save-time">
                  </article>
              </section>
          </main>
          <footer>
              <figure class="footer__logo">
                  <img src="./assets/img/FooterLogo.svg" alt="El logo de batatabit" />
              </figure>
          </footer>
          <script src="./src/index.js"></script>
      </body>
  </html>

  ```

  Experimenta un poco con las etiquetas que conociste el día de hoy, y luego continúa tu aprendizaje aprendiendo a instalar tu primer editor de código: [Visual Studio Code](https://platzi.com/clases/3208-programacion-basica/51982-visual-studio-code/).

</details>


<details>
  <summary>06/84 - Instalando tu primer editor de código</summary>
  <br/>

  Si vas a aprender a programar, necesitas un editor de código. Pero ¿Por qué usar uno? ¿Cuál elegir? ¿Y cómo instalarlo? Quédate conmigo y respondamos todas esas preguntas 😉.

  ## **¿Qué es un editor de código?**

  En pocas palabras, un editor de código es un software que te permite escribir y editar código **en texto plano**, a la vez que te brinda herramientas varias para facilitar tu proceso de trabajo.

  El código se escribe en **texto plano**. Es decir, texto simple y sin ningún tipo de formato (como negritas, cursivas y variedades de tamaño o color). Por lo tanto, no puedes escribir código usando software dedicado a aplicar estos formatos en cartas y documentos (como Microsoft word, Google docs, o Pages).

  Así que necesitas un software especializado que te permita escribir texto plano, pero que al mismo tiempo te brinde herramientas para facilitar tu proceso de trabajo. Algunas de estas herramientas son: detector de errores en el código, herramientas para autocompletar, buscar y reemplazar; resaltados varios para facilitar la lectura del código, entre otros.

  Además. algunas de estas herramientas admiten la instalación de extensiones que permiten personalizar y ampliar aún más las capacidades del editor de código. Van desde asistencia con colores y resaltados, a herramientas de comunicación de equipos dentro del editor de código como [CodeStream](https://www.codestream.com/).

  ## **¿Qué editor de código instalo primero?**

  Si estás siguiendo este curso, te recomendamos que empieces probando [Visual Studio Code](https://code.visualstudio.com/).

  Existen muchos editores de código en el mercado, y la mayoría son gratuitos (incluyendo el block de notas o el “notepad” que viene con tu computadora). Sin embargo, Platzi eligió esta para ti porque es gratuita, corre en windows, mac y Linux; y es una de las mejor valoradas en el entorno profesional al momento de lanzar este curso (2022).

  ## **¿Cómo instalar Visual Studio Code?**

  1. Entra al sitio web oficial de [Visual Studio Code](https://code.visualstudio.com/) y descárgalo para tu sistema operativo.
  2. Ejecuta el instalador que se descargó en tu computadora.
  3. Acepta los términos y condiciones (si estás de acuerdo).
  4. Luego tendrás que indicarle al instalador si deseas que realice alguna tarea adicional (abajo te explico qué significan estas opciones), y le das a siguiente.
  5. Finalmente, esperas a que termine la instalación y le das finalizar 🙂

  ### Tareas adicionales durante la instalación de Visual Studio Code

  Te recomendamos habilitar las siguientes opciones: te recomendamos:

  1. Crear el acceso directo en el escritorio (para que puedas abrirlo desde el escritorio con facilidad).
  2. Agregar la acción “abrir en code” a los menu contextuales de archivo y de directorio (Esto te permite abrir archivos y carpetas desde el menú que se abre cuando haces click derecho en ellos).
  3. Registrar Code como editor para los tipos de archivo admitidos (para que tu computadora abra los archivos con Visual Studio Code en lugar del Notepad).
  4. Agregarlo al PATH (para que puedas abrir tus archivos y carpetas fácilmente desde la [terminal y línea de comandos](https://platzi.com/cursos/terminal/)).

  Estas opciones te beneficiarán en tu carrera cómo programador, especialmente si Visual Studio Code se convierte en tu editor de texto preferido.

  ![Vista de la ventana de "Tareas Adicionales" durante la instalación de Visual Studio Code (2022)](https://static.platzi.com/media/articlases/Images/Clase%206%20-%201.png)

  ## **Usando Visual Studio Code por primera vez**

  Solo la práctica te hará un maestro en Visual Studio Code. Sin embargo, déjame darte algunas nociones clave para que empieces a usarlo ahora mismo 👍

  ![Primera impresión de la ventana de Visual Studio Code (2022)](https://static.platzi.com/media/articlases/Images/Clase%206%20-%202.png)

  1. VSCode emplea ventanas al igual que el navegador de internet. Puedes trabajar con varios archivos a la vez desde la misma ventana.
  2. Por defecto, VSCode suele mostrar una ventana de bienvenida y otra con las mejoras de la última versión instalada. Puedes cerrarlas cuando quieras.
  3. Por defecto, VSCode te preguntará si confías en los autores de los archivos que intentes abrir. Esta es una medida de seguridad normal, y se toma para protegerte de archivos ejecutables que puedan puedan perjudicar tu computador.
  4. VSCode tiene un menú superior muy similar a los de otros software, pero también tiene un menú a la izquierda que se distingue por íconos en lugar de palabras. Estos despliegan un panel lateral con diferentes funcionalidades.
  - El primer botón es el explorador de archivos. Si decides abrir una carpeta entera con VSCode, este panel te permite navegar fácilmente por los diferentes archivos que se encuentran dentro de la carpeta.
  - El segundo botón es un buscador. Te permite buscar palabras en cualquiera de los archivos de la carpeta que tienes abierta (y resalta todas sus iteraciones).
  - El tercero tiene que ver con un software de control de versiones (algo indispensable para programar profesionalmente. Más información en el [Curso Profesional de Git y Github](https://platzi.com/cursos/git-github/)).
  - El cuarto es una herramienta interna de VSCode para correr y detectar bugs en el código.
  - El quinto abre un panel dónde podrás buscar e instalar extensiones para tu editor de código.
  1. El editor de VSCode tiene tema oscuro por defecto para que distingas la implementación de colores dentro del código.
  2. VSCode cuenta el número de líneas del archivo que tengas abierto. También destaca la indentación de código, y aplica un código de colores al texto del archivo (que depende de la extensión del archivo).
  3. VSCode emplea una vista miniatura del código en el extremo derecho de la ventana. Puedes usar este para navegar fácilmente por tu código.
  4. Puedes hacer zoom para aumentar el tamaño del código y facilitar su lectura. Puedes lograrlo pulsando Ctrl→”+” y Ctrl→”-”

  ## **Bonus: utf-8**

  El navegador no puede leer acentos y letras “ñ” si no indicas esto en el HTML.

  Es probable que ya te hayas dado cuenta de que estos acentos no se muestran bien cuando cargas el archivo HTML común y corriente en tu navegador. Esto se debe a que los acentos no pertenecen al set de caracteres que carga por defecto el HTML.

  Para usar caracteres comunes del español (como acentos y la letra “ñ”), necesitas activar el Unicode Transformation Format 8 (UTF-8) en tu archivo HTML colocando la siguiente etiqueta `<meta>` en el `<head>` de tu archivo:

  ```html
  <meta charset="utf-8" />
  ```

  Esta se ve así dentro del código:

  ```html
  <!DOCTYPE html>
  <html lang="es">
      <head>
          <meta charset="utf-8" />
      </head>
      <body>

      </body>
  </html>
  ```

  ¿Qué tal si creas un nuevo archivo HTML, pero esta vez desde Visual Studio Code? 🙂

  Experimenta un poco, y nos vemos a continuación en la siguiente clase: [Como declarar variables y usar prompt](https://platzi.com/clases/3208-programacion-basica/51983-prompt/) 😉

</details>



<details>
  <summary>07/84 - Cómo declarar variables y usar prompt</summary>
  <br/>

  Estos dos procesos pueden ser muy útiles cuando estás aprendiendo a programar.

  ## **Cómo declarar variables en JavaScript**

  Sin complicarnos mucho, puedes declarar una variable en JavaScript escribiendo lo siguiente:

  1. La palabra reservada “let”.
  2. El nombre que quieres para tu variable.
  3. El signo “=” para asignar un valor a ese nombre.
  4. El valor que quieres para la variable. Puede ser texto (strings), números, y otras cosas que aprenderás si profundizas un poco más en JavaScript.

  ```jsx
  let a = 1;
  ```

  “Declarar una variable” consiste en reservar un nombre en la memoria de la computadora y asignarle el valor que tú indiques.

  En JavaScript (el lenguaje que entienden los navegadores de internet) hay varias formas de declarar una variable. Sin embargo, cuando estas empezando, puedes declarar variables con “let” sin mayor problema 👍

  ## **Uso de promt()**

  “Prompt()” es una función nativa del navegador. Cuando la usas, esta dispara una pequeña ventana con el texto que indiques entre los paréntesis, dónde le pide al usuario que te entregue alguna información. Por lo tanto, podemos usarla para obtener información del usuario y usarla en otro lugar.

  Ejemplo:

  ```jsx
  let nombre = "";
  nombre = prompt("¿Cuál es tu nombre?");
  alert(nombre + ", Bienvenido a Platzi :)");
  ```

  Prueba a correr ese código en el navegador para que veas lo que ocurre, y animate a experimentar un poco con lo que aprendiste aquí 😊

  Luego, pasa con confianza a la siguiente clase: [Algoritmo de piedra, papel o tijera](https://platzi.com/clases/3208-programacion-basica/51984-algoritmo-de-piedra-papel-o-tijera/).

</details>

<details>
  <summary>08/84 - Algoritmo de piedra, paper o tijera</summary>
  <br/>

  Ahora que conoces lo más básico de programar ¿te animas a crear un pequeño juego de piedra papel o tijera con tu navegador?

  Esta clase requiere que sepas lo fundamental sobre crear archivos HTML y escribir código JavaScript. Si aún no lo sabes, entonces visita [la primera clase del curso](https://platzi.com/clases/3208-programacion-basica/52069-que-es-platzi/) y empieza desde allí 🙂 Esta es la clase número 9 del curso gratis de programación básica de Platzi 💚

  ## **Tips para aprender a programar**

  Ahora, antes de empezar, déjame darte algunos tips que seguro te ayudarán 😉

  ### Escribe comentarios con “//”

  La computadora ignora todo lo que escribas después de un “//” en una línea de código. Así que puedes usar esto para dejar mensajes útiles para ti (o tus compañeros) a lo largo del código.

  Por ejemplo:

  ```jsx
  //RECOGIENDO LA ELECCIÓN DEL JUGADOR
  let eleccionJugador = prompt(); // Aquí el jugador elije piedra, papel o tijera

  ```

  ### Nombra variables

  Se recomienda fuertemente usar nombres que dejen claro el propósito de la variable. Evita usar nombres sencillos como “a”, porque puedes olvidar que es lo que hace cuando trabajas con muchas variables a la vez.

  La práctica más común es utilizar nombres compuestos por varias palabras en Camel Case (sin espacios, empezando en minúscula, y colocando en mayúscula la inicial de todas las palabras después de la primera).

  Ojo, recuerda no emplear acentos ni “ñ” en tu código para evitar errores de lectura.

  Por ejemplo:

  ```jsx
  eleccionUsuario
  nombreUsuario
  primerApellidoUsuario
  fechaNacimientoUsuario
  ```

  ### Utiliza condicionales

  Si lo piensas bien, el juego de piedra, papel y tijera requiere de condiciones como “si el jugador elije piedra y la computadora elije piedra, entonces el jugador gana”.

  Para hacer eso en JavaScript debes seguir una formula sencilla:

  ```jsx
  if ( variableAComparar == ValorDeComparacion ) {
      //Código a ejecutar si la condición se cumple
  }
  else if ( variableAComparar == ValorDeComparacion2 ) {
      //Código a ejecutar si la condición 1 no se cumple, pero la segunda sí
  }
  else ( variableAComparar == ValorDeComparacion3 ) {
      //Código a ejecutar si ninguna condición se cumple
  }
  ```

  En resumen:

  1. Usas `if` para evaluar la primera condición. `else if`, para evaluar más condiciones si la primera no se cumple, y `else` para decir lo que ocurrirá si ninguna otra condición se cumple.
  2. Entre los paréntesis escribes la condición que deseas evaluar. Por lo general se compara una variable con un valor.
  3. Recuerda que `=` se utiliza para asignar valores a las variables. Si deseas comparar variables con valores dentro de un `if`, entonces debes emplear un `==`. También puedes emplear un `===`si quieres comparar tanto el valor como el tipo de dato (número, string, o *boolean).
  4. El código que escribas entre `{}` es el código que se va a ejecutar si la condición entre paréntesis se cumple.

  💡 Los datos tipo **Boolean** son datos “Verdadero o falso”. Puedes escribirlos como `true` / `false` o 1 / 0. Por lo regular son muy útiles 👍

  ## **Escribiendo el algoritmo**

  Esto lo vamos a hacer en dos partes. Y lo primero es crear el archivo HTML dónde vamos a escribir nuestro código, abrirlo en nuestro editor de código, y escribir la base en HTML.

  Intenta hacerlo sin ayuda 😉 Y si te pierdes, aquí te dejo el código que deberías preparar de primeras.

  ```html
  <!DOCTYPE html>
  <html>
      <head>
          <meta charset="utf-8" />
          <title>Algoritmo piedra, papel o tijera</title>
          <script>

          </script>
      </head>
      <body>
          <h1>Piedra, papel o tijera</h1>
      </body>
  </html>
  ```

  Luego escribiremos un código que nos permita saber si el jugador elije piedra papel o tijera. Intenta crear una variable que capture la elección del jugador usando un `prompt()`. Explícale que escriba 1 para piedra, 2 para papel o 3 para tijera, y luego recuérdale el número que eligió con un `alert()`.

  Intenta hacerlo sin ver la solución. Cuando termines, compara lo que obtuviste con el código de abajo y sigue leyendo:

  ```html
  <!DOCTYPE html>
  <html>
      <head>
          <meta charset="utf-8" />
          <title>Algoritmo piedra, papel o tijera</title>
          <script>
              //OBTENIENDO LA ELECCIÓN DEL JUGADOR
              let eleccionDelJugador = 0;
              eleccionDelJugador = prompt("Elige: 1 para piedra, 2 para papel, 3 para tijera");
              alert("Elegiste " + jugador);
          </script>
      </head>
      <body>
          <h1>Piedra, papel o tijera</h1>
      </body>
  </html>
  ```

  Bien, ahora probemos con la condición. Primero convierte el recordatorio en un comentario. Vamos a crear un recordatorio más preciso, uno que le diga al usuario si eligió piedra, papel, tijera, o algo más.

  Para hacerlo, inicia una condición dónde vas a hacer tres comparaciones. Primero usa un `if` para evaluar si el jugador eligió piedra. Si lo hizo, envíale un `alert()` indicándole que eligió piedra. Luego usa un par de `else if` para evaluar si eligió papel o tijeras, y envíale un `alert()` en cada uno informándole de su decisión.

  Finalmente, emplea un `else` para evitar que el jugador quiera pasarse de listo al escribir algo que no sea 1, 2 o 3. En ese caso, envíale un `alert()` indicándole que elija 1, 2 o 3 (o juegale una broma. Es tu juego después de todo 😉).

  Intenta hacerlo por tu cuenta. Y cuando termines, compáralo con el código de abajo antes de continuar.

  ¡Recuerda probar tu código en el navegador y pulirlo hasta que funcione!

  ```html
  <!DOCTYPE html>
  <html>
      <head>
          <meta charset="utf-8" />
          <title>Algoritmo piedra, papel o tijera</title>
          <script>
              //OBTENIENDO LA ELECCIÓN DEL JUGADOR
              let eleccionDelJugador = 0;
              eleccionDelJugador = prompt( "Elige: 1 para piedra, 2 para papel, 3 para tijera" );
              // alert( "Elegiste " + jugador );

              //INFORMANDO LA ELECCIÓN DEL JUGADOR
              if ( eleccionDelJugador == 1 ) {
                  alert( "Elegiste piedra" );
              }
              else if ( eleccionDelJugador == 2 ) {
                  alert( "Elegiste papel" )
              }
              else if ( eleccionDelJugador == 3 ) {
                  alert( "Elegiste tijera" )
              }
              else {
                  alert( "Elegiste otra cosa, así no puedes jugar >-<" )
              }
          </script>
      </head>
      <body>
          <h1>Piedra, papel o tijera</h1>
      </body>
  </html>
  ```

  Dejémoslo hasta aquí por ahora. Intenta reproducir este código por tu cuenta ahora que sabes cómo funciona. Y cuando estés listo, acompáñame a terminar este pequeño juego en: [Algoritmo avanzado de piedra, papel o tijera](https://platzi.com/clases/3208-programacion-basica/51985-algoritmo-avanzado-de-piedra-papel-o-tijera/)

</details>

<details>
  <summary>09/84 - Algoritmo avanzado de piedra, papel o tijera</summary>
  <br/>
  
  Ya construimos la base de nuestro juego de piedra, papel o tijera. Ahora pongámoslo a funcionar. Esta es la segunda parte del ejercicio de [programar un juego de piedra, papel o tijera](https://platzi.com/clases/3208-programacion-basica/51984-algoritmo-de-piedra-papel-o-tijera/) que planteamos la clase anterior. Visita la clase si deseas ver cómo llegamos hasta aquí 😉

  ## **¿Dónde nos quedamos?**

  Aquí nos quedamos. Compáralo con tu código, o construye el tuyo para continuar la clase 🙂

  > 💡 Ojo, no copies y pegues si no lo has hecho aún. Al contrario, aprovecha la oportunidad para practicar 😉
  > 

  Sin embargo, si tienes problemas para visualizarlo por el tamaño de la ventana, prueba copiandolo y pegandolo en un archivo HTML diferente al tuyo en Visual Studio Code. Ahí deberías poder verlo bien 👍

  ```html
  <!DOCTYPE html>
  <html>
      <head>
          <meta charset="utf-8" />
          <title>Algoritmo piedra, papel o tijera</title>
          <script>
              //OBTENIENDO LA ELECCIÓN DEL JUGADOR
              let eleccionDelJugador = 0;
              eleccionDelJugador = prompt( "Elige: 1 para piedra, 2 para papel, 3 para tijera" );
              // alert( "Elegiste " + jugador );

              //INFORMANDO LA ELECCIÓN DEL JUGADOR
              if ( eleccionDelJugador == 1 ) {
                  alert( "Elegiste piedra" );
              }
              else if ( eleccionDelJugador == 2 ) {
                  alert( "Elegiste papel" )
              }
              else if ( eleccionDelJugador == 3 ) {
                  alert( "Elegiste tijera" )
              }
              else {
                  alert( "Elegiste otra cosa, así no puedes jugar >-<" )
              }
          </script>
      </head>
      <body>
          <h1>Piedra, papel o tijera</h1>
      </body>
  </html>

  ```

  ## **La elección de la computadora**

  Necesitamos un oponente para este juego, así que primero debemos trabajar en la elección de la computadora.

  Lógico quieres que la computadora elija una opción al azar para el juego. Pero eso lo construiremos en la clase de [aleatoriedad](https://platzi.com/clases/3208-programacion-basica/51986-aleatoriedad/) 😉 Mientras tanto, usa comentarios y espacios para crear un apartado dónde escribiremos este código más tarde; y escribe en una línea que la computadora. Elige una de las tres opciones (puede ser la que tú quieras, con los números que empleamos para la elección del jugador).

  ¿Ya lo hiciste? Inténtalo por tu cuenta, y luego compáralo con el código aquí abajo 😉

  ```html
  <!DOCTYPE html>
  <html>
      <head>
          <meta charset="utf-8" />
          <title>Algoritmo piedra, papel o tijera</title>
          <script>
              //OBTENIENDO LA ELECCIÓN DEL JUGADOR
              let eleccionDelJugador = 0;
              eleccionDelJugador = prompt( "Elige: 1 para piedra, 2 para papel, 3 para tijera" );
              // alert( "Elegiste " + jugador );

              //INFORMANDO LA ELECCIÓN DEL JUGADOR
              if ( eleccionDelJugador == 1 ) {
                  alert( "Elegiste piedra" );
              }
              else if ( eleccionDelJugador == 2 ) {
                  alert( "Elegiste papel" )
              }
              else if ( eleccionDelJugador == 3 ) {
                  alert( "Elegiste tijera" )
              }
              else {
                  alert( "Elegiste otra cosa, así no puedes jugar >-<" )
              }

              //OBTENIENDO LA ELECCIÓN DEL COMPUTADOR
              let eleccionDelComputador = 1;

          </script>
      </head>
      <body>
          <h1>Piedra, papel o tijera</h1>
      </body>
  </html>

  ```

  ## **Anunciando la elección del computador**

  Antes de proceder, planteemos un momento como queremos que se produzca el juego:

  1. El juego pide su elección al jugador, y luego le informa cuál fue su elección.
  2. El juego asigna una elección a la computadora, y luego le informa al jugador la elección de la computadora.
  3. El juego evalúa ambas elecciones, decide el ganador, y muestra un mensaje informando el veredicto.

  Por lo tanto, ahora que la computadora ya eligió, crea un apartado que informe la elección de la computadora con un `alert()` 🙂 crea un apartado para esto, y recicla el código que usaste para informar la elección del jugador para que muestre ahora la elección del computador 😉

  > 💡 ¡Por cierto! También puedes usar emojis en los mensajes. Puedes utilizarlos desde la emojipedia o, si estás en windows, puedes pulsar Win+”.” para abrir la ventana de emojis 🙂
  > 

  Hazlo tú y pruébalo en el navegador para validar que esté funcionando bien. Luego compáralo con el código de abajo antes de continuar 😉

  ```html
  <!DOCTYPE html>
  <html>
      <head>
          <meta charset="utf-8" />
          <title>Algoritmo piedra, papel o tijera</title>
          <script>
              //OBTENIENDO LA ELECCIÓN DEL JUGADOR
              let eleccionDelJugador = 0;
              eleccionDelJugador = prompt( "Elige: 1 para 🥌, 2 para 📄, 3 para ✂️" );
              // alert( "Elegiste " + jugador );

              //INFORMANDO LA ELECCIÓN DEL JUGADOR
              if ( eleccionDelJugador == 1 ) {
                  alert( "Elegiste 🥌" );
              }
              else if ( eleccionDelJugador == 2 ) {
                  alert( "Elegiste 📄" )
              }
              else if ( eleccionDelJugador == 3 ) {
                  alert( "Elegiste ✂️" )
              }
              else {
                  alert( "Elegiste otra cosa, así no puedes jugar 😣" )
              }

              //OBTENIENDO LA ELECCIÓN DEL COMPUTADOR
              let eleccionDelComputador = 1;

              //INFORMANDO LA ELECCION DEL COMPUTADOR
              if ( eleccionDelComputador == 1 ) {
                  alert( "La computadora eligió 🥌" );
              }
              else if ( eleccionDelComputador == 2 ) {
                  alert( "La computadora eligió 📄" )
              }
              else if ( eleccionDelComputador == 3 ) {
                  alert( "La computadora eligió ✂️" )
              }
              else {
                  alert( "Cometí un error programando la elección del computador 🙃" )
              }

          </script>
      </head>
      <body>
          <h1>Piedra, papel o tijera</h1>
      </body>
  </html>
  ```

  ## **¿Quién gana y quién pierde?**

  Crea un nuevo apartado para saber si ganas o pierdes. Allí debes escribir condiciones para evaluar:

  - Cuándo empatas.
  - Cuándo ganas.
  - Cuándo pierdes.

  Luego de evaluar esto, utiliza un `alert()` para informarle al jugador si ganó, empató o perdió 👍

  💡 Ojo, puedes evaluar varias condiciones a la vez en un solo `if` si separas las condiciones con un `&&`. Por ejemplo:

  ```jsx
  if ( eleccionDelJugador = 1 && eleccionDelComputador = 3 ) {
      alert( "¡GANASTE! 🥳" );
  }
  ```

  Empieza escribiendo la condición de empate (que es la más fácil) y luego escribe las demás. Inténtalo, pruébalo en el navegador, cambia la elección del computador para validar que en serio todo funciona, y luego compara tu código con el ejemplo de abajo 👍

  ```html
  <!DOCTYPE html>
  <html>
      <head>
          <meta charset="utf-8" />
          <title>Algoritmo piedra, papel o tijera</title>
          <script>
              //OBTENIENDO LA ELECCIÓN DEL JUGADOR
              let eleccionDelJugador = 0;
              eleccionDelJugador = prompt( "Elige: 1 para 🥌, 2 para 📄, 3 para ✂️" );
              // alert( "Elegiste " + jugador );

              //INFORMANDO LA ELECCIÓN DEL JUGADOR
              if ( eleccionDelJugador == 1 ) {
                  alert( "Elegiste 🥌" );
              }
              else if ( eleccionDelJugador == 2 ) {
                  alert( "Elegiste 📄" )
              }
              else if ( eleccionDelJugador == 3 ) {
                  alert( "Elegiste ✂️" )
              }
              else {
                  alert( "Elegiste otra cosa, así no puedes jugar 😣" )
              }

              //OBTENIENDO LA ELECCIÓN DEL COMPUTADOR
              let eleccionDelComputador = 1;

              //INFORMANDO LA ELECCION DEL COMPUTADOR
              if ( eleccionDelComputador == 1 ) {
                  alert( "La computadora eligió 🥌" );
              }
              else if ( eleccionDelComputador == 2 ) {
                  alert( "La computadora eligió 📄" )
              }
              else if ( eleccionDelComputador == 3 ) {
                  alert( "La computadora eligió ✂️" )
              }
              else {
                  alert( "Cometí un error programando la elección del computador 🙃" )
              }

              //DECIDIENDO EL GANADOR
              if ( eleccionDelJugador == eleccionDelComputador ) {
                  alert( "¡EMPATE! 🤼" );
              }
              else if ( eleccionDelJugador == 1 && eleccionDelComputador == 3 ) {
                  alert( "¡GANASTE! 🥳" );
              }
              else if ( eleccionDelJugador == 2 && eleccionDelComputador == 1 ) {
                  alert( "¡GANASTE! 🥳" );
              }
              else if ( eleccionDelJugador == 3 && eleccionDelComputador == 2 ) {
                  alert( "¡GANASTE! 🥳" );
              }
              else {
                  alert( "PERDISTE... 😢" );
              }

          </script>
      </head>
      <body>
          <h1>Piedra, papel o tijera</h1>
      </body>
  </html>

  ```

  ¿Te divertiste?

  Existen muchos caminos para llegar a la misma solución. Puedes abordar el problema de varias formas y personalizarlo a tu gusto. Si te dio error en algún lado, no te preocupes. Resolver errores en el código es la mitad del trabajo de un programador. Desarrolla tu tolerancia a la frustración, y tómalo como parte del oficio.

  Experimenta un poco con tu código, personalízalo y cuando estés listo continúa a la clase de [aleatoriedad](https://platzi.com/clases/3208-programacion-basica/51986-aleatoriedad/) para que aprendas a hacer que la computadora elija por si misma lo que va a jugar 😁

</details>

<details>
  <summary>10/84 - Aleatoriedad</summary>
  <br/>

  Ya programamos lo básico para que el juego funcione. Pero es momento de hacer que el computador elija por si solo entre piedra, papel, o tijera. Necesito compartirte algunos fundamentos para que realices la práctica de hoy. Estos son:

  ## **El objeto “Math” en JavaScript**

  En JavaScript existen entidades llamadas “Objetos” que guardan dentro de ellas variables (que se llaman “propiedades” cuando viven dentro de un objeto) y funciones (que se llaman “métodos” cuando viven dentro de un objeto.

  En este sentido, **Math** es un objeto especial en JavaScript que contiene dentro de él numerosas funciones y valores que son esenciales para hacer cálculos matemáticos, como el número PI o la función de redondear números decimales.

  ## **¿Cómo usar el objeto Math de JavaScript?**

  Debes escribir “Math” (atención a la “M” en mayúscula), luego un punto (”.”) y finalmente la propiedad o método que desees invocar.

  Si deseas invocar un método, recuerda que debes escribir los paréntesis “( )” para que el método se ejecute.

  ### Ejemplos de propiedades

  | **Propiedades de Math** | **Para qué sirve** |
  | --- | --- |
  | `Math.PI` | Cuándo el código se ejecuta, el navegador sustituye esto por el número PI. |
  | `Math.E` | Cuándo el código se ejecuta, el navegador sustituye esto por la constante de Euler. |

  ### Ejemplos de métodos

  | **Métodos de Math** | **Para qué sirven** |
  | --- | --- |
  | `Math.ceil()` | Redondea hacia arriba el número decimal que esté entre los paréntesis, hasta convertirlo en un número entero. |
  | `Math.floor()` | Redondea hacia abajo el número decimal que esté entre los paréntesis, hasta convertirlo en un número entero. |
  | `Math.round()` | Redondea el número decimal entre paréntesis hacia el entero más cercano. |
  | `Math.random()` | Retorna un número decimal aleatorio entre el 0 (incluido) y el 1 (excluido). |

  Prueba estos valores y métodos en la consola del navegador 🙂

  ## **¿Cómo declarar funciones en JavaScript?**

  Cuando encuentras un segmento de código que puede repetirse dentro del programa, o que ejecuta un proceso muy específico dentro de tu código, entonces lo ideal es encapsularlo en una función.

  Hay varias formas de declarar una función. Pero la más básica de todas consiste en escribir la palabra reservada `function`, seguida de la función con sus parámetros entre paréntesis, y el bloque de código entre llaves `{ }`.

  Ejemplo:

  ```jsx
  function hacerAlgo( param1 , param2 ) {
      let resultado = param1 + param2;
      return resultado;
  }

  hacerAlgo( 3 , 4 ); //Devuelve 7
  ```

  Cuando ejecutas la función, esta ejecuta todo el código que insertaste dentro de las llaves `{ }` cuando la declaraste. De este modo, puedes ejecutar la función tantas veces como necesites con solo declararla una vez.

  Cuando la declaras, puedes indicar parámetros y usarlos dentro del bloque de código. Luego, cuando la ejecutes, esos parámetros se sustituirán con los valores que escribas entre paréntesis al momento de ejecutarla.

  También puedes utilizar la palabra reservada `return` dentro del bloque de código de la función para que, al ejecutarla, recibas el valor que indiques luego de escribir `return` (ojo, cuando la función llega a un `return`, su ejecución se detiene. Los comandos que escribas después de un `return` no se van a ejecutar).

  Haz algunos experimentos con esto en la consola antes de continuar 😉

  ## **Generando una elección aleatoria para el computador**

  Intentemos ahora emplear lo aprendido para hacer que la computadora elija piedra, papel o tijera por si sola. Para hacerlo, primero tenemos que entender cómo funcionaría el algoritmo que le permite hacer la selección, y luego tendríamos que introducirlo en nuestro código.

  ### Algoritmo de selección aleatoria

  Primero necesitamos generar un número aleatorio. Ya sabemos que `Math.random()` nos entrega un número aleatorio entre 0 y 1. Sin embargo, nuestro juego necesita un número aleatorio entre 3 y 1 para funcionar. ¿Se te ocurre cómo podrías crearlo con código?

  Para lograrlo, la operación sería esta:

  ```jsx
  Math.random() * ( max - min + 1 ) + min
  ```

  Si consideramos que nuestro valor máximo es 3 y el mínimo es 1, esto nos garantiza que siempre obtendremos un número entre 3.9999’ y 1. Por lo tanto, solo tendríamos que meter todo dentro de un `Math.floor()` para obtener un valor aleatorio entre 3 y 1.

  ![Formula para emitir números aleatorios en un rango](https://static.platzi.com/media/articlases/Images/10-1%20-%20Formula%20para%20emitir%20n%C3%BAmeros%20aleatorios%20en%20un%20rango.jpg)

  Por lo tanto, para conseguir que la computadora elija aleatoriamente, necesitaríamos el siguiente código:

  ```jsx
  //OBTENIENDO LA ELECCIÓN DEL COMPUTADOR
  let max = 3;
  let min = 1;
  let eleccionDelComputador = Math.floor( Math.random() * ( max - min + 1 ) + min );

  ```

  Introduce esto en tu código, y prueba a ver como funciona 🙂

  ## **Convirtiendo el algoritmo en una función**

  Ahora, ¿por qué no intentas convertir eso en una función? Te dejaré una posible solución aquí abajo para que compares, pero intenta hacerlo por tu cuenta antes de fijarte en ella 😉

  ```jsx
  //OBTENIENDO LA ELECCIÓN DEL COMPUTADOR
  function numeroAleatorio( min , max ) {
      return Math.floor( Math.random() * ( max - min + 1 ) + min );
  }
  let eleccionDelComputador = numeroAleatorio( 1 , 3 );

  ```

  Haz el cambio y prueba tu juego 😁 Sin embargo, ¿Crees que podrías escribir el mismo código en menos líneas? 🤔 No hablo de borrar espacios o líneas, hablo de emplear una lógica diferente para llegar al mismo resultado. Una que requiera menos pasos, y que aun así llegue al mismo sitio 🙂

  Piensa un poco al respecto, experimenta un poco, y cuando estés satisfecho y todo funcione, acompáñame a aprender más sobre como [usar funciones para mejorar la calidad de tu código](https://platzi.com/clases/3208-programacion-basica/51987-refactoring-de-funciones/) 😉 Nos vemos allá 😁

</details>

<details>
  <summary>11/84 - Creación y uso de funciones en programación</summary>
  <br/>
</details>

<details>
  <summary>12/84 - Ciclos y Condiciones en Programación: Piedra, Papel o Tijera</summary>
  <br/>
</details>

<details>
  <summary>13/84 - Gana 3 veces</summary>
  <br/>
</details>

<details>
  <summary>14/84 - Archivos de HTML y Javascript</summary>
  <br/>
</details>

<details>
  <summary>15/84 - ¿Qué es el DOM?</summary>
  <br/>
</details>
<br/>

### 🖥️ Desarrollando un juego con HTML y Javascript
<details>
  <summary>17/84 - Maquetación de Páginas Web para Videojuegos en HTML</summary>
  <br/>
</details>

<details>
  <summary>18/84 - Selección de Mascotas en HTML para Juegos Interactivos</summary>
  <br/>
</details>

<details>
  <summary>19/84 - Programar eventos de clic en botones HTML con JavaScript</summary>
  <br/>
</details>

<details>
  <summary>20/84 - Eventos de Carga en JavaScript: Iniciar Juego y Seleccionar Mascota</summary>
  <br/>
</details>

<details>
  <summary>21/84 - Selección de Mascota en JavaScript: Implementación y Validación</summary>
  <br/>
</details>

<details>
  <summary>22/84 - Manipulación del DOM con JavaScript para mostrar mascota seleccionada</summary>
  <br/>
</details>

<details>
  <summary>23/84 - Selección Aleatoria de Mascota Enemiga en JavaScript</summary>
  <br/>
</details>

<details>
  <summary>24/84 - Eventos de clic y lógica de ataque en JavaScript</summary>
  <br/>
</details>

<details>
  <summary>25/84 - Ataques Aleatorios para Mascotas Enemigas en JavaScript</summary>
  <br/>
</details>

<details>
  <summary>26/84 - Creación de Mensajes Dinámicos en Combate HTML y JavaScript</summary>
  <br/>
</details>

<details>
  <summary>27/84 - Lógica de Combate en JavaScript para Juego Mokepon</summary>
  <br/>
</details>

<details>
  <summary>28/84 - Operadores Lógicos en Programación: AND, OR y NOT</summary>
  <br/>
</details>

<details>
  <summary>29/84 - Actualización de Vidas en Juego de Combate con JavaScript</summary>
  <br/>
</details>

<details>
  <summary>30/84 - Validación de Vidas y Mensajes Finales en Juegos</summary>
  <br/>
</details>

<details>
  <summary>31/84 - Funcionalidad de Reinicio y Desactivación de Botones en Juego</summary>
  <br/>
</details>

<details>
  <summary>32/84 - Mostrar y ocultar secciones en HTML con JavaScript</summary>
  <br/>
</details>
<br/>

### 🖥️ Estilos con CSS
<details>
  <summary>34/84 - Estilos CSS: Selectores, Propiedades y Valores</summary>
  <br/>
</details>

<details>
  <summary>35/84 - Tipos de Visualización en CSS: Display Block, Inline e Inline Block</summary>
  <br/>
</details>

<details>
  <summary>36/84 - Alineación de Elementos con Flexbox en CSS</summary>
  <br/>
</details>

<details>
  <summary>37/84 - Modelo de Caja en CSS: Espaciado y Bordes</summary>
  <br/>
</details>

<details>
  <summary>38/84 - Diseño y Estilo de Páginas Web con HTML y CSS</summary>
  <br/>
</details>

<details>
  <summary>39/84 - Estilos CSS para Botones en Juegos: Diseño de Pantallas Interactivas</summary>
  <br/>
</details>

<details>
  <summary>40/84 - Estilos CSS para Mejorar la Interfaz de un Juego</summary>
  <br/>
</details>

<details>
  <summary>41/84 - Estilizado de Pantallas de Juego con CSS y Flexbox</summary>
  <br/>
</details>

<details>
  <summary>42/84 - Separación de mensajes y estilos en JavaScript y HTML</summary>
  <br/>
</details>

<details>
  <summary>43/84 - CSS Grid: Organiza Elementos en Rejillas Bidimensionales</summary>
  <br/>
</details>

<details>
  <summary>44/84 - Diseño Responsivo con CSS: Media Queries y Flexbox</summary>
  <br/>
</details>

<details>
  <summary>45/84 - Pseudoclases en CSS: Mejora la Interacción del Usuario</summary>
  <br/>
</details>
<br/>

### Optimización de código
<details>
  <summary>47/84 - Optimización de Código JavaScript con Clases y Objetos</summary>
  <br/>
</details>

<details>
  <summary>48/84 - Optimización de Código JavaScript: Variables y Funciones</summary>
  <br/>
</details>

<details>
  <summary>49/84 - Clases y Objetos: Fundamentos para Optimizar Juegos</summary>
  <br/>
</details>

<details>
  <summary>50/84 - Construcción de Clases y Objetos en JavaScript</summary>
  <br/>
</details>

<details>
  <summary>51/84 - Uso de Arreglos para Almacenar Objetos en JavaScript</summary>
  <br/>
</details>

<details>
  <summary>52/84 - Agregar ataques a objetos en JavaScript</summary>
  <br/>
</details>

<details>
  <summary>53/84 - Renderizado Dinámico de Objetos en HTML con JavaScript</summary>
  <br/>
</details>

<details>
  <summary>54/84 - Solución de errores en variables y elementos HTML en JavaScript</summary>
  <br/>
</details>

<details>
  <summary>55/84 - Uso de Objetos para Centralizar Información en JavaScript</summary>
  <br/>
</details>

<details>
  <summary>56/84 - Selección de Mascota Aleatoria en JavaScript</summary>
  <br/>
</details>

<details>
  <summary>57/84 - Iteración de Arreglos y Manipulación DOM en JavaScript</summary>
  <br/>
</details>

<details>
  <summary>58/84 - Crear Función "mostrarAtaques" en JavaScript para Juegos</summary>
  <br/>
</details>

<details>
  <summary>59/84 - Eventos de Clic en Botones con JavaScript</summary>
  <br/>
</details>

<details>
  <summary>60/84 - Secuencia de Ataques y Validación de Resultados en JavaScript</summary>
  <br/>
</details>

<details>
  <summary>61/84 - Implementación de lógica de combate en juegos JavaScript</summary>
  <br/>
</details>

<details>
  <summary>62/84 - Programación de Juegos: Lógica de Ataques y Victorias</summary>
  <br/>
</details>

<details>
  <summary>63/84 - Optimización y Corrección de Errores en Juegos Web con JavaScript</summary>
  <br/>
</details>

### Mapa con canvas
<details>
  <summary>65/84 - Dibujo y manejo de gráficos en Canvas con JavaScript</summary>
  <br/>
</details>

<details>
  <summary>66/84 - Movimiento de Capipepo en Canvas con HTML y JavaScript</summary>
  <br/>
</details>

<details>
  <summary>67/84 - Movimiento Continuo de Personajes en Canvas con JavaScript</summary>
  <br/>
</details>

<details>
  <summary>68/84 - Eventos de Teclado para Controlar Personajes en Juegos</summary>
  <br/>
</details>

<details>
  <summary>69/84 - Pintar Fondos y Personajes en Canvas HTML</summary>
  <br/>
</details>

<details>
  <summary>70/84 - Métodos de Clases en JavaScript para Juegos Interactivos</summary>
  <br/>
</details>

<details>
  <summary>71/84 - Detección de Colisiones en Videojuegos con JavaScript</summary>
  <br/>
</details>

<details>
  <summary>72/84 - Programación de eventos y colisiones en un juego interactivo</summary>
  <br/>
</details>

<details>
  <summary>73/84 - Programación de eventos y colisiones en un juego interactivo</summary>
  <br/>
</details>

<details>
  <summary>74/84 - Programación de eventos y colisiones en un juego interactivo</summary>
  <br/>
</details>
<br/>

### Backend: videojuego multijugador
<details>
  <summary>76/84 - Desarrollo de Juegos Multijugador con Cliente-Servidor y API</summary>
  <br/>
</details>

<details>
  <summary>77/84 - Instalación de Node.js en Windows para desarrollo backend</summary>
  <br/>
</details>

<details>
  <summary>78/84 - Uso básico de la terminal de comandos y Node.js</summary>
  <br/>
</details>

<details>
  <summary>79/84 - Creación de un Servidor Básico con Express.js en Node.js</summary>
  <br/>
</details>

<details>
  <summary>79/84 - Conceptos Clave de URIs y Verbos HTTP en Node.js</summary>
  <br/>
</details>

<details>
  <summary>79/84 - Desarrollo de API con Node.js y Comunicación Frontend-Backend</summary>
  <br/>
</details>

<details>
  <summary>79/84 - Selección de Mokepon y Comunicación JSON en Express.js</summary>
  <br/>
</details>

<details>
  <summary>79/84 - Implementación de un Endpoint para Coordenadas de Jugadores en Node.js</summary>
  <br/>
</details>

<details>
  <summary>79/84 - Integración de Coordenadas de Jugadores en Mokepon Multijugador</summary>
  <br/>
</details>

<details>
  <summary>79/84 - Optimización de Coordenadas en Videojuegos con JavaScript</summary>
  <br/>
</details>

<details>
  <summary>79/84 - Batalla Final en Mokepon: Implementación de Colisiones y Back-End</summary>
  <br/>
</details>

<details>
  <summary>Implementación de Ataques en Tiempo Real para Videojuego Mokepon</summary>
  <br/>
</details>
<br/>

### Próximos pasos
<details>
  <summary>79/84 - Corrección de errores en juego multijugador con Node.js</summary>
  <br/>
</details>

<details>
  <summary>79/84 - Desarrollo Colaborativo con Git y GitHub para Programadores</summary>
  <br/>
</details>