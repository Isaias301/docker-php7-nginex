# php7-nginex!

Estrutura para docker como php7 e nginex pronta para servidores ou droplets digital ocean.
Para poder utiliza-la siga os passos abaixo:
- Entre no sistema como root ( **sudo du** ).
- [Instale o docker-compose](https://docs.docker.com/compose/install/#master-builds) ( **curl -L https://github.com/docker/compose/releases/download/1.18.0/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose** ).
- Instale o mysql na maquina host ( **apt-get install mysql-server** ).
- [Instale o git](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Instalando-o-Git) ( **apt-get install git**).
- Inicie o git ( **git init** ).
- [Clone o projeto](https://github.com/Isaias301/php7-nginex.git) ( **git clone https://github.com/Isaias301/php7-nginex.git** ).
- Entre na pasta do projeto ( **cd php7-nginex.git** ).
- Execute o comando ( **docker-compose up** ).
