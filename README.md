# App Flask com PostgreSQL - Infraestrutura na Nuvem com AWS - IFF 2024

Este projeto é uma aplicação Flask simples que se conecta a um banco de dados PostgreSQL e permite operações CRUD para a entidade `User`.

## Funcionalidades

- **Create**: Criar novos usuários.
- **Read**: Listar todos os usuários.
- **Update**: Atualizar um usuário existente.
- **Delete**: Deletar um usuário.

## Endpoints

- `POST /users`: Cria um novo usuário.
- `GET /users`: Lista todos os usuários.
- `PUT /users/<id>`: Atualiza o nome de um usuário específico.
- `DELETE /users/<id>`: Deleta um usuário específico.

## Configuração

### Pré-requisitos

- [Docker](https://www.docker.com/get-started) e [Docker Compose](https://docs.docker.com/compose/install/) instalados.

### Como rodar o projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/bmicaella/AWS-LG.git
   cd AWS-LG
