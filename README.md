# Banco API Tests

Projeto de automação de testes para a API REST disponível em:\
https://github.com/juliodelimas/banco-api

Este repositório contém testes automatizados escritos em **JavaScript**,
utilizando ferramentas modernas do ecossistema Node.js para validar
endpoints da API de um sistema bancário.

------------------------------------------------------------------------

## 🎯 Objetivo do Projeto

Contribuir com a qualidade e o correto funcionamento da API REST por meio de
testes automatizados de integração, validando respostas, status codes e
comportamentos esperados.

------------------------------------------------------------------------

## 🧰 Stack Utilizada

-   **Node.js**
-   **Mocha** -- Framework de testes\
-   **Chai** -- Biblioteca de asserções\
-   **Supertest** -- Requisições HTTP para testar APIs\
-   **Mochawesome** -- Geração de relatórios HTML\
-   Outras dependências disponíveis no `package.json`

Documentações:\
- Mocha: https://mochajs.org\
- Chai: https://www.chaijs.com\
- Supertest: https://github.com/visionmedia/supertest\
- Mochawesome: https://github.com/adamgruber/mochawesome

------------------------------------------------------------------------

## 📁 Estrutura de Diretórios

    banco-api-tests/
    │── test/
    │   ├── login.test.js
    │   ├── transferencias.test.js
    │   └── ...
    │
    │── mochawesome-report/
    │   └── (gerado após execução com relatório HTML)
    │
    │── package.json
    │── .env (criado pelo usuário)
    │── README.md

------------------------------------------------------------------------

## ⚙️ Arquivo `.env`

Crie um arquivo `.env` na raiz do projeto com o seguinte formato:

    BASE_URL=http://localhost:3000

Essa variável define o endereço base da API que será testada.

------------------------------------------------------------------------

## ▶️ Como Executar os Testes

### 1. Instalar dependências

    npm install

### 2. Executar testes

    npm test

### 3. Gerar relatório Mochawesome

Após rodar os testes, o relatório HTML será gerado automaticamente em:

    /mochawesome-report/mochawesome.html

------------------------------------------------------------------------

## 📄 Relatórios

O Mochawesome gera relatórios completos em HTML, incluindo:\
- Testes executados\
- Sucessos e falhas\
- Screenshots (se configurado)

Para visualizar, abra o arquivo:

    mochawesome-report/mochawesome.html

------------------------------------------------------------------------

## 🧷 Links Úteis

-   Repositório da API testada:
    https://github.com/juliodelimas/banco-api
-   Repositório dos testes:
    https://github.com/Luanacvlcnt/banco-api-tests
