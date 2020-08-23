# docker-nginx-php-setup
Docker, for Laravel made, web-server which uses **[NGINX](https://hub.docker.com/_/nginx)** and **[PHP](https://hub.docker.com/_/php)** images.

> If you're searching for a Docker setup that includes database service like postgres (it's easily changeable), look into this repo https://github.com/grunburg/docker-nginx-php-pgsql-setup

### Installation

1. Clone this repository in your project folder.
```
$ git clone https://github.com/grunburg/docker-nginx-php-setup .
```
2. Edit [default.conf](https://github.com/grunburg/docker-nginx-php-setup/blob/master/default.conf) and [docker-compose.yml](https://github.com/grunburg/docker-nginx-php-setup/blob/master/docker-compose.yml): ports, volumes, etc.

3. To start the server, navigate to your folder via Terminal and run this command:
```
$ docker-compose build && docker-compose up -d
```

4. Congratulations! You have succesfully setup **NGINX** Server/Container.

### Usage
* You can access your web server via browser [localhost:8000](http:localhost:8000) (Or your port that you configured earlier).
* To turn on your container or restart or stop it, you can now use **Docker Desktop** interface.

![Screenshot](https://i.ibb.co/8Dr8j8f/Anot-cija-2020-04-11-214450.png)

