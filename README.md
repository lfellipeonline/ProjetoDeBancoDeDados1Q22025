# ProjetoDeBancoDeDados1Q22025
# 📦 Banco de Dados para E-commerce

Projeto acadêmico de modelagem e implementação de um banco de dados relacional para um sistema de e-commerce. Desenvolvido como parte da disciplina de **Modelagem de Banco de Dados** do curso de **Análise e Desenvolvimento de Sistemas** na UNINASSAU.

## 📚 Objetivo

Construir um banco de dados relacional normalizado até a Terceira Forma Normal (3FN), capaz de armazenar informações sobre:

- Usuários (clientes e administradores)
- Fornecedores
- Produtos
- Pedidos
- Itens de pedidos
- Pagamentos
- Entregas
- Avaliações de produtos

## 🛠️ Tecnologias Utilizadas

- **MySQL**
- **Workbench** para modelagem
- **SQL** para criação e manipulação dos dados
- **DB Fiddle** (ambiente de testes SQL online)
- **DB Diagram** (ferramenta visual para modelagem de banco de dados)

## 📐 Modelagem

O projeto inclui:

- Modelo Entidade-Relacionamento (MER)
- Modelo Relacional
- Script SQL de criação do banco
- Inserção de dados simulados
- Consultas SQL com finalidades reais de uso

## 📁 Estrutura das Tabelas

- `usuario(id_usuario, nome, email, senha, tipo)`
- `fornecedor(id_fornecedor, nome, cnpj)`
- `produto(id_produto, nome, descricao, categoria, preco, qtd_estoque, id_fornecedor)`
- `pedido(id_pedido, id_usuario, data_pedido, status)`
- `item_pedido(id_item_pedido, id_pedido, id_produto, quantidade, preco_unitario)`
- `pagamento(id_pagamento, id_pedido, tipo_pagamento, valor, data_pagamento)`
- `entrega(id_entrega, id_pedido, endereco, status_entrega)`
- `avaliacao(id_avaliacao, id_usuario, id_produto, nota, comentario)`

## 🧪 Consultas SQL

Exemplos implementados:

- Listagem de produtos com fornecedores
- Histórico de pedidos por cliente
- Cálculo do valor total por pedido
- Produtos mais vendidos
- Média de avaliações por produto
- Pedidos com entrega pendente

## 📄 Relatório

O projeto acompanha um relatório detalhado contendo:

- Objetivo
- Modelagem
- Normalização até a 3FN
- Justificativas técnicas
- Consultas comentadas

## 👥 Autores

- Luiz Felipe Rodrigues de Melo
- Nathan Mendonça da Silva
- Carla Valéria Alves da Silva
- Ikaro Dantas Totia da Silva
- Ester Neri Vanderlei
---
