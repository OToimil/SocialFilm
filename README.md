# SocialFilm

## Por qué fue creada esta aplicación web?

Este proyecto fue desarrollado para la entrega final de la asignatura Ingeniería de Servicios del grado en Ingeniería Informática de la USC. Consta de backend-frontend para una web dedicada a una red social para películas.

 [Imágenes del proyecto desplegado](#Imágenes)

## Backend

### Características

Se empleó **Java Spring Boot** para la creación de una **API REST** con acceso a una base de datos **MongoDB** y que permitiese realizar operaciones **CRUD**.

Además, se desarrolló una implementación de **autenticación y control de acceso** en los servicios empleando **tokens JWT**. A mayores, se consideró la inclusión de **links HATEOAS** para facilitar la navegación del cliente en la API.

Por último, cabe destacar que se hizo la **documentación** toda la API utilizando **Open API (Swagger)** de forma que sea mucho más fácil comprenderla.

### Ejecución

1. Clona este repositorio en tu sistema mediante ```git clone https://github.com/OToimil/SocialFilm```.
2. Emplea un IDE como *Intellij* y abre la carpeta backend.
3. Ejecuta el programa principal.


## Frontend

### Características

Se empleó **React** para la realización del frontend que consumiese el backend creado, para ello, nos ayudamos de **create-react-app** y de **React Router**.

Además, para dar estilo a las diferentes páginas, se optó por **Tailwind CSS**.

### Ejecución

1. Clona este repositorio en tu sistema mediante ```git clone https://github.com/OToimil/SocialFilm```.
2. Abre la carpeta frontend y ejecuta ```npm install``` de forma que se te instalen las dependencias.
3. Una vez realizado lo anterior, ejecutar ```npm start``` que hará el despliegue de la aplicación en *localhost*.


## Imágenes
### Backend
Documentación de la API:
<image src="https://raw.githubusercontent.com/Toimil/SocialFilm/master/readme-img/Documentacion-API.png" alt="Documentación de la API">
Ejemplo de un método HTTP de la API documentado:
<image src="https://raw.githubusercontent.com/Toimil/SocialFilm/master/readme-img/Documentacion-API-metodos.png" alt="Ejemplo método HTTP documentado API">
### Frontend
Inicio de sesión:
<image src="https://raw.githubusercontent.com/Toimil/SocialFilm/master/readme-img/Inicio-Sesion.png" alt="Inicio de sesión">
Registro:
<image src="https://raw.githubusercontent.com/Toimil/SocialFilm/master/readme-img/Registro.png" alt="Registro">
Pantalla principal:
<image src="https://raw.githubusercontent.com/Toimil/SocialFilm/master/readme-img/pagina-principal.png" alt="Pantalla principal">
Pantalla principal (más abajo):
<image src="https://raw.githubusercontent.com/Toimil/SocialFilm/master/readme-img/pagina-principal-peliculas.png" alt="Pantalla principal más abajo">
Opción de comentar dentro de las películas:
<image src="https://raw.githubusercontent.com/Toimil/SocialFilm/main/readme-img/comentario-pelicula.png" alt="Comentario peliculas">
Perfil del usuario:
<image src="https://raw.githubusercontent.com/Toimil/SocialFilm/master/readme-img/usuario.png" alt="Usuario">



## Hecho con

* [Java Spring Boot](https://spring.io/projects/spring-boot/)
* [React](https://es.react.dev/)
* [Tailwind CSS](https://tailwindcss.com/)
* [MongoDB](https://www.mongodb.com/es)

## Autor

* **Óscar Toimil** - [Toimil](https://github.com/Toimil)
