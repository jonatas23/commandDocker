# Comandos básicos no dia a dia para Docker

<details>
    <summary>1.	Containers </summary>
  
    Containers:  
    docker container <COMANDO>
  
    * create — Crie um novo container.
    * start — Start an existing container.
    * run — Crie um novo contêiner e inicie-o.
    * ls — Listar contêineres em execução.
    * logs — Print logs.
    * stop — Para container.
    * kill — Mate um ou mais contêineres em execução.
    * rm — Excluir um contêiner parado.
    * prune - Remova todas os containers parados

    > docker container run <NOME/ID IMAGE>
    > docker container stop < NOME/ID IMAGE>
    > docker container rm < NOME/ID IMAGE>
    > docker container logs –f < NOME/ID IMAGE>        
</details>

<details>
    <summary>2.	Images </summary>

    Images:
    docker image <COMANDO>

    * build — Criar uma imagem a partir de um Dockerfile.
    * push — Enviar uma imagem para um Dockerhub.
    * ls — Listar imagens.
    * inspect — Informações sobre a imagem.
    * rm — Remova uma ou mais images
    * prune - Remova todas as images não utilizadas

    > docker images ls
    > docker image rm < NOME/ID IMAGE>
    > docker image inspect < NOME/ID IMAGE>
</details>

<details>
    <summary>3.	Network </summary>

    Network:
    docker image <COMANDO>

    * create — Criar uma rede.
    * connect - Conecte um contêiner a uma rede
    * ls — Listar redes.
    * rm — Remova uma ou mais redes
    * prune - Remova todas as redes não utilizadas

    > docker network create < NOME NETWORK>
    > docker network ls 
</details>

<details>
    <summary>4.	Diversos </summary>

    Diversos:
    > docker exec -it < NOME/ID IMAGE> bash – Executar um comando em um contêiner em execução.
    > docker version - Liste informações sobre as versões do Docker Client e Server.
    > docker system prune - Exclua todos os contêineres, redes e imagens não utilizadas/ pendentes
</details>
