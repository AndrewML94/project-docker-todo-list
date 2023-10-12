# Projeto Docker Todo List (Décimo sétimo projeto desenvolvido)

Neste projeto temos uma aplicação full-stack: um aplicativo de tarefas! Esta aplicação precisa ser conteinerizada para funcionar. E eu desenvolvi os arquivos de configuração para cada frente específica: Front-end, Back-end e, para um aplicativo de teste que valida se as aplicações estão se comunicando.

## Habilidades desenvolvidas

- O conhecimento dos comandos dockers no CLI - Interface de linha de comando;
- A habilidade de criar um contêiner Docker para uma aplicação de front-end;
- A habilidade de criar um contêiner Docker para uma aplicação de back-end;
- A habilidade de criar um contêiner Docker para uma aplicação de testes;
- A habilidade de orquestrar os três contêineres utilizando o Docker compose.

## O que foi desenvolvido pelo autor

Todo o conteúdo e elementos presentes na pasta "src/docker-commands" foram desenvolvidos exclusivamente por mim, representando minha contribuição integral a este projeto. É importante mencionar que os demais arquivos foram elaborados pela equipe da Trybe como parte do contexto mais amplo do projeto.

## Requisitos do projeto

1. Criar um container em modo interativo, sem rodá-lo, nomeando-o como 01container e utilizando a imagem alpine na versão 3.12;
2. Iniciar o container 01container;
3. Listar os containers filtrando pelo nome 01container;
4. Executar o comando cat /etc/os-release no container 01container sem se acoplar a ele;
5. Remover o container 01container;
6. Fazer o download da imagem nginx com a versão 1.21.3-alpine sem criar ou rodar um container;
7. Rodar um novo container com a imagem nginx com a versão 1.21.3-alpine em segundo plano nomeando-o como 02images e mapeando sua porta padrão de acesso para porta 3000 do sistema hospedeiro;
8. Parar o container 02images que está em andamento;
9. Gerar uma build a partir do Dockerfile do back-end do todo-app nomeando a imagem para todobackend;
10. Gerar uma build a partir do Dockerfile do front-end do todo-app nomeando a imagem para todofrontend;
11. Gerar uma build a partir do Dockerfile dos testes do todo-app nomeando a imagem para todotests;
12. Subir uma orquestração em segundo plano com o docker-compose de forma que backend, frontend e tests consigam se comunicar.