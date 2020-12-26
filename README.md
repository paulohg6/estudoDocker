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

 
 
..
