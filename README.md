# Evolucionar un sistema de gestión de información

La necesidad de compartir ideas y pensamientos siempre ha estado tangible en la sociedad (p. ej. Facebook, Instagram, WhatsApp...); en el mundo educativo pasa lo mismo. Para ello se propone adaptar y evolucionar una plataforma web donde cualquier persona que se dedique al mundo de la enseñanza pueda compartir sus actividades.

Este desafío requiere que los desarrolladores que lo implementen siga estas restricciones:

- Partir del código base del repositorio [app-actividades](https://github.com/dannylarrea/app-actividades)
- Unificar los estilos en una única hoja CSS
- Las actividades tienen que tener atributos relacionados a fecha de subida, descripción, imagen, tiempo estimado, autor y topic asociados a la actividad

## User Stories

<!-- Sin Login -->

- [ ] Como usuario que no ha hecho login quiero poder ver una página `registro.html` para poder registrarme en la app
- [ ] Como usuario que no ha hecho login quiero poder ver un botón con el texto **Nueva Cuenta** y el ícono **address-card** en la pantalla principal (en `index.html`) para que al clicar me redireccione a la página descrita anteriormente
- [ ] Como usuario que no ha hecho login quiero poder ver una página `login.html` para poder hacer login y acceder a la app
- [ ] Como usuario que no ha hecho login quiero poder clicar el botón **acceder** de la pantalla principal (en `index.html`) para me redireccione a la página descrita anteriormente
- [ ] Como usuario que no ha hecho login quiero poder clicar el botón **Acceder** del menú de navegación (en `nosotros.html` y `actividades.html`) para que me redireccione a la página descrita anteriormente
- [ ] Como usuario que no ha hecho login quiero poder clicar el botón que tiene el ícono **Upload** del menú de navegación (en `nosotros.html` y `actividades.html`) para me redireccione a la página descrita anteriormente
- [ ] Como usuario que no ha hecho login quiero poder clicar el botón **corazón** de debajo de las actividades (en `actividades.html`) para que me redireccione a la página descrita anteriormente

<!-- Login -->

- [ ] Como usuario que ha hecho login quiero poder ver una página `subir.actividad.html` y que mediante un formulario pueda añadir una actividad para que se publique en la app
- [ ] Como usuario que ha hecho login quiero poder clicar el botón que tiene el ícono **Upload** del menú de navegación (en `nosotros.html` y `actividades.html`) para me redireccione a la página descrita anteriormente
- [ ] Como usuario que ha hecho login quiero poder ver una página `mis.actividades.html` para poder ver todas las actividades que he publicado en la app
- [ ] Como usuario que ha hecho login quiero poder ver un ítem con el texto **Mis actividades** en el menú de navegación (en `nosotros.html` y `actividades.html`) para me redireccione a la página descrita anteriormente
- [ ] Como usuario que ha hecho login quiero poder ver un botón de **logout** en lugar del botón **Acceder** del menú de navegación de para salir de la app
- [ ] Como usuario quiero poder ver 4 imágenes relacionadas a las 4 últimas actividades que se han subido recientemente a la app
- [ ] Como usuario quiero poder clicar encima de cualquier imagen de actividad y poder acceder a una página `actividad.html` para consultar sus detalles

<!-- Desarrollador -->

- [ ] Como futuro desarrollador quiero poder ver el código del la app comentado para poder entender como funciona el software desarrollado

## Bonus features

<!-- Usuario con/sin login -->

- [ ] Como usuario que ha hecho login quiero poder tener la opción de publicar una actividad de **manera pública** o de **manera privada** (para que los demás usuarios de la app no puedan acceder a ella)
- [ ] Como usuario quiero poder clicar el botón **enlace** de debajo de las actividades (en `actividades.html`) para copiar la url de la página (`actividad.html`) y poder consultar los detalles de la actividad seleccionada
- [ ] Como usuario quiero quiero poder ver una página `topics.actividades.html` para poder ver agrupadas las actividades por el **topic** en concreto
- [ ] Como usuario quiero poder clicar en el botón matemáticas (apartado Topics de `nosotros.html`) para me redireccione a la página descrita anteriormente y ver las actividades relacionadas a matemáticas
- [ ] Como usuario quiero poder clicar en el botón informática (apartado Topics de `nosotros.html`) para me redireccione a la página descrita anteriormente y ver las actividades relacionadas a informática

## Useful links and resources

- [Font Awesome](https://fontawesome.com/)
- [Bootstrap](https://getbootstrap.com/)
- [Actividades Matemáticas 1](http://www.xtec.cat//crp-anoia/webcons/sumari.htm)
- [Actividades Matemáticas 2](https://www.polyhedra.net/es/)
- [Actividades Matemáticas 3](http://recursostic.educacion.es/descartes/web/materiales_didacticos/Combinatoria/indice.htm)

## Example projects

- [Live de la app](https://dannylarrea.github.io/app-actividades/index.html)
