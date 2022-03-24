# Cours Symfony

Cours de symfony 5 en php 7.4 , mysql , phpmyadmin , maildev.

![Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/6/60/Symfony2.svg/1280px-Symfony2.svg.png)

## Deployment

To deploy this project run

```bash
   docker-compose up -d

   Si demandé pour l'image de PHP, faire un docker-compose build.
```

Pour connaitre les ports utilisés en localhost

```bash
  Docker ps
```

## pour tout stopper

stopper le project

```bash
docker stop www_docker_symfony && docker stop maildev_docker_symfony && docker stop phpmyadmin_docker_symfony && docker stop db_docker_symfony
```

## Documentation

[environnement](https://yoandev.co/un-environnement-de-d%C3%A9veloppement-symfony-5-avec-docker-et-docker-compose/)

[youtube de l'environnement](https://www.youtube.com/watch?v=tRI6KFNKfFo)

[cours nouvelle techno](https://www.youtube.com/watch?v=DBHs5iqxIPQ&list=PLBq3aRiVuwyyqbgym6fZcPSptUSmg9pkL)
