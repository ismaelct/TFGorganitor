# Trabajo Final de Grado: Organitor.es
Puedes acceder en: [Organitor.es](https://organitor.es)
También existe portainer.organitor.es & db.organitor.es, no accesibles al público. Donde una se trata del gestor de contenedores del servidor y la otra trata la base de datos de la web.
# ¿Qué es Organitor?
Organitor es el proyecto de fin de Curso de [Alba Gimeno](https://github.com/albagimeno) e [Ismael Castellanos](https://github.com/ismaelct). Se trata de un proyecto de Aplicacion Web desplegada a traves de Docker y con el entorno de ejecución Node.js.

# ¿Cuál es la finalidad del proyecto?
La base del proyecto es crear tanto las herramientas para un facil despliegue y la base de la aplicación web.

Para el iniciar el proyecto, usaremos _Portainer_[^1] un gestor de contenedores de _Docker_[^2]. Lo usaremos para desplegar los _stacks_, que es como denomina _Portainer_ a _Docker-Compose_[^3], también haremos uso de _Dockerfile_[^4] desde el propio gestor de contenedores.

Para el apartado web, haremos uso de _Node.js_[^5] usando _Express.js_[^6] como framework principal y con distintos modulos para todo el apartado del _back-end_, junto con _Bootstrap_[^7] para el css y _JavaScript_ para el _front-end_.

Para el almacenamiento de datos utilizaremos _MongoDB_[^8] dentro del _stack_ de servicios que desplegaremos.
s)

También utilizamos _Mongo-Express_[^9] que se trata de un administrador web para las bases de datos de MonogoDB.
	
## Tecnologías
El proyecto esta creado con:
* [^7]: [Boostrap](https://getbootstrap.com/docs/5.1/getting-started/introduction/) v5.1.3
* ['Cloudflare DDNS'](https://github.com/oznu/docker-cloudflare-ddns) Commit: _a96b637 el día 3 de Dic 2021_
* [^2]: [Docker](https://docs.docker.com/) 
    * [^4]: [Dockerfile](https://docs.docker.com/engine/reference/builder/)
* [^3]: [Docker-Compose](https://docs.docker.com/compose/) v2, 3 & 3.9
* [Httpd-Apache](https://httpd.apache.org/docs/2.4/)
* [^8] [MongoDB](https://www.mongodb.com/docs/) v5.0.8
* [^9]: [Mongo-Express](https://github.com/mongo-express/mongo-express) v1.0.0-alpha.4
* [^1]: [Portainer](https://docs.portainer.io/) v2.13.1
* [^5]: [Node.js](https://nodejs.org/es/docs/) v18.2.0
    * [Bcrypt.js](https://www.npmjs.com/package/bcryptjs) v2.4.3
    * [Connect-flash](https://www.npmjs.com/package/connect-flash) v0.1.1
    * [Cors](https://www.npmjs.com/package/cors) v2.8.5
    * [dotenv](https://www.npmjs.com/package/dotenv) v16.0.0
    * [^6]: [Express.js](https://www.npmjs.com/package/express) v4.18.1
    * [Express-handlebars](https://www.npmjs.com/package/express-handlebars) v6.0.5
    * [Express-session](https://www.npmjs.com/package/express-session) v1.17.2
    * [handlebars](https://www.npmjs.com/package/handlebars) v4.7.7
        * [@handlebars/allow-prototype-access](https://www.npmjs.com/package/@handlebars/allow-prototype-access) v1.0.5
    * [hbs](https://www.npmjs.com/package/hbs) v4.2.0
    * [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) v8.5.1
    * [method-override](https://www.npmjs.com/package/method-override) v3.0.0
    * [mongoose](https://www.npmjs.com/package/mongoose) v6.3.3
    * [morgan](https://www.npmjs.com/package/morgan) v1.10.0
    * [nodemailer](https://www.npmjs.com/package/nodemailer) v6.7.5
    * [nodemon](https://www.npmjs.com/package/nodemon) v2.0.16
    * [npm-check-updates](https://www.npmjs.com/package/npm-check-updates) v12.5.11
    * [passport](https://www.npmjs.com/package/passport) v0.5.2
    * [passport-local](https://www.npmjs.com/package/passport-local) v1.0.0

  
 
