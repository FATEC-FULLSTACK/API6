

# Sprint 2


<p align="center">
      <img src="/Documentacao/img/fullstack.png" alt="Logo da Equipe FullStack">


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

A Sprint 2 teve como objetivo principal ampliar as capacidades de avaliação e enriquecimento das respostas do sistema. Nesta etapa, focamos em:

**1. Implementar o sistema de avaliação detalhada:**

- Permite ao usuário atribuir notas individuais (1-5) para cada resposta LLM
- Coleta feedback justificado para cada avaliação
- Armazena os dados para análise e retreinamento dos modelos (RLHF)


**2. Disponibilizar perguntas pré-definidas:**

- Banco com 30 perguntas sobre cuidados com Alzheimer
- Interface para seleção fácil dessas perguntas
- Acelera o processo de avaliação pelos usuários

**3. Implementar RAG (Retrieval-Augmented Generation):**

- Integração com base de dados vetorizada
- Respostas enriquecidas com referências científicas
- Melhoria na qualidade e confiabilidade das respostas

Essas funcionalidades representam um avanço significativo na capacidade do sistema de coletar feedback qualificado e fornecer respostas baseadas em evidências científicas.


<br>


<span id="dor">

## :badger: Definição de DOR (Definition of Ready - DOR)

O DOR define quando uma tarefa está pronta para ser trabalhada em uma sprint. O objetivo dessa Sprint foi implementar o fluxo básico de envio de prompts e exibição de respostas dos LLMs.

**Tarefa:** Sistema de avaliação de respostas (Frontend).

**Critérios de Aceitação:** 
1. Componente de avaliação com: Seleção de nota (1-5 estrelas) para cada LLM. Campo de texto para justificativa. Botão de submissão.
2. Validação para garantir que: Pelo menos uma avaliação foi fornecida. Justificativa tem no mínimo 20 caracteres.
3. Feedback visual após submissão

**Tarefa:** Banco de perguntas pré-definidas (Backend).

**Critérios de Aceitação:**
1. Endpoint GET /perguntas que retorna: Lista das 30 perguntas sobre Alzheimer. Categorização por tópicos (se aplicável). 
2. Modelo Pydantic para validação
3. Dados armazenados no MongoDB

**Tarefa:** Implementação RLHF (Backend).

**Critérios de Aceitação:**
1. Processo periódico que: Agrega avaliações dos usuários. Calcula métricas de performance. Gera relatório para análise.
2. Integração com sistema de treinamento
3. Documentação do fluxo de dados

**Tarefa:** Implementação RAG (Backend).

**Critérios de Aceitação:**
1. Integração com base vetorizada: Conexão com serviço de embeddings. Busca por similaridade. Limite de 3 referências por resposta.
2. Modificação do endpoint /chat para: Incluir referências nas respostas. Manter formato compatível com frontend. 
3. Tratamento de falhas na busca

**Tarefa:** Integração frontend-backend para avaliações.

**Critérios de Aceitação:**
1. Endpoint POST /avaliar que: Recebe estrutura completa de avaliação. Valida dados recebidos. Armazena no MongoDB.
2. Frontend deve: Coletar todos os campos necessários. Enviar via POST para /avaliar. Tratar respostas (sucesso/erro).


<br>


<span id="dod">

## :dog: Definição de DOD (Definition of Done - DOD)

O DOD define quando uma tarefa está concluída e pronta para ser entregue. Para esta sprint, os critérios obrigatórios:

1. Funcionalidade:
- Usuário pode avaliar cada resposta com nota e justificativa
- Banco de perguntas pré-definidas acessível e funcional
- Respostas incluem referências científicas quando aplicável
- Sistema coleta dados para RLHF

2. Qualidade:
- Código revisado via Pull Request

3. Performance:
- Tempo adicional do RAG < 3s em 95% dos casos
- Sistema de avaliação responde em < 1s

4. Documentação:
- Swagger atualizado com novos endpoints
- README com instruções para usar novas features
- Documentação técnica do fluxo RLHF


<br>


<span id="backlog">

## :dart: Backlog da Sprint

<p align="center">
      <img src="/Documentacao/img/backlogs2.png" alt="Backlog da Sprint">






