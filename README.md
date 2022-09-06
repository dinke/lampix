# Lampix
Docker bootstrap for typical LAMP stack along with Symfony cli installer command

## Requirements
- Docker

## Installation

```
# Build containers
docker-compose up -d --build

# Check Symfony requirements
docker-compose exec php symfony check:requirements

# All green? Instal Symfony into app folder
docker-compose exec php symfony new .
```

Note: If you don't want to use Symfony, no problem. Just create app/public folder which will be your Document Root

Credits:
Based on https://www.twilio.com/blog/get-started-docker-symfony