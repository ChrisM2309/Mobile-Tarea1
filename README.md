# Primer Proyecto en Flutter

**Autor:** Christopher Marroquín  
**Carnet:** 20245332

## Descripción

Este proyecto corresponde al **primer proyecto desarrollado en Flutter**, realizado como parte del proceso de aprendizaje y familiarización con el framework y el lenguaje de programación Dart.

## Bitácora de errores

Durante el desarrollo surgieron algunos inconvenientes, principalmente relacionados con la estructura y el uso de los componentes de Flutter.

Al ser mi primera vez utilizando la herramienta, desconocía que el `Scaffold` requiere utilizar ciertas propiedades específicas, como `floatingActionButton`.

Mi primer enfoque fue crear un segundo botón de acción y agregar en él la lógica necesaria para realizar el **reset**. Sin embargo, esta implementación generó errores y no funcionó como esperaba.

Posteriormente, al revisar la documentación disponible en Moodle, encontré el componente `Row` e intenté utilizarlo directamente dentro del `Scaffold` para colocar ambos botones. Esta solución tampoco funcionó inicialmente.

Después de revisar con mayor detenimiento la estructura de Flutter, comprendí que el `Row` debía colocarse **dentro del `floatingActionButton`** y que, a su vez, dentro del `Row` podían agregarse ambos botones.

Con este cambio fue posible organizar correctamente los botones y solucionar el problema.

Este proceso me permitió comprender mejor cómo funcionan los widgets anidados en Flutter y la importancia de respetar la estructura esperada por cada componente.

## Uso de IA

Durante el desarrollo del proyecto se utilizaron las **autocorrecciones y sugerencias de GitHub Copilot** como apoyo.

Sin embargo, las sugerencias no resultaron particularmente efectivas para resolver los problemas específicos que se presentaron durante el desarrollo. Su principal utilidad fue servir como referencia para comprender y recordar la **sintaxis de Dart**.

Tambien se uso IA para mejorar la redaccion y formato markdown de esta bitacora. 