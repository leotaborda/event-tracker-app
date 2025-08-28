# Projeto: Event Tracker

## Descrição

Este projeto foi desenvolvido durante o curso "React: gerenciando estado com Recoil" da Alura, ministrado por Vinicios Neves. O objetivo principal foi aprender e aplicar técnicas de gerenciamento de estado em aplicações React utilizando a biblioteca Recoil.

A aplicação permite gerenciar uma lista de eventos, adicionar, editar e excluir eventos de forma eficiente.

## Funcionalidades

*   Adicionar novos eventos com título, data e horário.
*   Editar eventos existentes.
*   Excluir eventos da lista.
*   Filtrar eventos por data.
*   Persistência de dados utilizando.

## Tecnologias Utilizadas

*   React
*   Recoil
*   TypeScript

## Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina:

*   [Node.js](https://nodejs.org/)
*   [npm](https://www.npmjs.com/) (geralmente instalado com o Node.js)

## Instalação

1.  Clone este repositório:

    ```bash
    git clone [URL do repositório]
    ```
2.  Acesse a pasta do projeto:

    ```bash
    cd [nome do projeto]
    ```
3.  Instale as dependências:

    ```bash
    npm install
    ```

## Execução

Para executar a aplicação, siga os seguintes passos:

1.  Inicie o servidor de desenvolvimento:

    ```bash
    npm run dev
    ```

    Este comando irá iniciar a aplicação no modo de desenvolvimento, geralmente acessível em `http://localhost:3000`.
2.  Inicie o servidor JSON (se aplicável):

    ```bash
    npm run server
    ```

    Este comando irá iniciar o servidor JSON na porta 5500, `http://localhost:5500`, que será utilizado para simular uma API para persistência de dados.

## Debug

Durante o curso, aprendemos a utilizar ferramentas de debug para facilitar o desenvolvimento e a identificação de problemas. Para auxiliar na depuração, foi criado um componente que faz o log no console de todas as alterações de estado.

## Considerações Finais

Este projeto foi uma excelente oportunidade para aprofundar os conhecimentos em gerenciamento de estado com Recoil e aplicar as boas práticas de desenvolvimento aprendidas no curso. A refatoração do código, a criação de *hooks* customizados e a utilização de ferramentas de debug foram fundamentais para tornar a aplicação mais escalável e fácil de manter.

## Próximos Passos

*   Implementar testes unitários e de integração.
*   Adicionar autenticação de usuários.
*   Melhorar a interface do usuário.
*   Implementar novas funcionalidades.
