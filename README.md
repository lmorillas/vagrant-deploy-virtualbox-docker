# vagrant-deploy-virtualbox-docker
Demo of how to deploy Docker services using Vagrant and VirtualBox (academic purposes)

## How to start
- Go to repo dir and execute *vagrant up*
- Access docker service (adminer) through browser using url: *http://localhost:8080*
- La base de datos de Postgresql está en ```localhost 5432```
- Access deployed machine using *vagrant ssh*
- Carpeta mapeada en ```/vagrant```

## How to stop
- Go to repo dir and execute *vagrant halt*
- Eliminar: *vagrant destroy*
