# Comandos básicos no dia a dia para Docker

# 1.	Containers: 

docker container <COMANDO>

* create — Crie um novo container.
* start — Start an existing container.
*	run — Crie um novo contêiner e inicie-o.
*	ls — Listar contêineres em execução.
*	logs — Print logs.
*	stop — Para container.
*	kill — Mate um ou mais contêineres em execução.
*	rm— Excluir um contêiner parado.
*	prune - Remova todas os containers parados

1.	docker container run <NOME/ID IMAGE>
2.	docker container stop < NOME/ID IMAGE>
3. docker container rm < NOME/ID IMAGE>
4.	docker container logs –f < NOME/ID IMAGE>

# 2.	Images:
docker image <COMANDO>

*	build — Criar uma imagem a partir de um Dockerfile.
*	push — Enviar uma imagem para um Dockerhub.
*	ls — Listar imagens.
*	inspect — Informações sobre a imagem.
*	rm — Remova uma ou mais images
*	prune - Remova todas as images não utilizadas

1.	docker images ls
2.	docker image rm < NOME/ID IMAGE>
3.	docker image inspect < NOME/ID IMAGE>

# 3.	network:
docker network <COMANDO>

*	create — Criar uma rede.
*	connect - Conecte um contêiner a uma rede
*	ls — Listar redes.
*	rm — Remova uma ou mais redes
*	prune - Remova todas as redes não utilizadas

1.	docker network create < NOME NETWORK>
2.	docker network ls 

# 4.	Diversos: 
1.	docker exec -it < NOME/ID IMAGE> bash – Executar um comando em um contêiner em execução.
2.	docker version - Liste informações sobre as versões do Docker Client e Server.
3.	docker system prune - Exclua todos os contêineres, redes e imagens não utilizadas/ pendentes
