# App de Hotel realizada en Gatsby.js

Esta aplicación es un sitio estático que obtiene datos a través de consultas query mediante graphql a la página DatoCMS, adonde están cargados tanto datos del hotel, como de sus habitaciones y funciones de SEO. Las páginas de cada habitación son creadas de modo dinámico a medida que se cargan más datos a través de DatoCMS

## Tecnologías utilizadas

Para este proyecto se utilizó la librería de Gatsby.js. Para las query de datos al CMS de DatoCMS se aplicó graphql. Los estilos fueron realizados mediante Styled components y CSS en Js mediante @emotion.

## Instrucciones para correr el proyecto

 - Clonar el repositorio.
 - En terminal/símbolo de sistema descargar los módulos de npm a través de npm install.
 - Para correr el proyecto en localhost, escribir en terminal: gatsby develop. Acceder al mismo a través de http://localhost:8000. También se puede acceder al playground de graphql en la dirección http://localhost:8000/___graphql.
