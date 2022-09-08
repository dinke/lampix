# Lampix
Docker bootstrap for typical LAMP stack along with Symfony or Laravel frameworks

## Requirements
- Docker

## Installation

```
# Build containers
docker-compose up -d --build

# Wanna setup new Symfony project? Run command bellow
docker-compose exec php symfony --no-git new .

# Wanna setup new Laravel project? Run command bellow
docker-compose exec php composer create-project laravel/laravel .
```

You can test your new app by hitting http://localhost:8080.

Note: If you don't want to use Symfony or Laravel, no problem. Just create app/public folder which will be your Document Root

Credits:
Based on https://www.twilio.com/blog/get-started-docker-symfony