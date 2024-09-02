# Hackaton-2024-Santo-Digital-Desafio-3

Backlog 
------
  **História de Usuário 1: Visualizar Vendas Totais**
  
Como um stakeholder da AdventureWorks, quero visualizar as vendas totais ao longo do tempo com granularidade ajustável, para que eu possa gerenciar e planejar as ações da empresa.

Critérios de Aceitação:
- Os dados de vendas devem ser exibidos em um gráfico de linha com granularidade ajustável (dias, semanas, meses, trimestres, anuais).
- Deve poder aplicar filtros por categorias de produto, regiões e canais de venda.
- O sistema deve identificar e destacar tendências e anomalias usando técnicas de machine learning.
Tarefas Técnicas:
- Implementar rota de API para buscar dados de vendas filtrados (Back-end).
- Criar função para ajustar granularidade e aplicar filtros (Engenheiro de Dados).
- Desenvolver interface de usuário para visualização de dados com gráficos de linha (Front-end).
- Implementar detecção de outliers usando machine learning (Head Data).
- Configurar ambiente de produção para suportar funcionalidades (DevOps).
Pontuação de Planning Poker: 8

---
  **História de Usuário 2: Visualizar Produtos e Métricas**
  
Como um stakeholder da AdventureWorks, quero visualizar produtos por categoria com métricas adicionais e capacidade de comparação, para que eu possa entender melhor as vendas por produto e categoria.

Critérios de Aceitação:
- Os produtos devem ser exibidos com métricas como receita, margem de lucro e número de clientes únicos.
- Deve poder comparar produtos e categorias diferentes dinamicamente com filtros aplicados.
- Relatórios devem ser exportados em formatos CSV, Excel e PDF.
- Deve poder agendar o envio automático dos relatórios por e-mail.
Tarefas Técnicas:
- Implementar API para buscar dados de produtos com métricas (Back-end).
- Criar função para comparação dinâmica de métricas (Engenheiro de Dados).
- Desenvolver interface para exibição de produtos e exportação de relatórios (Front-end).
- Implementar funcionalidade de agendamento de relatórios (Back-end).
- Configurar ambiente para exportação de relatórios e agendamento (DevOps).
Pontuação de Planning Poker: 13

---
  **História de Usuário 3: Visualizar Desempenho dos Vendedores**
  
Como um stakeholder da AdventureWorks, quero visualizar o desempenho dos vendedores com KPIs detalhados, para que eu possa identificar dificuldades e comparar o desempenho entre eles.

Critérios de Aceitação:
- O desempenho deve ser exibido com KPIs como taxa de conversão, valor médio do pedido e taxa de retenção de clientes.
- Deve poder visualizar os dados em diferentes períodos e comparar vendedores lado a lado em gráficos.
- O funil de vendas deve incluir detalhes do primeiro contato até o fechamento, com tempo médio para conversão e identificação de gargalos.
Tarefas Técnicas:
- Implementar API para buscar dados de desempenho dos vendedores (Back-end).
- Desenvolver lógica para cálculo e exibição dos KPIs e funil de vendas (Engenheiro de Dados).
- Criar interface para visualização de desempenho e comparação de vendedores (Front-end).
- Configurar ambiente para suportar análise de desempenho (DevOps).
Pontuação de Planning Poker: 8

---
  **História de Usuário 4: Visualizar Vendas por Região**
  
Como um stakeholder da AdventureWorks, quero visualizar vendas por região em mapas interativos, para que eu possa identificar padrões e planejar ações regionais.

Critérios de Aceitação:
- As vendas devem ser exibidas em mapas interativos com métricas como densidade de vendas, receita gerada e crescimento percentual.
- Deve poder segmentar visualizações por categorias de produtos e períodos de tempo.
- O sistema deve projetar tendências futuras por região usando machine learning.
Tarefas Técnicas:
- Implementar API para buscar dados de vendas regionais (Back-end).
- Desenvolver lógica de segmentação por categoria e tempo (Engenheiro de Dados).
- Criar interface com mapas interativos para visualização regional (Front-end).
- Implementar machine learning para projeção de tendências regionais (Head Data).
- Configurar ambiente para suportar visualização de mapas e machine learning (DevOps).
Pontuação de Planning Poker: 13

---
  **História de Usuário 5: Gerenciamento de Produtos**
  
Como um stakeholder da AdventureWorks, quero gerenciar registros de produtos com validação robusta e auditoria, para que eu possa manter informações precisas e atualizadas sobre os produtos.

Critérios de Aceitação:
- Usuário deve poder criar, atualizar e deletar registros de produtos com validação de dados e controle de versões.
- Todas as operações devem ser auditadas, registrando informações como quem fez a alteração e quando.
- Deve poder importar produtos em massa de arquivos CSV ou Excel.
- Deve ser possível definir e gerenciar categorias, subcategorias e atributos personalizados para os produtos.
Tarefas Técnicas:
- Implementar API para CRUD de produtos com validação e controle de versões (Back-end).
- Criar sistema de auditoria para rastreamento de alterações (Back-end).
- Desenvolver função de importação em massa de produtos (Back-end).
- Criar interface para gerenciamento de produtos, categorias e atributos (Front-end).
- Configurar ambiente para suportar operações de CRUD e importação em massa (DevOps).
Pontuação de Planning Poker: 13


Sprints
-
  Como não foi especificado nenhuma ferramenta e tecnologia que a equipe esteja confortável de utilizar não foi presumida nenhuma.

  **Sprint 1:**
- História de Usuário 1: Visualizar Vendas Totais
- Tarefas Iniciais para História #5: Gerenciamento de Produtos
  - Implementação da API básica para CRUD de produtos.
Dependências: Nenhuma dependência crítica.
Riscos: Configuração inicial da API e possíveis desafios na visualização de vendas.

---
  **Sprint 2:**
- História de Usuário 5: Gerenciamento de Produtos
  - Completar funcionalidades de CRUD, auditoria, e importação em massa.
Dependências: Finalização da API básica na Sprint 1.
Riscos: Complexidade no controle de versões e validação de dados.

---
  **Sprint 3:**
- História de Usuário 2: Visualizar Produtos e Métricas
  - A primeira parte focada na visualização e comparação dinâmica.
Dependências: Nenhuma dependência crítica.
Riscos: Integração dos filtros com a visualização.

---
  **Sprint 4:**
- História de Usuário 2: Visualizar Produtos e Métricas
  - Completar funcionalidades de exportação e agendamento de relatórios.
- História de Usuário 3: Visualizar Desempenho dos Vendedores
  - Foco nos KPIs e visualização gráfica.
Dependências: Nenhuma dependência crítica.
Riscos: Complexidade na exportação de relatórios.

---
  **Sprint 5:**
- História de Usuário 3: Visualizar Desempenho dos Vendedores
  - Foco no funil de vendas detalhado.
- História de Usuário 4: Visualizar Vendas por Região
  - Início com foco nas visualizações básicas.
Dependências: Nenhuma dependência crítica.
Riscos: Implementação do funil de vendas pode ser desafiadora.

---
  **Sprint 6:**
- História de Usuário 4: Visualizar Vendas por Região
  - Completar a funcionalidade com previsão de vendas.
Dependências: Nenhuma dependência crítica.
Riscos: Complexidade na implementação de machine learning para previsões.
