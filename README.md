# projeto-bd-colab
criação e manipulação de um BD em SQLite

## O que o projeto faz

- Cria tabelas no banco SQLite
- Insere dados nas tabelas
- Mostra os dados com SELECT

- Usa JOIN para juntar as informações das tabelas

##  Diagrama ER
![Texto alternativo](https://github.com/user-attachments/assets/e5b48b45-253b-4366-8ec6-1e3bcc745aa9)

## Tabelas criadas

- **pessoas**: nome e idade  
- **produtos**: descrição, quantidade e preço de compra  
- **vendas**: mostra quem comprou, o que comprou e quanto pagou

As tabelas têm relacionamento com chaves estrangeiras.

## Estrutura do Banco  
| Tabela   | Descrição                  | Campos principais                     |  
|----------|----------------------------|---------------------------------------|  
| PESSOAS  | Cadastro de clientes       | `id`, `nome`, `idade`                 |  
| PRODUTOS | Itens disponíveis          | `id`, `descricao`, `estoque`, `preco` |  
| VENDAS   | Registro de transações     | `id_venda`, `id_pessoa`, `id_produto`, `quantidade` |  

## Conclusão
Este projeto demonstrou na prática:
✔ Criação de um banco de dados relacional 
✔ Implementação de chaves estrangeiras para integridade dos dados
✔ Geração de relatórios combinando informações múltiplas

## Ferramentas usadas

- Python
- SQLite (`sqlite3`)
- Google Colab
- GitHub

## Resultado

O código mostra no console quem comprou e por qual valor.

Exemplo:
Maria comprou 2x Camiseta por R$60,00
