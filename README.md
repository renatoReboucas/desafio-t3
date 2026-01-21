# Projeto da tasks

Este projeto é uma monólito construído com Next.js

## Pré-requisitos

- Docker
- Docker Compose
- node

## Como rodar o projeto

1. **Clone o repositório**:

   ```bash
   git clone https://github.com/renatoReboucas/desafio-t3.git
   cd desafio-t3
   ```

2. **Configure o arquivo `.env`**:
   Certifique-se de que o arquivo `.env` está configurado corretamente com todas as variáveis de ambiente necessárias.

3. **Construa e inicie o contêiner**:
   Execute o seguinte comando para construir e iniciar o contêiner:

   ```bash
    docker-compose up --build -d
   ```

4. **Acesse a API**:
   A API estará disponível em `http://localhost:3000/api`.

## Scripts disponíveis

- `npm run dev`: Inicia a aplicação.

## Estrutura do projeto

- `src/`: Contém o código fonte da aplicação.
- `docker-compose.yml`: Configuração do Docker Compose.

## Notas

- Certifique-se de que o Docker está rodando antes de executar os comandos.
- Verifique os logs do contêiner para diagnosticar problemas com:
  
  ```bash
  docker-compose logs
  ```
  