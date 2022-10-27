# Twitter Scraper

## Nastavení .envů

- z ./.docker/.env.example vytvořit ./.docker/.env a nastavit v něm vlastní hodnoty
- z ./.env.local.example vytvořit ./.env.local a doplnit hodnoty podle předchozího envu z ./.docker/

## Spuštění dockeru

```shell
~/.docker$ docker-compose -f docker-compose.yml up --build
```

## Nastavení hosts souboru

do /etc/hosts (nebo alternativ podle OS) přidat řádek

`127.0.0.1 local.twitterscraper`

aplikace bude dostupná na `http://local.twitterscraper/`

