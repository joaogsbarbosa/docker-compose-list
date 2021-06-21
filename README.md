# docker-compose-list

## SETUP
*OBS: Esse passo deve ser realizado apena uma vez. Após o ambiente criado, utilizar o docker-compose para iniciar os containers como mostrado no tópico INICIANDO O AMBIENTE*

#### Criação do diretório docker:
*OBS: A criação do diretório é importante para os mapeamentos necessários*
          
   * No Linux:
      * Criar o diretório na home do usuário
        ex: /home/user/docker

#### Em um terminal/DOS, dentro diretório docker, realizar o clone do projeto no github
          git clone https://github.com/joaogsbarbosa/docker-compose-list
          
## INICIANDO O AMBIENTE
   
### No terminal, abrir o diretório do serviço que você quer utilizar e executar o docker-compose
          docker-compose up -d        

### Verificar imagens
          docker image ls

### Verificar containers
          docker container ls

## SOLUCIONANDO PROBLEMAS 

### Parar um container
         docker stop [nome do container]      

### Parar todos os containers
         docker stop $(docker ps -a -q)
  
### Remover um container
         docker rm [nome do container]

### Remover todos os containers
         docker rm $(docker ps -a -q)         

### Dados do containers
         docker container inspect [nome do container]

### Iniciar um container
         docker-compose up -d [nome do container]

### Iniciar todos os containers
         docker-compose up -d 

### Acessar log do container
         docker container logs [nome do container] 

## Acesso por shell
         docker exec -it [nome do container] bash
