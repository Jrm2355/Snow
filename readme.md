# SnowTricks

SnowTricks est un site internet présentant des figures de snow.

### Pré-requis
    * PHP
    * Composer
    * Symfony cli
    * Docker
    * Docker-compose

-> symfony check:requirements

### Lancer environnement de développment

    composer install
    npm install
    npm run build
    docker-compose up -d
    symfony server:start -d

#### Charger les fixtures

    php bin/console doctrine:fixtures:load

#### GIT

    git checkout [branche] // changer de branche
    git branch -d [branche] // supprimer la branche en local

#### Lancer un test
