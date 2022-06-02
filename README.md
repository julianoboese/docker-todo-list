# Docker Todo List
Projeto da [Trybe](https://www.betrybe.com/) - Bloco 19 - Criação e orquestração de containers com Docker.

## 💻 Projeto

"Conteinerização" de aplicações de frontend, backend e testes com o uso de Docker, criando uma conexão entre elas e orquestrando seu funcionamento.

<details>
  <summary><strong>Meu desempenho</strong></summary><br />

  <img />
</details>

## 🚀 Tecnologias
Esse projeto foi desenvolvido com as seguintes tecnologias:

## 📌 Habilidades

Nesse projeto, desenvolvi as seguintes habilidades:

- Usar comandos dockers no CLI - Interface de linha de comando;
- Criar um contêiner Docker para uma aplicação de front-end;
- Criar um contêiner Docker para uma aplicação de back-end;
- Criar um contêiner Docker para uma aplicação de testes;
- Orquestrar os três contêineres utilizando o Docker compose.

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
## 💬 Contatos

<div align="center" style="display: inline_block">
  <a href="https://julianoboese.github.io" target="_blank"><img height="28rem" src="https://img.shields.io/badge/my_portfolio-3fc337?style=for-the-badge" target="_blank"></a> 
  <a href="https://www.linkedin.com/in/julianoboese" target="_blank"><img height="28rem" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> 
  <a href = "mailto:juliano.boese@gmail.com"><img height="28rem" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
</div>
<!-- ## 📄 Licença

Esse projeto está sob licença. Veja o arquivo [LICENÇA](LICENSE.md) para mais detalhes.

[⬆ Voltar ao topo](#nome-do-projeto)<br> -->
