# docker4symfony
Docker stack for Symfony projects

## Stack

| Container       | Versions                | Service name    | Image                              |
| --------------- | -------------------     | --------------- | ---------------------------------- |
| PHP with Apache | 7.3-apache<br>7.2-apache<br>7.1-apache<br>latest        | `php`           | [abgeo/php-symfony]                 |
| MariaDB         | 10.3, 10.2, 10.1        | `mariadb`       | [wodby/mariadb]                    |
| Mailhog         | latest                  | `mailhog`       | [mailhog/mailhog]                  |
| phpMyAdmin      | latest                  | `pma`           | [phpmyadmin/phpmyadmin]            |
| Portainer       | latest                  | `portainer`     | [portainer/portainer]              |
| Traefik         | latest                  | `traefik`       | [_/traefik]                        |

## License

This project is licensed under the MIT open source license.

[abgeo/php-symfony]: https://hub.docker.com/r/abgeo/php-symfony
[_/traefik]: https://hub.docker.com/_/traefik
[mailhog/mailhog]: https://hub.docker.com/r/mailhog/mailhog
[phpmyadmin/phpmyadmin]: https://hub.docker.com/r/phpmyadmin/phpmyadmin
[portainer/portainer]: https://hub.docker.com/r/portainer/portainer
[wodby/mariadb]: https://github.com/wodby/mariadb
