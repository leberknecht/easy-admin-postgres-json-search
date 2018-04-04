Installation
----

    composer install
    docker-compose run ea_phpfpm php bin/console doctrine:database:create
    docker-compose run ea_phpfpm php bin/console doctrine:migrations:migrate -n
    docker-compose run ea_phpfpm php bin/console assets:install --symlink --relative
    docker-compose up -d
 
 