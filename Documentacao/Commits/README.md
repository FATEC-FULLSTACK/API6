# API ADS 6º Semestre

# Projeto Plataforma de Treinamento de IA

<p align="center">
      <img src="/Documentacao/img/fullstack.png" alt="Logo da Equipe FullStack">



# Padrões de commits 📜

De acordo com a documentação do **[Conventional Commits](https://www.conventionalcommits.org/pt-br)**, commits semânticos são uma convenção simples para ser utilizada nas mensagens de commit. Essa convenção define um conjunto de regras para criar um histórico de commit explícito, o que facilita a criação de ferramentas automatizadas.

Esses commits auxiliarão a equipe a entender de forma facilitada quais alterações foram realizadas no trecho de código que foi commitado.

Essa identificação ocorre por meio de uma palavra que identifica se aquele commit realizado se trata de uma alteração de código, atualização de pacotes, documentação, alteração de visual, teste.

<br>

## Tipo e descrição 📝



O **type** é responsável por nos dizer qual o tipo de alteração ou iteração está sendo feita. Das regras da convenção, temos os seguintes tipos:

- **test**: Indica qualquer tipo de criação ou alteração de códigos de teste.  
  **Exemplo:** test: Criação de testes unitários.

- **feat**: Indica o desenvolvimento de uma nova feature ao projeto.  
  **Exemplo:** feat: Acréscimo de um serviço, funcionalidade, endpoint, etc.

- **refactor**: Usado quando houver uma refatoração de código que não tenha qualquer tipo de impacto na lógica/regras de negócio do sistema.  
  **Exemplo:** refactor: Mudanças de código após um code review.

- **style**: Empregado quando há mudanças de formatação e estilo do código que não alteram o sistema de nenhuma forma.  
  **Exemplo:** style: Mudar o style-guide, mudar de convenção lint, arrumar indentações, remover espaços em brancos, remover comentários, etc.

- **fix**: Utilizado quando há correção de erros que estão gerando bugs no sistema.  
  **Exemplo:** fix: Aplicar tratativa para uma função que não está tendo o comportamento esperado e retornando erro.

- **chore**: Indica mudanças no projeto que não afetem o sistema ou arquivos de testes. São mudanças de desenvolvimento.  
  **Exemplo:** chore: Mudar regras do eslint, adicionar prettier, adicionar mais extensões de arquivos ao `.gitignore`.

- **docs**: Usado quando há mudanças na documentação do projeto.  
  **Exemplo:** docs: Adicionar informações na documentação da API, mudar o README, etc.

- **build**: Utilizada para indicar mudanças que afetam o processo de build do projeto ou dependências externas.  
  **Exemplo:** build: Gulp, adicionar/remover dependências do npm, etc.

- **perf**: Indica uma alteração que melhorou a performance do sistema.  
  **Exemplo:** perf: Alterar `ForEach` por `while`, melhorar a query ao banco, etc.

- **ci**: Utilizada para mudanças nos arquivos de configuração de CI.  
  **Exemplo:** ci: Circle, Travis, BrowserStack, etc.

- **revert**: Indica a reversão de um commit anterior.  
  **Exemplo:** revert: Reverter um commit que introduziu um bug.



<br>

