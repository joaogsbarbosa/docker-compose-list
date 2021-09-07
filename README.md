# docker-compose-list

## 1º passo - criação de diretórios e clone do repositório
*OBS: Esse passo deve ser realizado apenas uma vez.

#### Criação do diretório docker:       
   * No Linux:
      * Criar o diretório na home do usuário
        ex: /home/user/docker
      * Entrar no diretório

#### Em um terminal, dentro diretório docker, realizar o clone do projeto no github
          git clone https://github.com/joaogsbarbosa/docker-compose-list
          
## 2º passo - (re)criação dos containers
*OBS: Executar esse passo para criar e executar os containers pela primeira vez ou recriar e executar se houve alguma alteração no arquivo **docker-compose.yml**.*
   
### No terminal, abrir o diretório do serviço que você quer utilizar e executar o docker-compose
          docker-compose up -d        

## Comandos comuns

| Command                | Description                                                             |
|------------------------|-------------------------------------------------------------------------|
| docker compose build   | Build or rebuild services                                               |
| docker compose convert | Converts the compose file to platform’s canonical format                |
| docker compose cp      | Copy files/folders between a service container and the local filesystem |
| docker compose create  | Creates containers for a service.                                       |
| docker compose down    | Stop and remove containers, networks                                    |
| docker compose events  | Receive real time events from containers.                               |
| docker compose exec    | Execute a command in a running container.                               |
| docker compose images  | List images used by the created containers                              |
| docker compose kill    | Force stop service containers.                                          |
| docker compose logs    | View output from containers                                             |
| docker compose ls      | List running compose projects                                           |
| docker compose pause   | pause services                                                          |
| docker compose port    | Print the public port for a port binding.                               |
| docker compose ps      | List containers                                                         |
| docker compose pull    | Pull service images                                                     |
| docker compose push    | Push service images                                                     |
| docker compose restart | Restart containers                                                      |
| docker compose rm      | Removes stopped service containers                                      |
| docker compose run     | Run a one-off command on a service.                                     |
| docker compose start   | Start services                                                          |
| docker compose stop    | Stop services                                                           |
| docker compose top     | Display the running processes                                           |
| docker compose unpause | unpause services                                                        |
| docker compose up      | Create and start containers                                             |

## Referências
[Overview of docker-compose CLI](https://docs.docker.com/compose/reference/)

[docker compose](https://docs.docker.com/engine/reference/commandline/compose/)
