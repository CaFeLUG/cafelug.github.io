# Introducción
El propósito bajo el cual se pretende implementar esta plataforma es el de hallar un espacio que nos invite a formar parte de las actividades del CaFeLUG, y por decirlo así lograr suplir ciertas necesidades, como pueden ser:

* Disponer de más puntos para la difusión
* Visualizar y analizar mejor cierta información
* Implementar una herramienta colaborativa específica

Hay destacar que la filosofía del proyecto está en hacer pública la mayor cantidad de información posible, dependiendo en la menor de las medidas respecto a cualquier servicio privado que resultara preciso. Cabe aclarar entonces el desafío que implica utilizar herramientas aún en desarrollo, como lo pueden ser integraciones que todavía no son completamente oficiales y permanecen en fase de pruebas temporalmente de forma experimental.

Actualmente tal sitio tiene como principal dependencia [VueJS](https://vuejs.org/), lo cual resulta completamente discutible.

# Funcionalidad
La primer funcionalidad es, a prior, la de integrar salas de conversación en Gitter. Ya se dispone de una sala [Lobby](https://gitter.im/cafelug/Lobby/) que integra el chat de CaFeLUG en Telegram mediante [Sameroom](https://sameroom.io). Todavía falta integrar la cuenta oficial de Twitter en la sala [Noticias](https://gitter.im/cafelug/Noticias).

La segunda meta ó funcionalidad es la de lograr un sistema de gestión de contenidos ([CMS](https://es.wikipedia.org/wiki/Sistema_de_gesti%C3%B3n_de_contenidos)) aprovechando la API de [Github](https://developer.github.com/v3/) para extender nuestra cuenta de usuario con acciones propias de la plataforma (un ejemplo seria la posibilidad cargar una base de datos en este repositorio mediante tal sitio) de manera que seamos los usuarios quienes colaboremos suministrando información para luego en base a nuestra habilidad para gestionar datos (enlaces, posts, artículos de la wikipedia, etcétera) identificar tareas críticas y así buscar soluciones específicas o pendientes para la organización.

# Pendiente
- Integrar la cuenta oficial de Twitter en la sala 'Noticias' de Gitter.
- Migrar cualquier parte hecha con jQuery directamente a Javascript.
- Implementar OAuth de Github.
- La posibilidad de pushear desde la plataforma.
- La posibilidad de implementar algún patrón MVC en vez de VueJS.

# Referencias útiles/interesantes
[Github.js](https://github.com/github-tools/github)
[Github Platform Community](https://platform.github.community/)
[Prose](https://github.com/prose)
[HackMIT](https://github.com/HackMIT)

# Comentarios
Si alguien difiere acerca de la iniciativa y política del proyecto, como también si alguien precisa utilizar tal dominio, pueden comunicarse libremente conmigo @sietedosfede. Saludos!
