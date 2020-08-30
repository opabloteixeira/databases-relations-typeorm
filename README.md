ativar no banco
CREATE EXTENSION IF NOT EXISTS "uuid-ossp";

### Banco de dados
- Clientes
- Produtos
- Pedidos 
  - chave estrangeira( cliente_id)
- PedidosProdutos (id, id_produto, id_pedidos quantidade, valor) 
  - chave estrangeira( pedido_id, produto_id)
