# Docker Todo List
Projeto da [Trybe](https://www.betrybe.com/) - Criação e orquestração de containers com Docker.

## 💻 Projeto

"Conteinerização" de aplicações de frontend, backend e testes com o uso de Docker, criando uma conexão entre elas e orquestrando seu funcionamento.

<details>
  <summary><strong>🏆 Meu desempenho</strong></summary><br />

  <img src="<img src="https://a.imagem.app/onleuY.png" alt="onleuY.png" border="0" />"/>
</details>

## 🚀 Tecnologias
> Este projeto foi desenvolvido com as seguintes tecnologias:

- Bash
- Docker

## 📌 Habilidades

> Neste projeto, desenvolvi as seguintes habilidades:

- Usar comandos Docker na CLI;
- Criar imagens Docker de aplicações;
- Criar e executar contêineres Docker;
- Orquestrar contêineres utilizando o Docker Compose.

## ⬇️ Instalando dependências

```bash
npm install
cd docker
``` 

## ⚡ Executando a aplicação

Inicialmente fazemos o build das imagens de back-end, front-end e testes:
```bash
docker image build -t todobackend ./todo-app/back-end
docker image build -t todofrontend ./todo-app/front-end
docker image build -t todotests ./todo-app/tests
``` 
Então subimos e orquestramos os containers:

```bash
docker-compose up -d
``` 
Para executar a aplicação, basta acessar o endereço http://localhost:3000 no browser.

## 🧪 Executando os testes

Para rodar os testes:

```bash
docker attach docker_todotests_1
```


[⬆ Voltar ao topo](#nome-do-projeto)<br> -->
