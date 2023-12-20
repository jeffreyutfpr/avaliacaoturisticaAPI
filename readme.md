# Sobre
A API foi desenvolvida em Node.js, é crucial para um sistema abrangente de gerenciamento de pacotes turísticos. Esta aplicação atua como um microsserviço focado na inserção e no acesso a feedbacks de clientes sobre experiências turísticas.

## Tecnologias

A API foi desenvolvida para aprimorar e fornecer uma solução eficaz no gerenciamento de feedback de clientes sobre passeios turísticos. A escolha criteriosa de tecnologias foi essencial para cumprir esse objetivo.

- **JavaScript:** Foi a linguagem de programação primária adotada no desenvolvimento desta aplicação.
- **Node.js:** Plataforma de execução do lado do servidor para JavaScript, que facilita a criação de aplicações web e APIs.
- **MongoDB:** Banco de dados NoSQL empregado para armazenar feedback de clientes, proporcionando flexibilidade e escalabilidade no armazenamento de dados.
- **Express:** Framework para Node.js que agiliza o desenvolvimento de aplicativos web, abrangendo especialmente a criação de APIs REST.
- **Outras dependências Node.js comuns:** Verifique o arquivo `package.json` para obter mais informações das demais dependências.

As tecnologias selecionadas foram fundamentais para criar uma aplicação eficaz no gerenciamento de avaliações turísticas. Node.js foi usado para desenvolver aplicativos web robustos, MongoDB para armazenar dados de forma flexível, Express para facilitar a criação de APIs, e dependências adicionais do Node.js foram incorporadas para ampliar a funcionalidade da aplicação.

## Como Iniciar

Etapas a seguir para iniciar o servidor da API localmente:

1. Clone este repositório em sua máquina:
```bash
git clone https://github.com/jeffreyutfpr/sistemadeavaliacaoturisticaAPI.git
```
2. Navegue até o diretório do projeto:
```bash
cd sistemadeavaliacaoturisticaAPI
```
3. Instale as dependências usando npm (Node.js Package Manager):
```bash
npm install
```
4. Inicie o servidor da API:
```bash
npm start
```

A API estará disponível em http://localhost:3000.

## Endpoints
A API oferece os seguintes endpoints:

**GET** /avaliacoes: Recupera todas as avaliações.

**GET** /avaliacoes/: id: Recupera uma avaliação específica por ID.

**POST** /avaliacoes: Insere uma nova avaliação.

**PUT** /avaliacoes/: id: Atualiza uma avaliação existente por ID.

**DELETE** /avaliacoes/: id: Exclui uma avaliação por ID.

---

© 2023 **Jeffrey Souza** | Este projeto faz parte das implementações da disciplina de Back-End do curso de Engenharia de Software da **UTFPR-CP**, ministrada pelo **Prof. Adriano Rivolli da Silva.**