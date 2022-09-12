# PostasAmericanas
## Tabla de Contenidos
1. [Información General](#Información-General)
2. [Tecnologías](#Tecnologías)
3. [Instalación](#Instalación)
4. [Información Personal](#Acerca-de-mi)

### Información General
***
Este sitio se encuentra en su primera etapa de desarrollo.
Tiene por objeto permitir que toda la comunidad de nadadores tengan información actualizada de todos los Eventos de Postas Americanas.
Las próximas versiones incluirán backend para darle mayor funcionalidad al sitio.
Posteriormente se pretende integrarlo con otras tecnologías para poder registrar en tiempo real, el registro de segundos de cada nadador, y obtener un resultado de cada evento on-line.

### Logo
![Image text](https://postasamericanascba.000webhostapp.com/img/IconoPostasBlack.jpeg)
## Tecnologías
***
Lista de tecnologías utilizadas en este proyecto:
* [Boostrap](https://getbootstrap.com/docs/4.0/getting-started/introduction/): Versión 4 
* [NodeJs](https://nodejs.org/en/download/): Versión 16.17
* [npm](https://www.npmjs.com/package/npm): Versión 8.19.1
* [Font Awesome](https://fontawesome.com/): Versión 6.2

### Instalación
:keyboard:**Desarrolladores:**
Todos aquellos que quieran continuar con el proyecto se utiliza HTML, SASS y Boostrap.
A continuación les dejo los pasos para poder compilar con node-js
* Descargar e instalar NodeJs y npm
* Ir a la carpeta del proyecto y ejecutar
npm init
* ejecutar npm install node-sass nodemon
* Crear carpeta y archivo SCSS
* Copiar contenido de style.css del proyecto en style.scss
* Configurar el archivo package.json agregando las siguientes lineas en la sección scripts:
    "build-css": "node-sass --include-path scss scss/style.scss css/style.css",
    "watch-css": "nodemon -e scss -x \"npm run build-css\""
* Dar formato SASS al archivo style.scss
* Ejecutar: npm run watch-css


### Acerca de mi
:star2:*Sobre mi:*
   - Soy alguien con una personalidad creativa.
   - Tengo siempre una visión general del proyecto.
   - Disfruto aprender constantemente cosas nuevas.
   - Suelo tener la iniciativa en el trabajo en equipo.
