
# Projeto Docker UCP - Git - Nginx - Stack - Services
## artigo-swarm-nginx

#### Stack deploy usando o compose
<pre>
docker stack deploy -c docker-compose.yml nginx
</pre>

#### Escalar o serviço
<pre>
docker service scale nginx_web-nginx=3
</pre>
