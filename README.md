# docker-todo-list

Este é um projeto simples de uma lista de tarefas (to-do list) que usa o Docker para facilitar o ambiente de desenvolvimento.

## Como usar

1. Clone este repositório em seu computador:
```bash
git clone https://github.com/GabrielDota/docker-todo-list.git
```
2. Navegue até o diretório raiz do projeto:
```bash
cd docker-todo-list
```
3. Inicie o contêiner do Docker Compose:
```
docker-compose up -d
```
4. Acesse o aplicativo em seu navegador em:
```
http://localhost:3000/
```
5. Para parar o contêiner, execute o seguinte comando:
```
docker-compose down
```

## Requisitos de docker:

1. Crie um container em modo interativo, sem rodá-lo, nomeando-o como 01container e utilizando a imagem alpine na versão 3.12

2. Inicie o container 01container

3. Liste os containers filtrando pelo nome 01container

4. Execute o comando cat /etc/os-release no container 01container sem se acoplar a ele

5. Remova o container 01container

6. Faça o download da imagem nginx com a versão 1.21.3-alpine sem criar ou rodar um container

7. Rode um novo container com a imagem nginx com a versão 1.21.3-alpine em segundo plano nomeando-o como 02images e mapeando sua porta padrão de acesso para porta 3000 do sistema hospedeiro

8. Pare o container 02images que está em andamento

## Requisitos de dockerfile
9. Gere uma build a partir do Dockerfile do back-end do todo-app nomeando a imagem para todobackend

10. Gere uma build a partir do Dockerfile do front-end do todo-app nomeando a imagem para todofrontend

11. Gere uma build a partir do Dockerfile dos testes do todo-app nomeando a imagem para todotests

12. Suba uma orquestração em segundo plano com o docker-compose de forma que backend, frontend e tests consigam se comunicar
