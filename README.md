# TEPW - Biblioteca Virtual
Projeto que inicialmente visa a construção de uma API completa para uma biblioteca virtual, sendo necessário a conclusão de alguns requisítos.

## Pré-requisitos de Instalação
No Spring Initialzr:
- Lombok
- Spring Web
- Spring Data JPA
- H2 Database
- Docker Compose Support

## Requisítos
- Definição e validação dos requisitos de um software de biblioteca virtual pública;
- Definição de cronograma de entregas por membro;
- Desenvolver rotas para 05 CRUDs completos (cadastrar, editar, pesquisar todos, pesquisar por ID e excluir);
- Desenvolver pelo menos 01 funcionalidade (que ñ envolva CRUD) no contexto especificado, sendo avaliado pela complexidade do desenvolvimento;
- As entidades deverão possuir ao menos 04 atributos ( sem contar o ID ), podendo diminuir mediante justificativa do contexto;
- Todas as entidades deverão possuir as camadas e padrões de projeto abordados em sala ( Model, DTO, Repository, Service e Controller );
- As possíveis exceções/erros deverão ser devidamente tratados e retornados de uma forma amigável na rota (com seus respectivos Status Code);
- Todas as operações de CRUD das entidades deverão ser executadas em uma base de dados;
- Todo o DDL das tabelas das entidades deverão ser executados via Migration;
- Todas as rotas da API deverão ser completamente documentadas (Swagger);
