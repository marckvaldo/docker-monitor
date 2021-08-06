# Docker Laravel 

<div style="background-color: #f0f0f0; height:20vh; display: flex; flex-direction: row; justify-content: center;">
<img src="https://github.com/marckvaldo/docker-php/blob/main/www/public/imagens/laravel.png">
<img src="https://github.com/marckvaldo/docker-php/blob/main/www/public/imagens/docker.png">
</div>

![GitHub](https://img.shields.io/github/license/marckvaldo/docker-php)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/marckvaldo/docker-php)


## Descrição do Projeto
Esse projeto tem o intuito de monitorar os container do docker-php (um ambiente docker para o laravel) ....

<h4>
    <a href="https://laravel.com/">🔗 Grafana</a>
</h4>
<p>🚀 Ambiente pronto para construções de Apps em PHP ou Laravel</p>


<h4> 
	🚧  Docker Laravel 🚀 Em construção...  🚧
</h4>

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:

[Git](https://git-scm.com)<br/>
[Docker](https://docs.docker.com/engine/install/). 

Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

### 🎲 Rodando

```bash
# Clone este repositório
$ git clone <https://github.com/marckvaldo/docker-php.git>

# Acesse a pasta do projeto no terminal/cmd
$ cd docker-php

# levante os docker 
$ docker-compose up -d

# O servidor inciará na porta:80/443 - acesse <http://localhost>
# O phpMyadmin está rodando na porta 8000 então digite localhost:8000
# Para logar no phpMyadmin no campo Host/Servidor digite o nome do container Mysql/MariaDB que está na coluna NAMES.
# Para ver o nome do container digite no terminal docker ps...

#CONTAINER ID   IMAGE                   COMMAND                  CREATED         STATUS         PORTS                                                                      NAMES
#a26674f177ae   phpmyadmin/phpmyadmin   "/docker-entrypoint.…"   3 minutes ago   Up 3 minutes   0.0.0.0:8000->80/tcp, :::8000->80/tcp                                      docker-php_phpmyadmin_1
#9010af215c79   docker-php_nginx        "nginx -g 'daemon of…"   6 minutes ago   Up 6 minutes   0.0.0.0:80->80/tcp, :::80->80/tcp, 0.0.0.0:443->443/tcp, :::443->443/tcp   docker-php_nginx_1
#c1740f64316d   docker-php_php          "docker-php-entrypoi…"   6 minutes ago   Up 6 minutes   0.0.0.0:9000->9000/tcp, :::9000->9000/tcp                                  docker-php_php_1
#9cb8b5bccf54   mysql:5.7.29            "docker-entrypoint.s…"   6 minutes ago   Up 6 minutes   33060/tcp, 0.0.0.0:3307->3306/tcp, :::3307->3306/tcp                       docker-php_dataBaseMysql_1
#8610cf137383   redis                   "docker-entrypoint.s…"   6 minutes ago   Up 6 minutes   0.0.0.0:8379->6379/tcp, :::8379->6379/tcp                                  docker-php_redis_1

# No exemplo acima é o "docker-php_dataBaseMysql_1"
```

### 🛠 Configuração

As configurações de senha e porta do Mariadb e phpmyadmin estão no arquivo .env na raiz do projeto

### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Nginx](https://www.nginx.com/)
- [Mariadb](https://mariadb.org/)
- [PHP](https://www.php.net/)
- [Redis](https://redis.io/)
- [Docker](https://www.docker.com/)


#📝 Licença
Este projeto esta sobe a licença MIT.

Feito com ❤️ por Marckvaldo Wallas 👋🏽 Entre em contato (marckvaldo@hotmail.com, marckvaldowallas@gmail.com)
