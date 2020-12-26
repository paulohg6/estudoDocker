# Curso Alura de Docker

## Comandos Basicos:

docker ps = listar todos o containers ativos no momento

docker ps -a = listar todos os conteiners ja criados

docker run -it ubuntu = caso você tenha baixado a imagem do ubunto o seu terminar vira o terminal do ubuntu

docker start = inicia o container lembrar de colocar o -a e -i

docker stop = parar o container

docker run -d nomeDaImagem  = Ele roda o docker mas nao trava o terminal. roda em background

docker run -d -P nomeDaImagem = -P mapeia uma porta aleatoria do PC o container

docker port idDoContainer = Mostra a porta mapeada para o container

docker container prume = remove todos os containers parados

docker ps -q = retonar somente o id dos containers ativos

docker stop $(docker ps -q) = Vai parar todos os containers ativos que o comando docker ps -q vai retonrar

docker port ID_DO_CONTAINER = saber a porta mapeada
docker ps - exibe todos os containers em execução no momento.
docker ps -a - exibe todos os containers, independentemente de estarem em execução ou não.
docker run -it NOME_DA_IMAGEM - conecta o terminal que estamos utilizando com o do container.
docker start ID_CONTAINER - inicia o container com id em questão.
docker stop ID_CONTAINER - interrompe o container com id em questão.
docker start -a -i ID_CONTAINER - inicia o container com id em questão e integra os terminais, além de permitir interação entre ambos.
docker rm ID_CONTAINER - remove o container com id em questão.
docker container prune - remove todos os containers que estão parados.
docker rmi NOME_DA_IMAGEM - remove a imagem passada como parâmetro.
docker run -d -P --name NOME dockersamples/static-site - ao executar, dá um nome ao container.
docker run -d -p 12345:80 dockersamples/static-site - define uma porta específica para ser atribuída à porta 80 do container, neste caso 12345.
docker run -d -P -e AUTHOR="Fulano" dockersamples/static-site - define uma variável de ambiente AUTHOR com o valor Fulano no container criado.
 
 
..
