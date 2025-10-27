
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
💡

💡 Los lenguajes de programación tienen reglas de escrituras. Si te equivocas, la computadora no entenderá lo que dices y te avisará mostrándote un error.

</aside>

Los errores que derivan de errores de escritura en el código se llaman **errores de sintaxis** y son bastante comunes, en especial cuando estás aprendiendo a programar.

</details>

<details>
  <summary>03/84 - Crear tu primer sitio web</summary>
  <br/>
</details>

<details>
  <summary>04/84 - Sitios web con HTML</summary>
  <br/>
</details>

<details>
  <summary>05/84 - Estructura de árbol en HTML</summary>
  <br/>
</details>

<details>
  <summary>06/84 - Instalando tu primer editor de código</summary>
  <br/>
</details>

<details>
  <summary>07/84 - Cómo declarar variables y usar prompt</summary>
  <br/>
</details>

<details>
  <summary>08/84 - Algoritmo de piedra, paper o tijera</summary>
  <br/>
</details>

<details>
  <summary>09/84 - Algoritmo avanzado de piedra, papel o tijera</summary>
  <br/>
</details>

<details>
  <summary>10/84 - Aleatoriedad</summary>
  <br/>
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