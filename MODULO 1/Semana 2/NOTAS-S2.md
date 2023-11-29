# NOTAS CSS

En CSS, el contenido dentro de los corchetes tiene el nombre de **"Bloque de declaracion"**.  

En CSS, el elemento a modificar tiene el termino de **"selector"**.

## Selectores

A la hora de dar estilo a una página web, existen muchos tipos de selectores disponibles que permiten a los desarrolladores ser tan amplios o específicos como necesiten a la hora de seleccionar elementos HTML a los que aplicar reglas CSS.

## Tipos de Selectores

**Selectores de elementos**  
El selector de elementos permite a los desarrolladores seleccionar elementos HTML basándose en su tipo de elemento.
La regla se aplicará a todos los elementos de la página web especificados con el selector.

```CSS
p { 
  color: blue; 
}
```

**Selectores ID**  
El selector ID utiliza el atributo id de un elemento HTML. Dado que el id es único dentro de una página web, permite al desarrollador seleccionar un elemento específico para estilizarlo. Los selectores ID llevan como prefijo el carácter "#".

```CSS
#latest { 
  background-color: purple; 
}
```

**Selectores de clase**  
Los elementos también pueden seleccionarse en función del atributo de clase que se les aplique. La regla CSS se ha aplicado a todos los elementos con el nombre de clase especificado. El selector de clase lleva como prefijo el carácter ".".

```CSS
.navigation { 
  margin: 2px;
}
```

**Elemento con selector de clase**  
Un método más específico para seleccionar elementos HTML consiste en seleccionar primero el elemento HTML y después la clase CSS o ID.

```CSS
p.introduction { 
  margin: 2px;
}
```

**Selectores descendientes**  
Los selectores descendientes son útiles si necesita seleccionar elementos HTML que están contenidos dentro de otro selector.

```CSS
/* Un Descendiente */
#blog h1 {
  color: blue;
}

/* Varios Descendientes */
#blog div h1 {
  color: blue;
}
```

**Selectores hijos**  
Los selectores hijos son más específicos que los selectores descendientes. Sólo seleccionan elementos que son descendientes inmediatos (hijos) de un selector (el padre).

```CSS
#blog > h1 {
  color: blue;
}
```

## Pseudoclases

Una palabra clave especial denominada "pseudoclase" permite a los desarrolladores seleccionar elementos en función de su estado.

```CSS
a:hover {
  color: orange;
}
```

## Texto y color en CSS

Cuando diseñe páginas web, trabajará mucho con colores y texto. Existen muchas formas diferentes de mostrar texto y otras tantas de definir los colores.

## Color

**Valor RGB**

RGB es un modelo de color que suma los colores rojo (R), verde (G) y azul (B) para crear colores. Se basa en cómo ve los colores el ojo humano.

Cada valor se define como un número entre0 y 255, que representa la intensidad de ese color. Se representa mediante la palabra clave `rgb`.

```CSS
p { 
  color: rgb(255, 0, 0); 
}
```

**Valor RGBA**

RGBA es una extensión de RGB que añade un canal alfa (A). El canal alfa representa la opacidad, o transparencia, del color.

Al igual que el RGB, se especifica en CSS mediante la palabra clave `rgba`.

```CSS
p { 
  color: rgba(255, 0, 0, 0.8);
}
```

**Valor HSL**

HSL es un modelo de color más reciente definido como Tono (H), Saturación (S) y Luminosidad (L). El objetivo del modelo es simplificar la visualización mental del color que representa el valor. En CSS, se utiliza la palabra clave `hsl` para definir un color con HSL.

```CSS
p { 
  color: hsl(0, 100%, 50%);
}
```

**Valor hexadecimal**

Los colores pueden especificarse utilizando un valor hexadecimal. Si no está familiarizado con el hexadecimal, piense en él como un conjunto de números diferente. Para fefinir un color hexadecimal se utiliza el prefijo `#`.

```CSS
p { 
  color: #000000;
}
```

**Nombres de colores predefinidos**

Los navegadores web modernos admiten 140 nombres de colores predefinidos. Algunos nombres de colores comunes disponibles.

```txt
black
silver
gray
white
maroon
red
purple
fuchsia
green
lime
olive
yellow
navy
blue
teal
aqua
```

## Texto

Con CSS hay muchas formas de cambiar cómo se muestra el texto. En esta sección, aprenderá las propiedades CSS de manipulación de texto más comunes.

**Color del texto**
La propiedad color establece el color del texto. El siguiente CSS establece el color del texto para todos los elementos de párrafo en rojo.

```CSS
p { 
  color: red;
}
```

**Fuente y tamaño del texto**

Existen muchas fuentes diferentes para mostrar texto en su ordenador. En términos sencillos, una fuente es una colección de caracteres de texto escritos en un estilo y tamaño específicos.

Para establecer el tipo de letra utilizado por el texto en CSS se utiliza la propiedad `font-family`.

```CSS
p { 
  font-family: "Courier New", monospace;
}
```

Dado que los ordenadores varían en cuanto a los tipos de letra que tienen instalados, se recomienda incluir varios tipos de letra al utilizar la propiedad `font-family`. Estas se especifican en un orden alternativo, lo que significa que si la primera fuente no está disponible, se buscará la segunda. Si la segunda fuente no está disponible, buscará la tercera y así sucesivamente. Si ninguna de las fuentes está disponible, utilizará la fuente predeterminada del navegador.

Para fijar el tamaño de la fuente, se utiliza la propiedad `font-size`.

```CSS
p { 
  font-family: "Courier New", monospace;
  font-size: 12px;
}
```

**Transformación del texto**

La transformación del texto es útil si desea garantizar la correcta capitalización del contenido del texto. En el ejemplo siguiente, la regla CSS cambiará todo el texto de los elementos de párrafo a mayúsculas utilizando la propiedad `text-transform`.

```CSS
p { 
  text-transform: uppercase;
}
```

Los valores más utilizados para la propiedad `text-transform` son: **uppercase**, **lowercase**, **capitalize** y **none**. El valor por defecto utilizado es **none**, lo que significa que el texto se muestra tal y como fue escrito en el documento HTML.

**Decoración del texto**

La propiedad `text-decoration` es útil para aplicar una decoración adicional al texto, como el **subrayado** y el **tachado*.

```CSS
p { 
  text-decoration: underline;
}
```

También es posible establecer el **color**, **grosor** y **estilo de la decoración**.

```CSS
p { 
  text-decoration: underline red solid 5px;
}
```

## Alineación de texto

Alinear texto dentro de un elemento HTML es muy sencillo. Para ello, se utiliza la propiedad CSS `text-align`.

```CSS
p { 
  text-align: left;
}

h1 { 
  text-align: right;
}

h2 { 
  text-align: center;
}

h3 { 
  text-align: justify; 
}
```

La alineación **justify** extiende el texto para que cada línea del texto tenga la misma anchura.
