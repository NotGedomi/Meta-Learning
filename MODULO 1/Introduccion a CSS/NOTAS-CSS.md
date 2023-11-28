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

/* Varios Descendiente */
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

## Psudoclases

Una palabra clave especial denominada "pseudoclase" permite a los desarrolladores seleccionar elementos en función de su estado.

```CSS
a:hover {
  color: orange;
}
```
