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
