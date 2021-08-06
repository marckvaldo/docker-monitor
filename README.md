# Docker Monitor 

<div style="background-color: #f0f0f0; height:20vh; display: flex; flex-direction: row; justify-content: center;">
<img src="https://github.com/marckvaldo/docker-monitor/blob/main/imagens/Grafana.png">
</div>

![GitHub](https://img.shields.io/github/license/marckvaldo/docker-php)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/marckvaldo/docker-php)


## Descrição do Projeto
Esse projeto tem o intuito de monitorar os containes do projeto <a href="https://github.com/marckvaldo/docker-php">docker-php</a> (um ambiente docker para o laravel) ....

<h4>
    <a href="https://grafana.com/">🔗 Grafana</a>
</h4>
<p>🚀 Um ambiente pronto para monitorar os seus aplicativos que rodam no NGINX, DOCKER, MYSQL/MARIADB</p>


<h4> 
	🚧  Docker Monitor 🚀 Em construção...  🚧
</h4>

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:

[Git](https://git-scm.com)<br/>
[Docker](https://docs.docker.com/engine/install/). 

Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

### 🎲 Rodando

```bash
# Clone este repositório
$ git clone <https://github.com/marckvaldo/docker-monitor.git>

# Acesse a pasta do projeto no terminal/cmd
$ cd docker-monitor

# levante os docker 
$ docker-compose up -d

# O serviço grafana inciará na porta:3000 - acesse <http://localhost:3000>
# Para logar no grafana digite as credenciais encontradas no arquivo .env nas variaves "GF_SECURITY_ADMIN_USER" e "GF_SECURITY_ADMIN_PASSWORD".
```

### 🛠 Configuração
Todas as configurações do projeto estão no arquivo .env

Atenção Especial para as variaveis 
STATUS_NGINX
MYSQL_STRING 
onde tiver host-nginx e host-mysql substituir para o host da maquina que está executando os respequitivos serviços

### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Grafana](https://grafana.com/)
- [InfluxDb](https://www.influxdata.com/)
- [Telegaf](https://docs.influxdata.com/telegraf/v1.19/)
- [Docker](https://www.docker.com/)


#📝 Licença
Este projeto esta sobe a licença MIT.

Feito com ❤️ por Marckvaldo Wallas 👋🏽 Entre em contato (marckvaldo@hotmail.com, marckvaldowallas@gmail.com)
