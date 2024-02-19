# LARAVEL WEB APP EXAMPLE

## Clone

    cd /path
    
    git clone git@github.com:path.git path.app.lan
            
## Enter folder
        
    cd my-web.lan
        
## For install

    composer install
    npm install

### Create environment file

	cp .env.example  .env

### see what was created

	cat .env

### Generate key

	php artisan key:generate

### Create link to resources folder

	php artisan storage:link
                
# Update .env file data

    nano .env
        
    APP_NAME=App Name
    APP_URL=https://domain.app/
#### Agregar

    APP_NAME_WA=name
    APP_SN_WA=short_name
    APP_DESCRIPTION_WA=info_about_my_web_app

         
##### Replace in the .env, the names of the databases to use, username and password to run the migrations
    
    nano .env
       
##### Run the migrations
       
    php artisan migrate
    
## Bringing changes from the GIT HUB repository to GIT main can be changed by a specific branch

    git pull origin main
        
## To run the local server

    php artisan serve
    npm run dev

