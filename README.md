# Compartir actividades educativas

**MP4UF3A1**

La necesidad de compartir ideas y pensamientos siempre ha estado tangible en la sociedad (p. ej. Facebook, Instagram, WhatsApp...); en el mundo educativo pasa lo mismo. Para ello se propone adaptar y evolucionar una plataforma web donde cualquier persona que se dedique al mundo de la enseñanza pueda compartir sus actividades.

Este desafío requiere que los desarrolladores que lo implementen siga estas restricciones:

-   Partir del código base del repositorio [app-actividades](https://github.com/dannylarrea/app-actividades)
-   Unificar los estilos en una única hoja CSS
-   Las actividades tienen que tener atributos relacionados a fecha de subida, descripción, autor y topic relacionado a la actividad, imagen y tiempo estimado de la actividad

## User Stories
<!-- Sin Login -->
-   [ ] Como usuario que no ha hecho login quiero poder ver una página `registro.html` para poder registrarme en la app
-   [ ] Como usuario que no ha hecho login quiero poder ver un botón con el texto **Nueva Cuenta** y el ícono **address-card** en la pantalla principal (en `index.html`) para que al clicar me redireccione a la página descrita anteriormente
-   [ ] Como usuario que no ha hecho login quiero poder ver una página `login.html` para poder hacer login y acceder a la app
-   [ ] Como usuario que no ha hecho login quiero poder clicar el botón **acceder** de la pantalla principal (en `index.html`) para me redireccione a la página descrita anteriormente
-   [ ] Como usuario que no ha hecho login quiero poder clicar el botón **Acceder** del menú de navegación (en `nosotros.html` y `actividades.html`) para que me redireccione a la página descrita anteriormente
-   [ ] Como usuario que no ha hecho login quiero poder clicar el botón que tiene el ícono **Upload** del menú de navegación (en `nosotros.html` y `actividades.html`) para me redireccione a la página descrita anteriormente
-   [ ] Como usuario que no ha hecho login quiero poder clicar el botón **corazón** de debajo de las actividades (en `actividades.html`) para que me redireccione a la página descrita anteriormente

<!-- Login -->
-   [ ] Como usuario que ha hecho login quiero poder ver una página `subiractividad.html` y que mediante un formulario pueda añadir una actividad para que se publique en la app
-   [ ] Como usuario que ha hecho login quiero poder clicar el botón que tiene el ícono **Upload** del menú de navegación (en `nosotros.html` y `actividades.html`) para me redireccione a la página descrita anteriormente
-   [ ] Como usuario que ha hecho login quiero poder ver una página `misactividades.html` para poder ver todas las actividades que he publicado en la app
-   [ ] Como usuario que ha hecho login quiero poder ver un ítem con el texto **Mis actividades** en el menú de navegación (en `nosotros.html` y `actividades.html`) para me redireccione a la página descrita anteriormente
-   [ ] Como usuario que ha hecho login quiero poder ver un botón de **logout** en lugar del botón **Acceder** del menú de navegación de para salir de la app

-   [ ] Como usuario quiero poder clicar en el botón matemáticas (apartado Topics de `nosotros.html`) para ver las actividades relacionadas a la asignatura de matemáticas
-   [ ] Como usuario quiero poder clicar en el botón informática (apartado Topics de `nosotros.html`) para ver las actividades relacionadas a la asignatura de informática
-   [ ] Como usuario quiero poder clicar en el botón economía (apartado Topics de `nosotros.html`) para ver las actividades relacionadas a la asignatura de economía
-   [ ] Como usuario quiero poder ver una página `actividad.html` para poder consultar los detalles de una actividad en concreta
-   [ ] Como usuario quiero poder clicar encima de una actividad (en `nosotros.html`, `actividades.html`, `topics.html` y `misactividades.html`) para me redireccione a la página descrita anteriormente

-   [ ] Como usuario quiero poder ver 4 imágenes relacionadas a las 4 últimas actividades que se han subido recientemente a la app y que al clicar sobre una de ellas me redireccione a la página `actividad.html`

## Bonus features

-   [ ] Como usuario que ha hecho login quiero poder tener la opción de publicar una actividad **de manera privada** para que los demás usuarios de la app no puedan verla
-   [ ] Como usuario quiero poder clicar el botón **enlace** de debajo de las actividades (en `actividades.html`) para copiar la url de la página `actividad.html` y poder consultar los detalles de la actividad seleccionada

## Useful links and resources

-   [Font Awesome](https://fontawesome.com/)
-   [Bootstrap](https://getbootstrap.com/)

## Example projects

-   [Live de la app](https://dannylarrea.github.io/app-actividades/index.html)