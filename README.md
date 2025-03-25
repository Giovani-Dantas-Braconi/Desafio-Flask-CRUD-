# Desafio: Construindo um E-commerce com Python e API

## Descrição do Desafio
Neste desafio, você deverá desenvolver o back-end de um e-commerce utilizando Python e uma API REST com Flask ou FastAPI. Todo o código deverá ser escrito no Google Colab.

O objetivo é criar um sistema modular e bem estruturado, utilizando Programação Orientada a Objetos (POO) para gerenciar os recursos do e-commerce, como usuários, produtos, pedidos e pagamentos.

--------------------------------------------------

## Objetivos do Projeto

- Construir um back-end funcional para um e-commerce, sem necessidade de front-end.
- Criar e organizar o sistema usando POO.
- Implementar uma API REST utilizando Flask ou FastAPI.
- Criar endpoints para CRUD de usuários, produtos e pedidos.
- Simular pagamentos e gestão de estoque.
- Trabalhar com banco de dados em JSON (ou SQLite, opcional).
- Garantir que o sistema seja modular e escalável.
- Escrever testes automatizados para garantir a qualidade do código.

--------------------------------------------------

## Tecnologias Recomendadas

- Python (3.10 ou superior)
- Google Colab para desenvolvimento
- Flask ou FastAPI para a API
- Banco de dados em JSON (ou SQLite, opcional)
- pytest/unittest para testes automatizados

--------------------------------------------------

## Estrutura do Projeto

/desafio-ecommerce
│-- ecommerce/
│   ├── models.py  (Classes POO: Usuário, Produto, Pedido)
│   ├── database.py  (Manipulação do banco de dados JSON)
│   ├── api.py  (Implementação da API REST)
│   ├── services.py  (Regras de negócio e lógica de aplicação)
│   ├── main.py  (Arquivo principal para rodar a aplicação)
│-- tests/
│   ├── test_models.py  (Testes das classes)
│   ├── test_api.py  (Testes dos endpoints)
│-- README.txt

--------------------------------------------------

## Requisitos Mínimos

1. Gerenciamento de Usuários:
   - Criar classe Usuario com atributos id, nome, email e senha.
   - Criar endpoints para cadastro, login e remoção de usuários.

2. Gestão de Produtos:
   - Criar classe Produto com atributos id, nome, preco e estoque.
   - Criar endpoints para listar, adicionar, atualizar e remover produtos.

3. Pedidos e Carrinho de Compras:
   - Criar classe Pedido com id, usuario_id, itens e status.
   - Criar endpoint para criação de pedidos, listagem e alteração de status.

4. Simulação de Pagamento:
   - Criar endpoint para simular pagamento e confirmar pedido.
   - Implementar regra que reduz o estoque ao confirmar compra.

5. Testes Automatizados:
   - Criar testes para garantir que os endpoints funcionam corretamente.
   - Criar testes para validar regras de negócio.

--------------------------------------------------

## Como Começar

1. Clone o repositório:
   git clone <URL_DO_REPOSITORIO>

2. Abra o Google Colab e importe os arquivos.

3. Escolha Flask ou FastAPI e implemente a API.

4. Teste localmente os endpoints da API usando Postman ou cURL.

5. Crie os testes automatizados.

6. Envie o link do notebook finalizado.

--------------------------------------------------

## Critérios de Avaliação

- Organização do código e uso correto de POO.
- Implementação dos endpoints de forma eficiente.
- Correta manipulação de dados e regras de negócio.
- Cobertura de testes para validar as funcionalidades.
- Clareza na documentação do código e uso adequado do Google Colab.

--------------------------------------------------

## Desafio Extra (Opcional)

Para aqueles que querem se destacar:
- Implementar autenticação JWT para proteger os endpoints.
- Criar um sistema de cupons de desconto.
- Gerar um relatório de vendas em JSON.

Boa sorte e que vença o melhor dev!
