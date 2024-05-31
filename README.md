Añadir una aplicación Symfony7

    Crear un archivo conf con el nombre y el hostname del dominio local que vamos a utilizar
    Lanzar docker compose build para que el archivo de configuración se cargue en el contenedor del servidor nginx
    Lanzar docker compose up -d para iniciar los contenedores
    Acceder al contenedor symfony7_php y clonar en la carpeta /var/www/symfony el proyecto desde Github
    Acceder al archivo Hosts (en Windows o Ubuntu) para añadir el nombre del dominio (local) que vamos a utilizar:
        127.0.0.1 wiki_augc
    Crear un usuario y una base de datos específica para la app
    Crear un archivo .env.local con la configuración necesaria
