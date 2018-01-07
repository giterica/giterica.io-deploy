giterica.io-deploy
==================

giterica.io deployment with Docker Swarm. docker-stack.yml and Caddy config for external HTTPS. 

Deployment
----------

First time:

```bash
docker swarm init
./init
```

Stack deployment

```bash
./deploy
```

See also
--------

* <https://github.com/giterica/giterica.io> - all about ``giterica.io`` Docker image
* <https://hub.docker.com/r/giterica/giterica.io/> - ``giterica.io`` on Docker Hub

License
-------

MIT