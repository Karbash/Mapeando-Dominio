# Sistema de Gerenciamento de Estoque

Este projeto é um sistema de gerenciamento de estoque que permite o rastreamento de produtos, definição de quantidades mínimas, notificações de alerta e automação de ordens de compra. O sistema é voltado para facilitar o controle de inventário e a tomada de decisões de compra com base no histórico de vendas.

## Funcionalidades

### 1. Rastreamento Individual de Produtos
Permite que cada produto tenha um número de identificação único e seja monitorado de forma detalhada.

- **Atributos**:
  - Número de identificação único
  - Nome
  - Quantidade em estoque
  - Quantidade mínima de estoque
  - Informações adicionais (como tamanho e cor)
  - Histórico de movimentações no estoque

### 2. Definição e Monitoramento de Quantidade Mínima de Estoque
Permite configurar um limite mínimo para cada produto. Quando o estoque atinge ou se aproxima deste limite, um alerta é enviado.

- **Notificação**:
  - Envio de alertas por e-mail e no sistema para produtos com estoque baixo.

### 3. Visualização do Histórico de Vendas e Estoque
Exibe relatórios de vendas e movimentações de estoque para análise de desempenho e tomada de decisões.

- **Dados Disponíveis**:
  - Quantidades vendidas por período
  - Lucro por produto
  - Tendências de vendas e movimentações de estoque ao longo do tempo

### 4. Gestão e Automação de Ordens de Compra
Permite a criação e o gerenciamento de ordens de compra, incluindo automação com base nas quantidades mínimas e nas tendências de vendas.

- **Funcionalidades**:
  - Geração automática de ordens de compra com base no estoque mínimo
  - Atualização e gerenciamento de ordens de compra
  - Integração com fornecedores para atualizações automáticas de prazos de entrega

### 5. Notificações de Alerta
O sistema envia alertas aos usuários quando o estoque de um produto se aproxima da quantidade mínima estabelecida.

- **Métodos de Alerta**:
  - E-mail
  - Notificações no próprio sistema

### 6. Integração com Fornecedores
Permite a integração com sistemas de fornecedores para atualizações automáticas sobre os prazos de entrega de novas remessas e status das ordens.

## Entidades de Domínio

1. **Produto**
   - Representa cada item no inventário com identificação única e informações adicionais para rastreamento preciso.

2. **Estoque**
   - Mantém o controle de quantidades e histórico de movimentações no sistema.

3. **Venda**
   - Armazena informações sobre vendas, incluindo data, quantidade e lucro por produto.

4. **Fornecedor**
   - Contém dados de fornecedores e informações de contato, permitindo a integração para atualizações de prazo de entrega.

5. **Ordem de Compra**
   - Registra as compras solicitadas e seu status, integrando-se com os fornecedores para controle de reabastecimento.

## Casos de Uso

1. **Rastreamento de Produtos**: Acompanhar movimentações de produtos no estoque.
2. **Monitoramento de Estoque Mínimo**: Configurar e receber alertas sobre quantidade mínima.
3. **Relatórios de Vendas e Estoque**: Visualizar relatórios de vendas, tendências e histórico de movimentações.
4. **Gestão de Ordens de Compra**: Criar, atualizar e gerenciar ordens de compra, com opção de automatização.
5. **Notificações de Estoque**: Enviar alertas por e-mail e no sistema para estoque baixo.
6. **Integração com Fornecedores**: Sincronizar status e prazos de entrega diretamente com os fornecedores.


