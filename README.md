# Docker-SqlServer2019
Docker compose para implmentação/disponibilização do Sql Server 2019

## Pré-requisito
- Docker instalado na máquina
- Acesso a rede para baixar a imagem
- Crie uma pasta chamada de [dados] um nível abaixo da pasta raiz deste projeto.
  - Esta pasta será utilizado para compartilhamento entre volumes

## Comando para iniciar o container
```
docker-compose up -d
```

## Comandos para encerrar o container
```
docker-compose down
```

## O que terá ao final do processo
- Servidor SQL Server 2019 habilitado para desenvolvimento de sistemas
- Rede interna no docker criada e pronta para ser compartilhada com outras aplicações também publicadas no docker
