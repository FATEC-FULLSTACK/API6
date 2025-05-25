

# Sprint 3


<p align="center">
      <img src="/Anexos/img/fullstack.png" alt="Logo da Equipe FullStack">


<hr>
<br>
<p align="center">
  <a href ="#mvp"> MVP da Sprint</a>  | 
  <a href ="#dor"> DOR </a>  |
  <a href ="#dod"> DOD </a>  |
  <a href ="#backlog"> Backlog da Sprint</a>  
</p>

</p>

<span id="mvp">

## :bookmark_tabs: MVP da Sprint

A Sprint 3 focou em análise comparativa avançada e integração com fontes científicas, consolidando o sistema como uma ferramenta robusta para avaliação de LLMs. As principais entregas foram:

**1. Comparação final de respostas avaliadas:**

- Interface para atribuição de nota global (1-5) a cada LLM após análise individual
- Campo de justificativa detalhada para a decisão final
- Armazenamento de métricas para priorização automática do melhor modelo


**2. Integração com base científica vetorizada:**

- Consumo de 15.000 artigos científicos (Dom Rock) via RAG
- Respostas enriquecidas com referências validadas e contextualizadas

**3. Dashboard de desempenho:**

- Visualização gráfica comparativa (em barras) entre os LLMs
- Métricas baseadas em avaliações humanas (média de notas, tendências)

**4. Documentação e pipeline de RLHF:**

- Guias técnicos para integração e manutenção do sistema
- Configuração inicial do pipeline de Reinforcement Learning from Human Feedback (RLHF) para fine-tuning contínuo

Essas funcionalidades elevam a plataforma a um patamar estratégico, permitindo decisões baseadas em dados científicos e feedback qualificado.


<br>


<span id="dor">

## :badger: Definição de DOR (Definition of Ready - DOR)

O DOR define quando uma tarefa está pronta para ser trabalhada em uma sprint.

**Tarefa:** Comparação final de respostas (Frontend)

**Critérios de Aceitação:**
1. Componente com:
      - Seleção de nota global (1-5) para cada LLM
      - Campo de justificativa (mín. 30 caracteres)
      - Botão para submeter decisão final

**Tarefa:** Integração com base científica (Backend)

**Critérios de Aceitação:**
1. Conexão com API da Dom Rock para buscar artigos
2. Limite de 5 referências por resposta

**Tarefa:** Dashboard de desempenho (Frontend/Backend)

**Critérios de Aceitação:**
1. Gráfico de barras comparativas (duplas) para cada LLM contendo:
      - Barra esquerda (azul): Número total de participações (vezes que o LLM respondeu a perguntas)
      - Barra direita (verde): Número de vezes que foi avaliado como "melhor desempenho"
      - Ordenação decrescente (LLM com mais participações à esquerda)
2. Legenda clara e eixos identificados (LLMs no eixo X, contagem no eixo Y)
3. Tooltips interativos mostrando:
      - Números absolutos
      - A quantidade total que o LLM participou da avaliação e obteve o melhor desempenho

**Tarefa:** Pipeline RLHF (Backend)

**Critérios de Aceitação:**
1. Script para extrair avaliações do MongoDB

**Tarefa:** Documentação técnica

**Critérios de Aceitação:**
1. Guia do usuário do sistema

<br>


<span id="dod">

## :dog: Definição de DOD (Definition of Done - DOD)

O DOD define quando uma tarefa está concluída e pronta para ser entregue. Para esta sprint, os critérios obrigatórios:

1. Funcionalidade:
- Comparação final implementada e funcional
- Dashboard exibe gráficos com dados reais
- Respostas incluem referências científicas em 95% dos casos

2. Qualidade:
- Código revisado e testado
- Dados exibidos consistentes com o banco de dados
- Pipeline RLHF documentado e replicável

3. Performance:
- Busca na base científica ≤ 2s
- Dashboard carrega em ≤ 1.5s
- Atualização dos gráficos em ≤ 0.5s após filtragem

4. Documentação:
- Swagger atualizado com novos endpoints
- README com instruções para acesso ao dashboard


<br>


<span id="backlog">

## :dart: Backlog da Sprint

<p align="center">
      <img src="/Anexos/img/backlogs3.png" alt="Backlog da Sprint">






