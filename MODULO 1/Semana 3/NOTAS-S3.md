# Notas Librerias y Frameworks

## Package

Colección de código que proporciona una funcionalidad específica

## Dependencias

Son paquetes que tu proyecto necesita para funcionar correctamente.

## Package Manager

Herramienta que te permite gestionar los paquetes o dependencias en tu proyecto.

## Responsive Design

Conjunto de practicas que permiten adaptar automaticamente en pantalla, el tamaño y diseño de un sitio web o app web, a distintos dispositivos.
Tecnicas utilizadas para realizar un diseño responsivo:

* Flexible grids
* Fluid images
* Media queries

**Gutter**  
Espacio entre columnas.

**Breakpoint**  
Punto en el que el contenido y diseño de un sitio web se adaptan para ofrecer una experiencia buena.

## Bootstrap

Bootstrap se describe a menudo como una forma de "construir sitios rápidos y con capacidad de respuesta" y es un "conjunto de herramientas front-end repleto de funciones, potente y extensible".

Algunas personas se refieren a él como un marco "front-end", y algunos tratan de ser más específicos refiriéndose a él como un "marco CSS" o una "biblioteca CSS". En pocas palabras, Bootstrap es una biblioteca de código CSS y JavaScript que puede combinar para construir rápidamente sitios web visualmente atractivos.

## Breakpoints disponibles en Bootstrap

**(Breakpoint / Class infix / Dimensiones)**  

```txt
Extra small /  / < 576px
Small / sm / >= 576px
Medium / md / >= 768px
Large / lg / >= 992px
Extra large / xl / >= 1200pxl
Extra extra large / xxl / >= 1400pxl
```

**Fluid**  
A menudo veras este termino modificador en las clases de Bootstrap, este modificador indica que el elemento es adaptable al tamaño del dispositivo.

**Class col-12**  
"col-12" indica que la columna debe ocupar todo el ancho disponible en una fila, es decir, 12 de las 12 columnas posibles en la cuadrícula de Bootstrap. Esto significa que la columna ocupará todo el ancho de la pantalla, independientemente del tamaño de la pantalla.

**Atributo role**  
El atributo **role** en HTML y Bootstrap se utiliza para indicar el propósito de un elemento para las tecnologías de asistencia, como los lectores de pantalla. Este atributo es parte de las especificaciones de ARIA (Accessible Rich Internet Applications) y ayuda a mejorar la accesibilidad de las aplicaciones web.

## Otros Frameworks y bibliotecas CSS

**Foundation**  
Foundation es un marco para la construcción de interfaces de usuario similar a Bootstrap. Lo utilizan muchas grandes empresas como Pixar, Polar y Sonos. Una característica destacada de Foundation es que puede utilizarse para dar estilo al contenido que se envía por correo electrónico.

```txt
https://get.foundation
```

**Pure.css**  
Pure.css es otra biblioteca para construir interfaces de usuario. Aunque no tiene tantas características como Bootstrap, está diseñada para tener un tamaño de archivo mínimo. Los archivos de menor tamaño mejoran los tiempos de carga de las páginas web, ya que hay menos datos que transferir desde el servidor web. Si su próximo proyecto se centra en un tiempo de carga mínimo, vale la pena considerar esta biblioteca.

```txt
https://purecss.io/
```

**Tailwind CSS**  
Tailwind CSS es un framework CSS que utiliza un enfoque basado en utilidades para sus reglas CSS. Esto significa que el marco proporciona muchas clases CSS con un único propósito. Por ejemplo, la clase CSS pt-6 establece la propiedad CSS padding-top en 6 píxeles. Esto significa que puede ser preciso a la hora de aplicar estilo a su HTML sin escribir CSS. La ventaja de esto es que es más flexible para personalizar el diseño de su página web utilizando el framework. Sin embargo, la desventaja es que si varios desarrolladores están trabajando en un proyecto, podría dar lugar a un diseño incoherente si el equipo no es estricto en sus reglas de diseño.

```txt
https://tailwindcss.com/
```

**UIKit**  
UIKit es un marco CSS ligero que incluye un pequeño conjunto de componentes con capacidad de respuesta. Su sencillo diseño permite a los desarrolladores personalizar fácilmente las reglas de estilo y los elementos visuales.

```txt
https://getuikit.com/
```

**MVP.css**  
MVP.css es una pequeña biblioteca CSS que aplica estilos automáticamente a los elementos HTML sin necesidad de aplicarles clases CSS. El objetivo de la biblioteca es permitir a un desarrollador crear rápidamente un prototipo de interfaz de usuario sin preocuparse por el diseño final, sin dejar de ser visualmente atractivo. MVP procede del término técnico Minimal Viable Product (producto mínimo viable), un producto con características suficientes para hacer una demostración a los clientes u otras partes interesadas del negocio.

```txt
https://andybrewer.github.io/mvp/
```

## Introduccion a React

**Static Content**  
Contenido fijo almacenado en un servidor web.

**Dynamic Content**  
Se genera al realizar una solicitud http, el contenido es distinto para cada usuario, el web server se conecta con el application server(back-end) para obtener contenido dinámico. En resumen, el servidor de aplicaciones genera el contenido dinámico que el servidor web devuelve al navegador del usuario.

**Application Server**  
Es un poco mas complejo que el Web server, mantiene la lógica de la aplicación, comunicacion con la base de datos y comprobaciones sobre permisos.

**Caching**  
Almacenamiento caché, les permite a los servidores web servir el contenido dinámico almacenado para evitar un problema de rendimiento en la carga. Cabe decir que este caché se actualiza cada cierto tiempo en base a los cambios en el servidor de aplicaciones.

**SPA**  
Single Page Application o Aplicacion de una sola pagina, consta de una sola pagina HTML que se envia del servidor al navegador, el contenido se actualiza a medida que el usuario interactua con esta, sin necesidad de descargar paginas web enteras.

**Enfoque Bundling SPA**  
En el enfoque de agrupacion, el servidor devuelve todo el HTML, CSS, JS y otros recursos.

**Enfoque Lazy Loading SPA**
En el enfoque de carga perezosa, el servidor devuelvo un minimo de HTML, CSS, JS y solo lo necesario. Los demas recursos se van descargando en base a las necesidades del usuario al interactuar con la pagina.

**Vistas en SPA**  
Las vistas son componentes reutilizables que contienen la lógica y el marcado HTML para una sección específica de la interfaz de usuario. En una SPA, en lugar de cargar una nueva página del servidor cada vez que el usuario navega a una nueva sección de la aplicación, la aplicación carga la vista correspondiente y la inserta en la página actual. Esto proporciona una experiencia de usuario más fluida y rápida, ya que no hay necesidad de esperar a que se cargue una nueva página completa.

## Introduccion a React

**¿Que es React?**
React esta disponible desde el 2013, es una Librería de código abierto que permite a los desarrolladores crear aplicaciones SPA, Aplicaciones moviles y escribir menos código para implementar funcionalidades en un navegador web, les ayuda a mantener el código a largo plazo y simplifica las pruebas, y también permite a los desarrolladores reutilizar componentes al construir sus aplicaciones. Evitas escribir codigo que ya existe, lo mejor de todo es que puedes utilizarla en conjunto con otras librerias.

**React Components**  
Puedes crear piezas de interfaz para construir tu aplicacion web, lo cual es excelente y reutilizable, además muy util para hacer pruebas aisladas. Toda aplicacion de React tiene al menos un **componente raiz**.

**React no es un framework MVC**  
React es una biblioteca para construir interfaces de usuario componibles. Fomenta la creación de componentes de interfaz de usuario reutilizables que presentan datos que cambian con el tiempo.

**Diferencias entre el DOM y el DOM Virtual**  
El DOM (Document Object Model) es una representación en forma de objeto de la estructura de un documento HTML. Cuando un navegador carga un documento HTML, interpreta el código HTML y crea un árbol DOM, donde cada elemento en el árbol es un objeto que puede ser manipulado para cambiar la estructura y el contenido del documento 1.  

Por otro lado, el DOM virtual es una tecnología utilizada en el framework de React. Es un árbol DOM ligero construido en memoria. Cuando el estado de un componente cambia, React recalcula el DOM virtual y lo compara con el DOM virtual previamente calculado para identificar los cambios, y luego actualiza solo las partes cambiadas en el DOM real 1.  

Las principales diferencias entre el DOM y el DOM virtual son:  

* El DOM es el modelo de objetos de documento real que existe en el navegador, mientras que el DOM virtual es un árbol DOM ligero construido en memoria.

* La manipulación directa del DOM puede ser lenta, mientras que el uso del DOM virtual puede mejorar el rendimiento porque el DOM virtual solo actualiza las partes cambiadas.
La manipulación del DOM requiere tener en cuenta la compatibilidad del navegador y otros problemas, mientras que el DOM virtual puede ser utilizado en diferentes plataformas.

* El DOM es una tecnología estándar, mientras que el DOM virtual es solo una implementación en el framework de React 1.

* En el proceso de renderizado, React utiliza el concepto de DOM virtual. Por ejemplo, cuando un elemento en el DOM real cambia, el DOM volverá a renderizar el elemento y todos sus hijos. Cuando se trata de construir aplicaciones web complejas con mucha interactividad y cambios de estado, este enfoque es lento e ineficiente. En cambio, en el proceso de renderizado, React utiliza el concepto de DOM virtual. Por lo tanto, podemos especificar en qué estado queremos que esté la interfaz de usuario, después de lo cual React lo hace realidad. Después de que el DOM virtual se actualiza, React lo compara con un snapshot del DOM virtual tomado justo antes de la actualización, determina qué elemento fue cambiado, y luego solo actualiza ese elemento en el DOM real. Este es uno de los métodos que emplea el DOM virtual para optimizar el rendimiento.

## Arquitectura Fiber de React

La Arquitectura Fiber permite a React renderizar incrementalmente la página web. Lo que esto significa es que en lugar de actualizar inmediatamente el DOM del navegador con todos los cambios virtuales del DOM, React puede distribuir la actualización a lo largo del tiempo.

Piense en ello como un sistema de prioridades. Los cambios de mayor prioridad, los elementos visibles para el usuario, se actualizan primero. Mientras que los cambios de menor prioridad, los elementos que no se muestran en ese momento, se actualizan más tarde.

## Alternativas a React

**Lodash**  
Como desarrollador, hay mucha lógica que escribirá comúnmente en las aplicaciones. Por ejemplo, puede que necesite ordenar una lista de elementos o redondear un número como `3.14` a `3`. Lodash proporciona lógica común como éstas como una biblioteca de utilidades para ahorrarle tiempo como desarrollador.

```txt
https://lodash.com/
```

**Luxon**  
Como desarrollador, trabajará a menudo con fechas y horas. Piense en ver una lista de pedidos y cuándo se realizaron, o en mostrar el calendario de un evento. Las fechas y las horas están en todas partes.

Luxon le ayuda a trabajar con fechas y horas proporcionando funciones para manipularlas y mostrarlas. Por ejemplo, piense en cómo se formatean las fechas en los distintos países. En Estados Unidos el formato es `Month Day Year` pero en Europa es `Day Month Year`. Esta es un área en la que Luxon puede ayudarle a mostrar la fecha en el formato local del usuario.

```txt
https://moment.github.io/luxon/#/
```

**Redux**  
Cuando construya una aplicación web, necesitará hacer un seguimiento de su estado. Piense en cuando compra en línea. La aplicación web realiza un seguimiento de los artículos que se encuentran actualmente en su cesta de la compra. Cuando retira un artículo del carrito, la aplicación necesita actualizar lo que aparece en la pantalla. Aquí es donde entra Redux. Le ayuda a gestionar el estado de su aplicación e incluso tiene funciones avanzadas como deshacer y rehacer.

```txt
https://redux.js.org/
```

**Axios**  
Como desarrollador, se comunicará frecuentemente con API a través de HTTP. La biblioteca Axios le ayuda a simplificar el envío de peticiones HTTP y el procesamiento de la respuesta. También proporciona funciones avanzadas que le permiten cancelar peticiones y modificar los datos recibidos del servidor web antes de que su aplicación los utilice.

```txt
https://axios-http.com/
```

**Jest**  
Como desarrollador profesional, es una buena práctica escribir pruebas automatizadas para su código. La biblioteca jest le ayuda a hacerlo y funciona con muchas bibliotecas y frameworks. También proporciona utilidades de generación de informes, como proporcionar información sobre qué parte de su código es comprobada por sus pruebas automatizadas.

```txt
https://jestjs.io/
```
