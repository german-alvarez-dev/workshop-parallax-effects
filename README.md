# Efectos Parallax con Javascript workshop

Materiales workshop Efectos Parallax con Javascript @ Ironhack Madrid (recurrente)

## Instalación

No requiere instalación.

## Ejecución

Ejecutar `index.html` en el navegador.

## Puntos esenciales
 - Los atributos `data-attributes` almacenan cualquier tipo de información en el DOM, pudiendo ser accedidos mediante [la propiedad `.dataset`](https://developer.mozilla.org/es/docs/Web/API/HTMLElement/dataset).
Parallax effects made with vanilla JS + VivusSVG plugin
 - El método `.getBoundingClientRect()` en su propiedad `.top` retorna la diferencia entre el punto superior de un objeto y el punto superior del *viewport*.
Parallax effects made with vanilla JS + VivusSVG plugin
 - La función `ìsInViewport()` retorna `true` cuando el elemento se encuentra dentro del *viewport*.
 - El plugin VivusSVG acepta un segundo argumento opcional: un *callback* que se ejecuta cuando el trazado finaliza [(plugin docs)](https://github.com/maxwellito/vivus#vivusjs)
 - Transiciones progresivas realizadas medante CSS (yay!):
   ````css
   .parallax {
      transition: transform 10s cubic-bezier(0,1,.5,1)
   }
   ````

## Recursos externos
 - VivusSVG plugin: https://github.com/maxwellito/vivus
 - Linea IO iconset (iconos SVG en el directorio _SVG_): https://github.com/linea-io/Linea-Iconset 
 - Generador online Bezier: https://cubic-bezier.com/
