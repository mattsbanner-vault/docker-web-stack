# Docker Based PHP Development Environment
**This project is currently WIP. There is currently no stable functionality.**

> A full PHP development environment run within Docker. Includes NGINX, PHP 5.6, 7.0, 7.1, 7.2, 7.3 & 7.4, MySQL with a replication instance, PHPMyAdmin, MongoDB, Mongo Express, Redis, Redis Commander, Mailhog and Portainer to monitor the whole shebang.

## To Do
Here you can see what I'm working on.
- [ ] Setup MySQL Replication, this is working in the mysql-replication directory, just need to combine this and the existing MySQL stack
- [ ] Write the NGINX configs to reverse proxy each of the services, their ports can then be closed
- [ ] Implement each version of PHP to the NGINX config and allow to specify PHP version in hostname
- [ ] Very basic site at http://stack.dev.localhost with shortcuts to each of the stack web UI's.

## Ideas
Ideally, the user should only have to add the wildcard of `*.dev.localhost` to their hosts file. The stack can then be used with the following.

- Redis Commander - http://redis-commander.stack.dev.localhost
- PHPMyAdmin - http://phpmyadmin.stack.dev.localhost
- Mongo Express - http://mongo-express.stack.dev.localhost
- Mailhog - http://mailhog.stack.dev.localhost
- Portainer - http://portainer.stack.dev.localhost

Default PHP sites can then be accessed with http://site-folder-name.dev.localhost

Specific PHP sites can be targetted with
- http://site-folder-name.php56.dev.localhost
- http://site-folder-name.php70.dev.localhost
- http://site-folder-name.php71.dev.localhost
- http://site-folder-name.php72.dev.localhost
- http://site-folder-name.php73.dev.localhost
- http://site-folder-name.php74.dev.localhost