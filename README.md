/// ANOTACIONES SOBRE PROYECTO ///

\*\*\* Cada sección del Home esta indicada con un comentario que señala el nombre del componente,
ej.: <!--------- como comprar ------------> refiere a la sección que identifica los 4 pasos generales para realizar una compra a través de BluEat.

\*\*\* La arquitectura del sitio esta basada en HTML5 y SASS. Se eligió este framework para la hoja de estilos por sus beneficios de anidamiento y permite ordenar mejor el código referido a estilos de cada componente, por ello en assets/scss/components se puede encontrar cada componente con su hoja de estilos propia. Si se desea modificar por ejemplo el Footer, se busca el componente identificado con el mismo nombre y se puede acceder a los estilos del mismo.

\*\*\* Respecto a la responsividad, la misma puede modificarse a través de la hoja de estilos assets/scss/mediaQuery/\_query.scss
La resolución general en el cuál se basa este código es 1920, ideal para large screens, en query's se encuentran los estilos adaptativos para que cada componente se vea correctamente en resolución 1280 (ideal para small screens)

A continuación se adjuntan dos muestras sobre cómo se visualiza la página desarrollada:

RESOLUCIÓN 1920
![muestra-1920-blueat](https://user-images.githubusercontent.com/79757893/131261354-c738ba00-6b71-4ce0-ae6f-d731fb8463b5.gif)

RESOLUCIÓN 1280
![Uploading muestra-1289.blueat.gif…]()
