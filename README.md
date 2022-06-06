# ¿Qué es Organitor?
Organitor es el proyecto de fin de Curso de [Alba Gimeno](https://github.com/albagimeno) e [Ismael Castellanos](https://github.com/ismaelct). Se trata de un proyecto de Aplicacion Web desplegada a traves de Docker y con el entorno de ejecución Node.js. 

# ¿Cuál es la finalidad del proyecto?
La base del proyecto es crear tanto las herramientas para un facil despliegue y la base de la aplicación web.

Para el despliegue, tendremos _docker file_ y el _docker-compose_ para desplegar la aplicación. Haremos uso de Portainer para desplegar esa pila de docker para que sea más amigable al usuario. 

Para la web, haremos uso de _Node.js_ usando _Expressjs_ como framework principal y con distintos modulos para todo el apartado del _back-end_, junto con _Bootstrap_ para el css y _JavaScript_ para el _front-end_.

Para el almacenamiento de datos utilizaremos _MongoDB_ dentro de la pila de _docker-compose_.
s)
	
## Tecnologías
El proyecto esta creado con:
* [Docker](https://docs.docker.com/) 
    * [Dockerfile](https://docs.docker.com/engine/reference/builder/)
* [Docker-Compose](https://docs.docker.com/compose/) versión: 2, 3 & 3.9
* [Httpd-Apache](https://httpd.apache.org/docs/2.4/)
* [MongoDB](https://www.mongodb.com/docs/) versión: 5.0.8
* [Mongo-Express Container](https://hub.docker.com/_/mongo-express) versión: 1.0.0-alpha.4
* [Portainer](https://docs.portainer.io/) versión: 2.13.1
* [Node.js](https://nodejs.org/es/docs/) versión: v18.2.0
    * [Bcrypt.js](https://www.npmjs.com/package/bcryptjs) versión: 2.4.3
    * [Connect-flash](https://www.npmjs.com/package/connect-flash) versión: 0.1.1
    * [Cors](https://www.npmjs.com/package/cors) versión: 2.8.5
    * [dotenv](https://www.npmjs.com/package/dotenv) versión: 16.0.0
    * [Express.js](https://www.npmjs.com/package/express) versión: 4.18.1
    * [Express-handlebars](https://www.npmjs.com/package/express-handlebars) versión: 6.0.5
    * [Express-session](https://www.npmjs.com/package/express-session) versión: 1.17.2
    * [handlebars](https://www.npmjs.com/package/handlebars) versión: 4.7.7
        * [@handlebars/allow-prototype-access](https://www.npmjs.com/package/@handlebars/allow-prototype-access) versión: 1.0.5
    * [hbs](https://www.npmjs.com/package/hbs) versión: 4.2.0
    * [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) versión: 8.5.1
    * [method-override](https://www.npmjs.com/package/method-override) versión: 3.0.0
    * [mongoose](https://www.npmjs.com/package/mongoose) versión: 6.3.3
    * [morgan](https://www.npmjs.com/package/morgan) versión: 1.10.0
    * [nodemailer](https://www.npmjs.com/package/nodemailer) versión: 6.7.5
    * [nodemon](https://www.npmjs.com/package/nodemon) versión: 2.0.16
    * [npm-check-updates](https://www.npmjs.com/package/npm-check-updates) versión: 12.5.11
    * [passport](https://www.npmjs.com/package/passport) versión: 0.5.2
    * [passport-local](https://www.npmjs.com/package/passport-local) versión: 1.0.0

  
 
