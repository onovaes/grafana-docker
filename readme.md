== Instalação ==
Grafana em container/docker. Após a instalação o login e usuário padrão é admin admin

== Instalação ==

1 - Clonar Repositório
$git clone https://github.com/onovaes/grafana-docker.git

2 - Entrar na pasta e criar pasta onde os arquivos serão persistidos
$cd grafana-docker
$mkdir data

3 - Salvar ID do seu usuário para ser executado como usuário do container
$ID=$(id -u)


4 - Subir o Cotainer
$docker-compose up