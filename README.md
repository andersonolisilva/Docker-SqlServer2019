# Docker-SqlServer2019
Docker compose para implmentação/disponibilização do Sql Server 2019

## Pré-requisito
- Docker instalado na máquina
- Acesso à Internet para baixar a imagem
- Crie uma pasta chamada de [dados] um nível abaixo da pasta raiz deste projeto.
  - Esta pasta será utilizada para compartilhamento entre volumes e evitar que ocorra perda de dados ao encerrar o container

## Comando para iniciar o container
O comando abaixo deverá ser executado dentro da pasta raiz do projeto
```
docker-compose up -d
```

# Comando para iniciar o container
```
docker start sql1
```

# Comando para parar o container
```
docker stop sql1
```

## Comandos para encerrar/destruir o container
```
docker-compose down
```

## O que terá ao final do processo
- Servidor SQL Server 2019 habilitado para desenvolvimento de sistemas
- Rede interna no docker criada e pronta para ser compartilhada com outras aplicações também publicadas no docker
