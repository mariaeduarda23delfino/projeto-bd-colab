# projeto-bd-colab
criação e manipulação de um BD em SQLite

## O que o projeto faz

- Cria tabelas no banco SQLite
- Insere dados nas tabelas
- Mostra os dados com SELECT
- Usa JOIN para juntar as informações das tabelas

## Tabelas criadas

- **pessoas**: nome e idade  
- **produtos**: descrição, quantidade e preço de compra  
- **vendas**: mostra quem comprou, o que comprou e quanto pagou

As tabelas têm relacionamento com chaves estrangeiras.

## Ferramentas usadas

- Python
- SQLite (`sqlite3`)
- Google Colab
- GitHub

## Resultado

O código mostra no console quem comprou e por qual valor.

Exemplo:
Maria comprou 2x Camiseta por R$60.0
João comprou 1x Sapato por R$150.0
