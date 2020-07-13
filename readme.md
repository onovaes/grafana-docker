# Grafana em container

Como rodar a última versão do grafana em um container do docker


## Instalação 

1 - Clonar Repositório
```
git clone https://github.com/onovaes/grafana-docker.git
```

2 - Entrar na pasta e criar pasta onde os arquivos serão persistidos
```
cd grafana-docker
$mkdir data
```
3 - Salvar ID do seu usuário para ser executado como usuário do container
```
$ID=$(id -u)
```
4 - Subir o Cotainer
```
$docker-compose up
```

5 - Acessar o navegador (admin/admin) http://localhost:3000
