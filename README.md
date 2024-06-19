Para rodar o docker é preciso confirmar se o docker e o docker-compose estão devidamente configurados na sua maquina

Use `sudo docker run hello-world` para testar o docer
Use `docker compose version` para testar o docker compose

crie um diretorio para armazenar os arquivos do docker e acesse ele
`
mkdir projetoDocker
cd projetoDocker
`

clone os dados do github 
`
git clone https://github.com/GusDechotti/Projeto-Docker.git
`

rode o docker compose
`
sudo docker compose up -d
`

Verifique o http://localhost:9090/ para mais informações do Prometheus
