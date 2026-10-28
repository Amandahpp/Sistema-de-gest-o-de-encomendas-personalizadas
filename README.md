# Sistema de Gestão de Encomendas Personalizadas

## 1. Sobre o projeto

O Sistema de Gestão de Encomendas Personalizadas é um projeto acadêmico desenvolvido como parte da Atividade Prática Supervisionada (APS), com o objetivo de estudar e modelar uma solução tecnológica para auxiliar pequenas empresas e empreendedores que trabalham com produtos personalizados.

O sistema busca facilitar o gerenciamento de encomendas, desde o primeiro contato com o cliente até a produção e a entrega do pedido, centralizando informações e reduzindo falhas de comunicação, atrasos e erros durante o processo.

O estudo de caso considera empresas que trabalham com produtos como peças de chochê, canecas, brindes, artesanato, lembrancinhas e outros itens produzidos sob encomenda.

## 2. Problema identificado

Pequenos empreendedores frequentemente recebem encomendas por diferentes canais de comunicação, como WhatsApp, Instagram e atendimento presencial. Quando as informações ficam espalhadas em conversas, anotações e planilhas, podem ocorrer problemas como:

- Perda de informações sobre os pedidos.
- Erros nas especificações dos produtos personalizados.
- Dificuldade para acompanhar o andamento das encomendas.
- Falta de controle sobre prazos de produção e entrega.
- Alterações solicitadas pelos clientes sem registro adequado.
- Falhas na comunicação entre o cliente e a empresa.

Esses problemas podem comprometer a organização do negócio, a produtividade e a satisfação dos clientes.

## 3. Objetivo geral

Modelar um sistema de gestão de encomendas personalizadas que centralize as informações dos pedidos e permita acompanhar suas etapas, contribuindo para a organização dos processos e a redução de erros operacionais.

## 4. Objetivos específicos

- Identificar os principais problemas relacionados ao gerenciamento de encomendas personalizadas.
- Levantar os requisitos funcionais e não funcionais do sistema.
- Definir os atores envolvidos e suas responsabilidades.
- Modelar os processos de cadastro, orçamento, aprovação, produção e entrega dos pedidos.
- Representar a estrutura e o comportamento do sistema por meio de diagramas UML.
- Propor uma solução que possa ser adaptada às necessidades de pequenas empresas.

## 5. Público-alvo

O sistema destina-se principalmente a pequenos empreendedores e empresas que trabalham com produtos personalizados, incluindo:

- Lojas de produtos de crochê e produtos personalizados.
- Empresas de brindes corporativos.
- Confeitarias e empresas de lembrancinhas.
- Artesãos e produtores independentes.
- Pequenos negócios que trabalham com encomendas sob medida.

## 6. Funcionalidades propostas

### 6.1 Cadastro de clientes

Permitir o registro e a consulta dos dados dos clientes, facilitando a identificação e o acompanhamento de suas encomendas.

### 6.2 Cadastro de produtos personalizados

Registrar os tipos de produtos oferecidos, suas características, opções de personalização e informações relevantes para a elaboração dos pedidos.

### 6.3 Registro de encomendas

Permitir o cadastro de uma nova encomenda com informações como cliente, produto, quantidade, descrição da personalização, valor e prazo desejado para entrega.

### 6.4 Elaboração de orçamentos

Registrar os valores estimados dos pedidos e permitir que o orçamento seja enviado ao cliente para aprovação ou recusa.

### 6.5 Aprovação e alteração de pedidos

Registrar a aprovação do orçamento e as alterações solicitadas pelo cliente, mantendo um histórico das modificações realizadas.

### 6.6 Acompanhamento da produção

Permitir que a empresa atualize o andamento da encomenda conforme suas etapas de trabalho.

Exemplos de status:

- Aguardando aprovação do orçamento.
- Aguardando confirmação do pedido.
- Aguardando produção.
- Em produção.
- Aguardando retirada ou envio.
- Entregue.
- Cancelada.

### 6.7 Controle de prazos

Registrar as datas previstas para produção e entrega, permitindo identificar encomendas próximas do vencimento do prazo.

### 6.8 Registro de pagamentos

Registrar informações sobre valores, pagamentos realizados e valores pendentes, permitindo acompanhar a situação financeira de cada encomenda.

### 6.9 Consulta de encomendas

Permitir a pesquisa e a visualização dos pedidos por cliente, período, prazo de entrega ou situação atual.

## 7. Requisitos do sistema

### Requisitos funcionais

- **RF01:** O sistema deve permitir cadastrar e consultar clientes.
- **RF02:** O sistema deve permitir cadastrar produtos personalizados.
- **RF03:** O sistema deve permitir registrar encomendas.
- **RF04:** O sistema deve permitir elaborar e registrar orçamentos.
- **RF05:** O sistema deve registrar a aprovação ou recusa dos orçamentos.
- **RF06:** O sistema deve permitir registrar alterações nas encomendas.
- **RF07:** O sistema deve permitir atualizar o status de cada pedido.
- **RF08:** O sistema deve permitir registrar prazos de produção e entrega.
- **RF09:** O sistema deve permitir registrar pagamentos e valores pendentes.
- **RF10:** O sistema deve permitir consultar o histórico das encomendas.

### Requisitos não funcionais

- **RNF01:** O sistema deve possuir uma interface simples e intuitiva.
- **RNF02:** Os dados cadastrados devem ser armazenados de forma organizada.
- **RNF03:** O sistema deve proteger as informações pessoais dos clientes.
- **RNF04:** O sistema deve validar os dados obrigatórios antes de registrar uma encomenda.
- **RNF05:** O sistema deve permitir consultas de maneira eficiente.
- **RNF06:** O acesso às funcionalidades administrativas deve ser controlado conforme o perfil do usuário.

## 8. Atores do sistema

**Cliente:** fornece as informações necessárias para a encomenda, consulta o orçamento e aprova ou solicita alterações no pedido.

**Atendente ou vendedor:** cadastra clientes, registra encomendas, elabora orçamentos e acompanha as solicitações.

**Responsável pela produção:** consulta as especificações dos pedidos e atualiza o andamento da produção.

**Administrador:** gerencia os usuários e as configurações do sistema, além de consultar as informações administrativas.

Os atores e suas permissões serão definidos com maior precisão durante a modelagem dos requisitos.

## 9. Modelagem UML

O estudo de caso poderá utilizar os seguintes diagramas UML:

- **Diagrama de casos de uso:** apresenta os atores e as funcionalidades disponíveis.
- **Diagrama de classes:** representa as principais entidades, seus atributos, métodos e relacionamentos.
- **Diagrama de sequência:** demonstra a interação entre os atores e os componentes do sistema durante o registro e a aprovação de uma encomenda.
- **Diagrama de atividades:** representa o fluxo de trabalho desde a solicitação do orçamento até a entrega do produto.
- **Diagrama de estados:** demonstra as possíveis mudanças de estado de uma encomenda ao longo de seu ciclo de vida.

Os diagramas serão elaborados com base nos requisitos e nas regras de negócio definidos para o estudo de caso.

## 10. Regras de negócio iniciais

- **RN01:** Toda encomenda deve estar associada a um cliente cadastrado.
- **RN02:** Uma encomenda deve possuir a descrição do produto e de suas especificações de personalização.
- **RN03:** A produção somente poderá ser iniciada após a aprovação do orçamento e a confirmação do pedido, conforme as condições comerciais estabelecidas.
- **RN04:** Alterações solicitadas após a aprovação devem ser registradas e podem exigir uma nova aprovação do cliente.
- **RN05:** Toda encomenda deve possuir uma situação atualizada para permitir seu acompanhamento.
- **RN06:** A entrega deve ser registrada quando o pedido for efetivamente entregue ao cliente.
- **RN07:** O cancelamento de uma encomenda deve ser registrado no sistema, preservando seu histórico.

## 11. Resultados esperados

Espera-se que o estudo de caso apresente uma proposta de sistema capaz de melhorar a organização das encomendas personalizadas, facilitar o acompanhamento dos pedidos e reduzir problemas relacionados a informações incompletas, alterações não registradas e atrasos.

A modelagem UML deverá demonstrar como os diferentes usuários interagem com o sistema e como as informações circulam entre as etapas do processo.

## 12. Escopo do projeto

O projeto será desenvolvido inicialmente como um estudo de caso acadêmico, concentrado no levantamento de requisitos, na definição das regras de negócio e na elaboração dos diagramas UML.

A implementação de um sistema funcional não faz parte do escopo inicial, podendo ser considerada futuramente como uma evolução do projeto.

## 13. Considerações finais

O Sistema de Gestão de Encomendas Personalizadas propõe uma solução tecnológica para um problema comum em pequenos negócios. Por meio da modelagem de seus processos, o projeto busca demonstrar como a análise e o desenvolvimento de sistemas podem contribuir para melhorar a organização, a comunicação e o controle operacional de uma empresa.
