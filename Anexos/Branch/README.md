# API ADS 6º Semestre

# Projeto Plataforma de Treinamento de IA

<p align="center">
      <img src="/Anexos/img/fullstack.png" alt="Logo da Equipe FullStack">



# Estratégia de Branch do Projeto 📜

Este projeto adota um fluxo de trabalho baseado no Git Flow, com branches estruturados para rastreabilidade e organização. Abaixo estão as diretrizes principais:

<br>

## Branches Permanentes 📝

### Branch `main`

- ✅ **Versão estável** em produção
- 🔀 Merges permitidos apenas de:
  - `develop` (para releases)
- 🏷️ Tags de versão (ex: `v1.0.0`)

<br>

### Branch `develop`

- 🔄 Branch de integração contínua
- 🧪 Ambiente de pré-produção
- ⬅️ Recebe merges de `feature/*`

<br>

## Branches Temporários

### Branch `feature/<Jira-ID>/<nome-da-feature>`

- 🌱 Criada a partir de `develop`
- 🏷️ Padrão de nomenclatura:

`feature/<codigo-Jira>/<nome-da-tarefa>`

- Ex: `feature/FAT-15/feature-x`

<br>

### Branch `refactor/<Jira-ID>/<nome-da-feature>`

- 🌱 Criada a partir de `develop`
- 🏷️ Padrão de nomenclatura:

`refactor/<codigo-Jira>/<nome-da-tarefa>`

- Ex: `refactor/FAT-16/refatorando-x`

<br>

### Branch `fix/<Jira-ID>/<nome-da-feature>`

- 🌱 Criada a partir de `develop`
- 🏷️ Padrão de nomenclatura:

`fix/<codigo-Jira>/<nome-da-tarefa>`

- Ex: `fix/FAT-17/bug-x`

<br>




## Fluxo de Trabalho

**1. Criar branch:**
   ```bash
   git checkout -b docs/FAT-19/readme develop
   ```

<br>

**2. Commitar alterações:**
   ```bash
   git commit -m "FAT-19: docs: Correção da Documentação"
   ```

<br>

**3. Enviar para Revisão:**
   ```bash
   git push origin docs/FAT-19/readme
   ```

<br>

**4. Abrir Pull Request para:** `develop`

<br>





