DIU - Practica2, entregables

Malla receptora de información 
Sitemap & Task flow 
Labelling 
Wireframe & User flow 


1 - Feedback Capture Grid
-----

Tras analizar las experiencias de usuario y conocer las sugerencias de nuestras personas he realizado el siguiente Feedback Capture Grid:

![Feedback Capture Grid](https://github.com/Jovalga/DIU20/blob/master/P2/Feedback%20Capture%20Grid.jpg "Feedback Capture Grid")

La propuesta es mejorar lo que ya tiene *Badi* en una nueva app, ya que podemos usarlo como base gracias a lo minimalista que es esta plataforma.

Como añadido destacado se va a implementar una **agenda cultural**. Esta agenda se entiende como un sitio donde los usuarios registrados pueden publicar eventos, ya sean públicos o privados, a los que otros usuarios de la plataforma pueden registrar su asistencia. Dependiendo del evento se requerirá identificación en el sistema para registrar la asistencia al mismo.
Esta nueva función sirve de enlace a las dos funciones principales (Buscar y Publicar) de modo que estos eventos quedarán conectados a las habitaciones, asi, conocido el lugar de una habitación, se ofrecerán eventos cercanos tras la reserva de la misma.

Con todo esto vamos a respetar funciones como **Buscar y Publicar habitaciones**, pero vamos a mejorarlas. Para ello, en el caso de la *Publicación*, vamos a dar la posibilidad de que no solo se pueda publicar una habitación, sino que sea posible poner más de una para una misma publicación, y asociar distinas especificaciones y precios por separado, además de dar la posibilidad de alquilar el piso entero.

Con respecto a la *Búsqueda* vamos a separlo en dos tipos de búsqueda:
<ol>
  <li>Mapa: Veremos en tiempo real las ofertas publicadas sobre el mapa.</li>
  <li>Tradicional: Nos arrojará resultados tras rellenar un campo de texto con la ciudad donde buscar.</li>
 </ol>

Ambas búsquedas se pueden ajustar gracias a una serie de filtros, como precio, puntuación, tamaño, etc. Además se podrán guardar publicaciones en favoritos para que los usuarios puedan volver a encontrar habitaciones interesantes de búsquedas previas. Tras seleccionar una publicación se podrá enviar una consulta incluso sin estar registrado, pero en este caso se deberá aportar un email para recibir respuesta. Con usuarios registrados esta comunicación se puede dar con el sistema de mensajería interna de la aplicación.

Con respecto a la **ayuda**, se implementará un chat en directo con agentes disponibles las 24 horas para responder cualquier pregunta, un FAQ donde estarán las respuestas a las dudas más comunes y un asistente de voz para personas que lo necesiten.

Con todas estas nuevas características se conseguirá una aplicación más clara, eficiente y funcional que *Badi*.

2 - User Task Matrix
-----

![User Task Matrix](https://github.com/Jovalga/DIU20/blob/master/P2/User%20Task%20Matrix.jpg "User Task Matrix")

3 - Arquitectura de la Información (SiteMap y Labelling)
-----

### SiteMap:
El SiteMap de la nueva aplicación es el siguiente:

![SiteMap](https://github.com/Jovalga/DIU20/blob/master/P2/Sitemap.jpg "SiteMap")

Tenemos en un primer nivel las funciones principales, y bajo estas, las funciones dependientes de ellas. Vamos a destacar mucho *Encuentra tu habitación* y *Publica tu habitación* ya que considero que son las funciones principales de la app.

Cabe mencionar que *Encuentra tu habitación* no va a tener un sitio en sí, sino que cuando se rellene el formulario de búsqueda se redirigirá directamente a *Tradicional* (búsqueda por resultados) pudiendo ir a búsquedas por mapa desde ahí, y viceversa, pero la aplicación siempre recordará cuál fué el último tipo de búsqueda usado, de modo que cuando se vuelva a buscar algo, se usará el modo de búsqueda usado por última vez.

Decir también que *Información* es una página que tiene toda la información del sitio, junto con información de carácter legal. La idea es que el footer contenga los enlaces a todas las secciones de esta página, de modo que apartamos la información de lugares con funcionalidades muy importantes como es el navegador superior. De esta forma le damos al footer una función importante, y así aquellos usuarios que quieran tener mucha más información de la aplicación lo podrán hacer de forma sencilla, ya que toda esta información estará junta en un mismo lugar y no esparcida en distintas partes de la página.

### Labelling:

Para mejor comprensión del SiteMap aporto el Labelling:

![Labelling](https://github.com/Jovalga/DIU20/blob/master/P2/Labelling.jpg "Labelling")


4 - Wireframes
-----

A continuación dejo planteado el diseño de la aplicación.

![WF_Inicio](https://github.com/Jovalga/DIU20/blob/master/P2/Wireframe/Inicio.jpg "WF_Inicio")
***
![WF_Tradicional](https://github.com/Jovalga/DIU20/blob/master/P2/Wireframe/Tradicional.jpg "WF_Tradicional")
***
![WF_Mapa](https://github.com/Jovalga/DIU20/blob/master/P2/Wireframe/Mapa.jpg "WF_Mapa")
***
![WF_Habitación](https://github.com/Jovalga/DIU20/blob/master/P2/Wireframe/Habitaci%C3%B3n.jpg "WF_Habitación")
***
![WF_Pago_Online](https://github.com/Jovalga/DIU20/blob/master/P2/Wireframe/Pago%20Online.jpg "WF_Pago_Online")
***
![WF_Publica_tu_habitación](https://github.com/Jovalga/DIU20/blob/master/P2/Wireframe/Publica%20tu%20habitaci%C3%B3n.jpg "WF_Publica_tu_habitación")
***
