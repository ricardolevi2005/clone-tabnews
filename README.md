# clone-tabnews

Implementação de projeto Tabnews através do Curso.dev


## Comandos Docker


```docker ps```
Lista processos dos containers, serve para consultar status atual do container.

```docker ps --all``` ou ```docker ps -a```
Lista até os containers inativos.

```docker logs nome-do-container```
Para visualizar logs do container.

Dica: usar a tecla ```tab``` para auto completar o nome do container.

```docker compose up```
Inicializa o container especificado no arquivo ```compose.yaml```.

```docker compose -f caminho/arquivo.yaml up```
Para usar outro arquivo yaml.

```docker compose up --detach``` ou ```docker compose up -d``` 
Para executar "nos bastidores" e deixar o terminal liberado.

```docker compose up -d --force-recreate```
Para recriar o container, ainda que já esteja em execução.

```docker compose stop``` (não apareceu na aula, mas é importante)
Pausa a execução do container, permitindo depois retomar a execução (resumir) com um up.

```docker compose down```
Encerra e destrói o container.