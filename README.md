
Projeto Docker - Git - Nginx
# artigo-swarm-nginx

#### Stack deploy usando o compose

docker stack deploy -c docker-compose.yml nginx

#### Escalar o serviço

docker service scale nginx_web-nginx=3
