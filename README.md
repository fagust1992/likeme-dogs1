# LikeMe-Dogs
![Likeme-Dogs](https://github.com/fagust1992/Likeme-Dogs/blob/master/public/img/likeme.jpg?raw=true "Likeme-Dogs")
LikeMe-Dogs es una de aplicación web full-stack desarrollado utilizando Node.js. Este proyecto permite a los usuarios agregar y explorar información sobre diferentes razas de perros.

## Características

- Agregar perros: Los usuarios pueden completar un formulario para agregar imágenes, descripciones y nombres de razas de perros.
- Explorar perros: Los usuarios pueden explorar la información y las imágenes de las diferentes razas de perros agregadas 
- Likes: Los usuarios pueden agregar likes a sus perros favoritos.

## Tecnologías utilizadas

- Backend: Node.js, Express
- Base de datos: SQL
- Frontend: JavaScript, HTML, CSS

## Contribuciones

En este proyecto, me enfoqué en el desarrollo del backend utilizando Node.js y Express. Implementé las rutas y lógica necesarias para permitir a los usuarios agregar y explorar información sobre las razas de perros. Además el  frontend lo diseñe pensando garantizar una integración fluida entre el frontend y el backend.

Mi objetivo principal fue asegurar el correcto funcionamiento del backend y brindar una experiencia de usuario mejorada mediante la posibilidad de agregar likes a los perros favoritos.

## Manual de instalacion 


Sigue los pasos a continuación para instalar y ejecutar el proyecto en tu entorno local:

1. Clona el repositorio en tu máquina local:
git clone https://github.com/fagust1992/Likeme-Dogs.git

2. Navega hasta el directorio del proyecto:
 cd Likeme-Dogs.
 
 
 ## crea base de datos

Antes de ejecutar la aplicación, es necesario crear la base de datos utilizando el archivo SQL proporcionado

Ejecuta el contenido del archivo like-base-datos.sql en tu gestor de base de datos. Esto creará las tablas y configuraciones necesarias en la base de datos recién creada.

   ## Configuración de la base de datos

Antes de ejecutar la aplicación, asegúrate de configurar correctamente las credenciales de la base de datos en el archivo de código.

1. Abre el archivo `index.js` en tu editor de código.
2. Busca la sección que contiene la configuración de la base de datos.
3. Reemplaza los valores de `host`, `user`, `password` y `database` con tus propias credenciales de base de datos.

```javascript
const pool = new Pool({
  host: "localhost",
  user: "tu_usuario",
  password: "tu_contraseña",
  database: "likeme",
  allowExitOnIdle: true,
});
   

