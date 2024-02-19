# :construction: Projeto Docker To Do List :construction:
O projeto teve como objetivo aprender e praticar o uso do Docker para facilitar o desenvolvimento, o empacotamento e a implantação de aplicativos por meio de contêineres. Abaixo está uma descrição das etapas realizadas e dos comandos Docker utilizados:

## Etapas Realizadas:
### Criação de Contêineres Alpine: 
Foram criados contêineres utilizando a imagem Alpine Linux versão 3.12, um sistema operacional leve, utilizando o comando docker container create.

### Início e Listagem de Contêineres: 
Os contêineres foram iniciados e listados utilizando os comandos docker start e docker container ls -a, respectivamente.

### Execução de Comandos nos Contêineres: 
Foram executados comandos dentro dos contêineres utilizando o comando docker exec, como exibir informações do sistema operacional.

### Remoção de Contêineres: 
Os contêineres foram removidos utilizando o comando docker container rm -f.

### Utilização de Imagens Nginx: 
Foi feito o download da imagem Nginx versão 1.21.3-alpine e iniciado um contêiner a partir dela, expondo a porta 80 do contêiner para a porta 3000 do host.

### Build de Imagens Personalizadas: 
Foram criados Dockerfiles para cada parte da aplicação (backend, frontend e testes) e as imagens foram construídas utilizando o comando docker build.

## Tecnologias Utilizadas:
### Docker: 
A principal tecnologia utilizada no projeto foi o Docker, uma plataforma de código aberto que permite a criação, a execução e o gerenciamento de contêineres de aplicativos.

### Alpine Linux: 
A imagem Alpine Linux foi escolhida devido à sua leveza e eficiência, tornando-a ideal para contêineres Docker.

### Node.js: 
Node.js foi utilizado para o desenvolvimento das partes backend e frontend da aplicação, aproveitando seu ecossistema de pacotes e sua facilidade de uso.

