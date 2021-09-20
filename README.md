# Flexbox-CSS

Modulo N°1 para maquetación con CSS

- Conceptos básicos.

- Propiedades:

  1. Del contenedor padre.
  2. De los elementos hijos.

- Flexbox en la práctica.
  1. Maquetación y responsive design.
  2. Ejemplos prácticos.
  3. Flexbox y Bootstrap.

# Notas:

1. Es el primer módulo de maquetación que nos ofrece CSS por lo tanto es importante conocerlo ya que nos permite hacer diseños y propuestas interesantes.
2. Al entender sus propiedades podemos usar y entender de forma más fácil otros complementos para usar CSS como son los frameworks de CSS (Bootstrap, Foundation, Materialize, Bulma, etc.). Entender las bases de Flexbox nos ayudara a sacar más provecho los frameworks de CSS.

# Entendiendo la terminología básica

Referencia: https://css-tricks.com/wp-content/uploads/2018/11/00-basic-terminology.svg

1. Es un sistema unidimensional donde podemos tener filas o columnas, pero no ambas cosas.
2. Tenemos en primer lugar el (flex container) que es el contenedor padre y dentro de este vamos a tener a los (flex item) que son los hijos.
3. Contamos con 2 ejes, el principal llamado (main axis) y el transversal llamado (cross axis). Tener en cuenta que (main axis) no es necesariamente horizontal, depende de la propiedad (flex-direction) para determinar su posición.
4. Los elementos flexibles se van a colocar dentro del (flex container) comenzando desde (main start) hasta (main end).
5. Main Size: El ancho y el alto de un (flex item) cualquiera que esté en (main size) es el tamaño principal del elemento. La propiedad de (main size) del (flex item) es la propiedad ancho o alto, cualquiera que esté en la dimensión principal.
6. Del (cross axis) al (main axis) se denomina eje transversal y su dirección depende de (main axis).
7. Las líneas flexibles se llenan con artículos y se colocan en el contenedor comenzando en el lado de (cross start) del (flex container) y yendo hacia el lado extremo (cross ens).
8. Cross Size: El ancho y el alto de un (flex item) cualquiera que esté en (cross size) es el tamaño principal del elemento. La propiedad de (cross size) del (flex item) es la propiedad ancho o alto, cualquiera que esté en la dimensión cruzada.

# Nota Extra: Incrustando imagenes al README.md

Método 1:
![Alt text](/img/dev.svg?raw=true "Optional title")

Método 2:

  <p align="center">
    <img src="/img/dev.svg" width="100" title="Hover text" alt="Optional text">
  </p>

# Flexbox propiedades para el "Padre"

1. display
Esto define un contenedor flexible; en línea o en bloque según el valor dado. Permite un contexto flexible para todos sus hijos directos.
<p align="center">
    <img src="/img/01-container.svg" width="527" height="210" title="Flexbox Propiedades" alt="Flexbox Propiedades">
</p>

2. flex-direction
Esto establece el eje principal, definiendo así la dirección en que se colocan los elementos flexibles en el contenedor flexible. Flexbox es (aparte de la envoltura opcional) un concepto de diseño de una sola dirección. Piense en los elementos flexibles como distribuidos principalmente en filas horizontales o columnas verticales.
<p align="center">
    <img src="/img/02-flex-direction.svg" width="505" height="232" title="Flexbox Propiedades" alt="Flexbox Propiedades">
</p>
