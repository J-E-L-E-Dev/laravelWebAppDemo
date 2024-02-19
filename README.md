# EJEMPLO DE LARAVEL WEB APP

## Clonar

    cd /path
    
    git clone git@github.com:ruta.git path.app.lan
            
## Ingresar en carpeta
        
    cd miweb.lan
        
## Para instalar

    composer install
    npm install

### Crear archivo de entorno

	cp .env.example  .env

### ver que se creo

	cat .env

### Generar clave 

	php artisan key:generate

### Crear enlace a la carpeta de recursos

	php artisan storage:link
                
# Actualizar datos del archivo .env

    nano .env
        
    APP_NAME=NombreApp
    APP_URL=https://midominio.app/
    QUEUE_CONNECTION=database  // para activar las colas en la base de datos
#### Agregar

    APP_NAME_WA=nombre
    APP_SN_WA=nombre_corto
    APP_DESCRIPTION_WA=info_de_mi_web_app

         
##### Reemplazar en el .env, los nombres de las bases de datos a usar, usuario y contraseña para correr las migraciones
    
    nano .env
       
##### Ejecutar las migraciones
       
    php artisan migrate
    
## Traer los cambios del repositorio en GIT HUB a GIT main puede ser cambiado por un branch especifico

    git pull origin main
        
## Para correr el servidor local

    php artisan serve
    npm run dev

