

# Sprint 1


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

A Sprint 1 teve como principal objetivo a entrega do **MVP (Produto Mínimo Viável)** da Plataforma de Treinamento de IA, estabelecendo as bases essenciais para a interação entre usuário e sistema.  

Nesta etapa inicial, desenvolvemos uma **interface funcional e intuitiva**, onde o usuário pode:  
- **Inserir uma pergunta** em um campo dedicado;  
- **Enviar a consulta** para processamento por dois modelos de linguagem (LLMs);  
- **Visualizar as respostas geradas**, exibidas lado a lado para comparação imediata.  

Essa funcionalidade representa o **núcleo da aplicação**, pois permite não apenas a interação básica, mas também **inicia o processo de avaliação comparativa** das respostas — um fundamento crítico para as próximas etapas de desenvolvimento, como feedback estruturado e aprimoramento dos modelos.  

Com essa entrega, garantimos que o sistema esteja **operacional, usável e pronto para evoluir** com as funcionalidades planejadas nas sprints seguintes.  


<br>


<span id="dor">

## :badger: Definição de DOR (Definition of Ready - DOR)

O DOR define quando uma tarefa está pronta para ser trabalhada em uma sprint. O objetivo dessa Sprint foi implementar o fluxo básico de envio de prompts e exibição de respostas dos LLMs.

**Tarefa:** Frontend da tela de prompts (Vue.js) - Criar interface com campo de input e botão de envio.

**Critérios de Aceitação:** 
1. Layout responsivo
2. Validação de input
3. Feedback visual durante loading

**Tarefa:** Backend da tela de prompts (FastAPI) - Criar endpoint POST /chat.

**Critérios de Aceitação:**
1. Receber JSON com prompt
2. Retornar status 200 (OK)
3. Retornar as respostas dos LLMs (OpenAI e Gemini)

**Tarefa:** Integração com OpenAI - Configurar API e formatar respostas.

**Critérios de Aceitação:**
1. Timeout de 15s
2. Tratamento de erros
3. Formato padrão de resposta

**Tarefa:** Integração com Gemini - Configurar API e formatar respostas.

**Critérios de Aceitação:**
1. Timeout de 15s
2. Tratamento de erros
3. Formato padrão de resposta 

**Tarefa:** Frontend das respostas (Vue.js) - Criar view com 2 colunas para exibição.

**Critérios de Aceitação:**
1. Criação de componente que mostra a resposta
2. O layout deve ser responsível
3. Duas colunas devem mostrar as respostas dos LLMs recebido do backend

**Tarefa:** Integração frontend-backend – frontend realizar requisição para as rotas do backend.

**Critérios de Aceitação:**
1. A página de prompt deverá realizar requisição POST com o input do usuário na rota /chat.
2. A página de prompt deverá receber a resposta do backend e mostrar as respostas das LLMs usando o componente de resposta.
3. Adicionar uma interface visual de loading enquanto o frontend espera a resposta do backend

**Tarefa:** Banco de dados das avaliações das respostas (MongoDB) - Criar coleção avaliacao.

Critérios de Aceitação:
1. Criar coleção "avaliacao" no MongoDB com o seguinte schema: {
    _id,
    llm1,
    llm2,
    endereco_ip_user,
    pergunta,
    resposta_llm1,
    resposta_llm2,
    avaliacao_llm1,
    avaliacao_llm2,
    feedback_usuario,
    melhor_performance
}
2. Criar modelo no FastApi que representa o schema avaliacao no banco.


<br>


<span id="dod">

## :dog: Definição de DOD (Definition of Done - DOD)

O DOD define quando uma tarefa está concluída e pronta para ser entregue. Para esta sprint, os critérios obrigatórios:

1. Funcionalidade:
- Usuário consegue enviar prompt e ver respostas lado a lado
- Tempo máximo de resposta: 20s (somando ambos LLMs)

2. Qualidade:
- Código revisado via Pull Request

3. Documentação:
- Swagger dos endpoints POST: /chat, POST: /avaliacao, PUT: /avaliacao, GET: /avaliacao, DELETE: /avaliacao
- README atualizado com instruções de deploy local


<br>


<span id="backlog">

## :dart: Backlog da Sprint

<p align="center">
      <img src="/Documentacao/img/backlogs1.png" alt="Backlog da Sprint">






