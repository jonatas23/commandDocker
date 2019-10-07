# Comandos básicos no dia a dia para Docker

<p> Docker é uma plataforma open source na linguagem de programação Go, que possui alto desempenho e é desenvolvida diretamente no Google. Tecnologia usada para criação e uso de containers Linux.  </p>

<details open>
    <summary>1.	Containers </summary>
    <h4> O container é um ambiente isolado. </h4>
    
    Containers:  
    docker container <COMANDO>
  
    * create — Crie um novo container.
    * start — Start an existing container.
    * run — Crie um novo contêiner e inicie-o.
    * ls ou ps — Listar contêineres em execução.
    * logs — Print logs.
    * stop — Parar container.
    * kill — Mate um ou mais contêineres em execução.
    * rm — Excluir um contêiner parado.
    * prune - Remova todas os containers parados

    Ex:
    > docker ps
    > docker container ls
    > docker container run <NOME/ID IMAGE>
    > docker container stop < NOME/ID IMAGE>
    > docker container rm < NOME/ID IMAGE>
    > docker container logs –f < NOME/ID IMAGE>        
</details>

<details open>
    <summary>2.	Images </summary>
    <h4>De uma forma bem resumida a image é um template em camadas para executar um container.</h4>
    
    Images:
    docker image <COMANDO>

    * build — Criar uma imagem a partir de um Dockerfile.
    * push — Enviar uma imagem para um Dockerhub.
    * ls — Listar imagens.
    * inspect — Informações sobre a imagem.
    * rm — Remova uma ou mais images
    * prune - Remova todas as images não utilizadas

    Ex:
    > docker images ls
    > docker image rm < NOME/ID IMAGE>
    > docker image inspect < NOME/ID IMAGE>
</details>

<details open>
    <summary>3.	Network </summary>
    <h4> Docker nos permite criar uma ou mais redes </h4>
    
    Network:
    docker image <COMANDO>

    * create — Criar uma rede.
    * connect - Conecte um contêiner a uma rede
    * ls — Listar redes.
    * rm — Remova uma ou mais redes
    * prune - Remova todas as redes não utilizadas

    Ex:
    > docker network create < NOME NETWORK>
    > docker network ls 
</details>

<details open>
    <summary>4.	Diversos </summary>

    Diversos:
    
    Ex:
    > docker exec -it < NOME/ID IMAGE> bash – Executar comando em um contêiner em execução.
    > docker run --name <NAME CONTAINER> -it <IMAGEM> - O Docker executa processos em contêineres isolados.
    > docker ps -a - Lista todos os containers existentes no host
    > docker version - Liste informações sobre as versões do Docker Client e Server.
    > docker system prune - Exclua todos os contêineres, redes e imagens não utilizadas/ pendentes


</details>
