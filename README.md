# Projeto de API REST para Serviço de Streaming de Música

Este projeto é uma implementação de uma API REST para um serviço de streaming de música, com funcionalidades similares ao Spotify. O objetivo é demonstrar a utilização do Chalice para a criação de APIs REST e o armazenamento de dados no serviço de banco de dados não relacional da AWS DynamoDB.

## Instruções do Projeto

1. Estudar e realizar o tutorial básico do Chalice, disponível em [Tutorial Básico do Chalice](https://aws.github.io/chalice/tutorials/basicrestapi.html).
2. Projetar, implementar e demonstrar a execução de uma API REST para o serviço de streaming de música, de acordo com os requisitos fornecidos.
3. Utilizar o DynamoDB para armazenar os dados dos recursos, como usuários, músicas e playlists, conforme especificado no diagrama a seguir.
4. Implementar a funcionalidade de notificação por meio do serviço nativo AWS SNS, que será acionada sempre que uma nova música for criada.

## Diagrama de Recursos

O projeto deve abranger as seguintes entidades e operações:

- Usuários: criação, consulta, atualização e remoção de perfis de usuários.
- Músicas: gerenciamento de informações sobre músicas, incluindo nome e dados do artista.
- Playlists: operações para criação, consulta, atualização e remoção de playlists de usuários.

## Estrutura do Repositório
