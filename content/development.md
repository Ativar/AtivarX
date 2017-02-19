Development
=========================

Como desarrollador, front-end o back-end algunas recomendaciones que pueden existir para la implementación en un proyecto es que te involucres desde la planeacion, asi pues, puedes estar seguro que todo lo que se describa puede ser llevado a cabo correctamente (Las capas de UI/UX, escalavilidad, entre otras cosas).

Tratá de que el código sea claro y modular. Como regla general no te repitas.

Usa Pull Requests para hacer una revisión de código antes de dar por finalizada una feature.

En desktop, como política general soportamos las dos últimas versiones estables de los browsers principales (Chrome, Firefox, IE, Safari). Asimismo, todos nuestros sites son responsive con soporte mobile por defecto.

En mobile, dada la mayor variación y disponibilidad de hardware, tomamos como base los dispositivos de referencia de iOS y Android, que son los iPhone y Nexus disponibles comercialmente durante los últimos 12 meses, incluyendo sus sistemas operativos. Esto significa actualmente minimo iPhone 5/6/6Plus (iOS 7 y 8) y Nexus 5/6 (Android 4.4 y 5).

Siempre trabaja con un repositorio y escribe cada commit en ingles, no importa si usas Google translate

Usá nuestro sistema de deployment automático siempre que puedas, que te va a permitir mostrar en qué estas trabajando en un branch específico, sin necesidad de SSH o FTP.

Usa [Git Flow](https://www.atlassian.com/git/tutorials/comparing-workflows)
Es una metodología que nos permite trabajar con mayor comodidad en un repositorio. Dale una leída al documento, pero lo que tenés que saber es lo siguiente: Usá siempre branches para nuevas features y fixes (feature/redesign), los cuales se mergean a dev para testearlos y recién una vez testeados los mandamos a master.

Utiliza comments en el codigo para cosas especificas, hacks para solucionar issues raros

Nuestras guidelines son muy simples:
- Usamos UTF-8 para todo.
- tabulado con 2 espacios.
- Trabajamos en inglés a menos que haya una excepción para el proyecto.

De lo mas importante de todo, es que todos pueden poder proponer la tecnologia en la que se necesite trabajar siempre y cuando se pueda justificar su utilidad ademas de un Code Style propuesto

##Resources:

### Code Styles

####[Standard / Javascript](https://github.com/feross/standard)

### Server Frameworks

####[Express / Node](http://expressjs.com/)

####[Feathers / Node](http://feathersjs.com/)

####[Meteor / Node](https://www.meteor.com/)

####[Django / Python](https://www.djangoproject.com/)

####[Flask / Python](http://flask.pocoo.org/)

####[Rails / Ruby](http://rubyonrails.org/)

####[Spring Boot / Java](https://projects.spring.io/spring-boot/)

####[.NET Core / C#](https://www.microsoft.com/net/core)

####[Laravel / PHP](https://laravel.com/)

### Front End Frameworks

####[React](https://facebook.github.io/react/)

####[Redux](http://redux.js.org/)

####[Ember](http://emberjs.com/)

####[Angular](https://angular.io/)

####[Vue](https://vuejs.org/)

### Movile Frameworks

####[React Native](https://facebook.github.io/react-native/)

####[Native Base](http://nativebase.io/)

### Databases

####[Mongo](https://www.mongodb.com/)

####[Postgre](https://www.postgresql.org/)

####[Cassandra](http://cassandra.apache.org/)

####[Couch](http://couchdb.apache.org/)

## Servers and DevOps

####[NGINX](https://www.nginx.com/resources/wiki/)

####[Docker](https://www.docker.com/)

####[AWS](https://aws.amazon.com/)

####[Digital Ocean](https://www.digitalocean.com/)

####[Dokku](https://github.com/dokku/dokku)

---
[Home](../README.md) / [Communication](communication.md)