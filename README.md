# NeroniWear-Database
Projeto final de modelagem e implementação de banco de dados da loja física NeroniWear

 Projeto Final – Banco de Dados NeroniWear

Este repositório contém o projeto completo desenvolvido como avaliação final da disciplina **Modelagem de Banco de Dados**, implementado no **Supabase (PostgreSQL)** para atender às necessidades da loja física **NeroniWear**.

---

 1. Cenário

A NeroniWear é uma loja física especializada na venda de camisetas urbanas e casuais.  
O sistema foi desenvolvido para organizar:

- Cadastro de clientes  
- Telefones e endereços  
- Produtos e categorias  
- Controle de estoque  
- Fornecedores e preços  
- Registro de vendas (pedidos e itens)  
- Controle de pagamentos  

O objetivo é substituir controles manuais e melhorar o fluxo operacional da loja.

---

 2. Modelagem Conceitual

A modelagem conceitual foi criada com base no Modelo Entidade-Relacionamento (MER).

Entidades principais:

- CLIENTE  
- CLIENTE_TELEFONE  
- ENDERECO  
- USUARIO  
- CATEGORIA  
- PRODUTO  
- ESTOQUE  
- FORNECEDOR  
- PRODUTO_FORNECEDOR  
- PEDIDO  
- ITEM_PEDIDO  
- PAGAMENTO  

Diagramas disponíveis na pasta:

 **/diagramas**

Inclui:

- DER.drawio  
- DER.png/jpg  

---

 3. Modelagem Lógica

A modelagem lógica foi construída com base nas regras do modelo relacional:

- Definição de chaves primárias e estrangeiras  
- Definição dos relacionamentos 1:1, 1:N, N:N  
- Tipos de dados corretos (VARCHAR, INT, DATE, DECIMAL, BOOLEAN etc.)  
- Normalização das tabelas  

---

 4. Modelagem Física

Scripts SQL utilizados para criação do banco:  
`scripts/create_tables.sql`

Inclui comandos:

- CREATE TABLE  
- PRIMARY KEY  
- FOREIGN KEY  
- UNIQUE  
- RELACIONAMENTOS  

---

 5. Dados

Foram inseridos **500 registros em cada tabela**, conforme exigido na avaliação.

Scripts na pasta:

 `scripts/inserts.sql`

Tabelas populadas:

- cliente  
- cliente_telefone  
- endereco  
- usuario  
- categoria  
- produto  
- estoque  
- fornecedor  
- produto_fornecedor  
- pedido  
- item_pedido  
- pagamento  

---

 6. CRUD

As operações CRUD foram demonstradas no Supabase com prints disponíveis em:

 **/prints**

Operações realizadas:

- INSERT  
- SELECT  
- UPDATE  
- DELETE  

Para as tabelas:

✔ cliente  
✔ produto  
✔ pedido  

---

 7. Relatórios SQL

Foram construídas **10 consultas SQL** usando:

- Seleção  
- Filtros (WHERE)  
- Ordenação (ORDER BY)  
- Junções (JOIN)  
- Agregações (SUM, COUNT)  

Os prints estão em:

**/prints**

---

 8. Documentação Final

Incluído na pasta:

**/documentacao**

- PDF completo com explicação do sistema  
- Arquivo Word editável  

---

 9. Autor

**Aluno:** Marcelo de Almeida Neroni 
**Disciplina:** Modelagem de Banco de Dados  
**Instituição: Fatec Franca





