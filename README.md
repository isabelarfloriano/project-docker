# Boas-vindas ao repositório do projeto Docker!
### Projeto desenvolvido durante o módulo de back-end da Trybe

Neste projeto realizei:

1. **_Conteinerização_** das aplicações;
1. Criação de uma conexão entre elas;
1. Orquestração seu funcionamento.

Temos uma aplicação full-stack neste repositório: um **aplicativo de tarefas**, que foi disponibilizada pela Trybe(https://www.betrybe.com/) para desenvolvimento do projeto.
Criar as imagens para as aplicações e configurei essas imagens com o `docker-compose`.

Para isto, utilizei uma série de comandos do `docker` com diferentes níveis de complexidade.

Cada comando foi escrito em seu próprio arquivo dentro da pasta `./docker` composta por:
 
 1. Pasta `docker-commands`: onde ficaram os comandos do CLI *(Interface de Linha de Comando)* do Docker que resolviam os requisitos propostos pela instituição.
 2. Pasta `todo-app`: onde fica a **pseudo-aplicação**, que serviu como base para os `Dockerfile`s e `Compose` desenvolvidos por mim.
 3. Arquivo `docker-compose.yml` criado para a orquestração das aplicações.
