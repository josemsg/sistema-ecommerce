# 📦 Sistema de E-commerce

Este repositório contém a modelagem conceitual de um banco de dados para um sistema de e-commerce. O objetivo do projeto é estruturar uma base de dados eficiente e escalável, permitindo a gestão de produtos, clientes, pedidos, fornecedores e estoque.

## 📌 Escopo do Projeto

O sistema de e-commerce terá as seguintes funcionalidades:

### 🛒 Cadastro de Clientes (PJ e PF)
- Um cliente pode ser **Pessoa Jurídica (PJ)** ou **Pessoa Física (PF)**, mas não pode possuir ambas as classificações no mesmo registro.
- Os dados do cliente incluem **CPF ou CNPJ**, nome e endereço para cálculo do frete.

### 📦 Gerenciamento de Produtos
- Os produtos podem ser vendidos por diferentes fornecedores dentro da plataforma.
- Cada produto está vinculado a um fornecedor e pode compor um ou mais pedidos.

### 💳 Pedidos e Pagamentos
- O cliente pode criar um pedido contendo um ou mais produtos.
- O pedido pode ser pago utilizando **diferentes formas de pagamento** (ex: cartão de crédito, boleto, PIX, etc.).
- Os pedidos podem ser cancelados dentro de um prazo estabelecido.

### 🚚 Entrega e Rastreamento
- Cada pedido possui um **status de entrega** (ex: aguardando envio, em transporte, entregue).
- O sistema armazena um **código de rastreio** para monitoramento da entrega.
- O pedido inclui informações sobre **data de envio e previsão de entrega**.

## 🏗️ Estrutura do Projeto

Este projeto inclui:
- **Diagrama Entidade-Relacionamento (DER)** para modelagem do banco de dados.
- **Scripts SQL** para criação das tabelas e inserção de dados de teste.
- **Documentação** detalhando as regras de negócio e as relações entre as entidades.

## 🛠️ Tecnologias Utilizadas

- **Banco de Dados:** MySQL / PostgreSQL (ou outro banco relacional)
- **Ferramentas de Modelagem:** Draw.io, MySQL Workbench, DB Designer
- **Linguagens e Frameworks:** SQL

## 📜 Licença

Este projeto é de código aberto e pode ser utilizado para fins acadêmicos ou profissionais.
