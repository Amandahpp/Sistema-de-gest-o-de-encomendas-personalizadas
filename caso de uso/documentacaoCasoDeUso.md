# Caso de Uso — Gestão de produção de encomendas artesanais
 
| Campo | Descrição |
|---|---|
| **Caso de uso** | Gestão de produção de encomendas artesanais |
| **Ator principal** | Cliente |
| **Atores secundários** | Atendente, Responsável pela produção, Administrador |
| **Resumo** | O sistema busca facilitar o gerenciamento de encomendas, desde o primeiro contato com o cliente até a produção e a entrega do pedido, centralizando informações e reduzindo falhas de comunicação, atrasos e erros durante o processo. |
 
## Pré-condições
 
- O sistema deve estar disponível e configurado pelo Administrador.
- O Atendente e o Responsável pela produção devem estar cadastrados e autenticados no sistema.
- O Cliente deve fornecer as informações necessárias para a encomenda.
## Pós-condições
 
- A encomenda fica registrada no sistema com orçamento aprovado e com o status atualizado até a entrega.
- O histórico do pedido (dados do cliente, especificações, orçamento e andamento da produção) fica disponível para consulta.
## Fluxo principal
 
1. O Cliente entra em contato e informa o que deseja encomendar.
2. O Atendente verifica se o Cliente já tem cadastro no sistema.
3. O Atendente registra a encomenda com as especificações (produto, quantidade, personalização, prazo desejado).
4. O Atendente elabora o orçamento e o disponibiliza ao Cliente.
5. O Cliente consulta o orçamento.
6. O Cliente aprova o orçamento.
7. O sistema muda o status da encomenda para "Aprovada" e a encaminha para a produção.
8. O Responsável pela produção consulta as especificações do pedido.
9. O Responsável pela produção atualiza o andamento ("Em produção" e depois "Concluída").
10. O Atendente acompanha a solicitação e avisa o Cliente que o pedido está pronto.
11. O pedido é entregue e o sistema registra o status "Entregue".
12. O caso de uso é encerrado.
## Fluxos alternativos
 
### FA01 — Cliente não cadastrado (passo 2)
 
1. O sistema informa que o Cliente não está cadastrado.
2. O Atendente cadastra o Cliente com nome, telefone, e-mail e endereço.
3. O fluxo volta ao passo 3 do fluxo principal.
### FA02 — Cliente solicita alterações no pedido (passo 6)
 
1. O Cliente pede alterações nas especificações ou no orçamento.
2. O Atendente registra as alterações na encomenda.
3. O Atendente refaz o orçamento.
4. O fluxo volta ao passo 5 do fluxo principal.
### FA03 — Cliente recusa o orçamento (passo 6)
 
1. O Cliente não aprova o orçamento e desiste da encomenda.
2. O Atendente registra a recusa.
3. O sistema muda o status da encomenda para "Cancelada".
4. O caso de uso é encerrado.
## Fluxos de exceção
 
### FE01 — Dados obrigatórios incompletos ou inválidos (passo 3 ou FA01, passo 2)
 
1. O sistema identifica campos obrigatórios em branco ou com formato inválido, como telefone ou e-mail.
2. O sistema exibe uma mensagem indicando os campos que precisam ser corrigidos e não salva o registro.
3. O Atendente corrige as informações e o fluxo volta ao passo em que a exceção ocorreu.
